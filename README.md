[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h3 align="center">Multithreaded Web Server</h3>

  <p align="center">
    It's a web server that says “hello” and to complete my journey in The Rust Programming Language book.
    <br />
    <a href="https://github.com/ccr5/multithreaded-web-server-rust"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/ccr5/multithreaded-web-server-rust/issues">Report Bug</a>
    ·
    <a href="https://github.com/ccr5/multithreaded-web-server-rust/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Here is our plan for building the web server:

1. Learn a bit about TCP and HTTP.
2. Listen for TCP connections on a socket.
3. Parse a small number of HTTP requests.
4. Create a proper HTTP response.
5. Improve the throughput of our server with a thread pool.



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

* Rust ^1.26.0

### Installation

1. Clone this repository
```shell
git clone https://github.com/ccr5/multithreaded-web-server-rust.git
```
2. Install <a href="https://linuxhint.com/rust-programming-language-ubuntu-2204/">dependencies</a>
3. Run Blackjack
```shell
cargo run 
```



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Matheus Nobre Gomes - matt-gomes@live.com

Project Link: [https://github.com/ccr5/multithreaded-web-server-rust](https://github.com/ccr5/multithreaded-web-server-rust)



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/ccr5/multithreaded-web-server-rust.svg?style=for-the-badge
[contributors-url]: https://github.com/ccr5/multithreaded-web-server-rust/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/ccr5/multithreaded-web-server-rust.svg?style=for-the-badge
[forks-url]: https://github.com/ccr5/multithreaded-web-server-rust/network/members
[stars-shield]: https://img.shields.io/github/stars/ccr5/multithreaded-web-server-rust.svg?style=for-the-badge
[stars-url]: https://github.com/ccr5/multithreaded-web-server-rust/stargazers
[issues-shield]: https://img.shields.io/github/issues/ccr5/multithreaded-web-server-rust.svg?style=for-the-badge
[issues-url]: https://github.com/ccr5/multithreaded-web-server-rust/issues
[license-shield]: https://img.shields.io/github/license/ccr5/multithreaded-web-server-rust.svg?style=for-the-badge
[license-url]: https://github.com/ccr5/multithreaded-web-server-rust/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/mattnobre
[product-screenshot]: img/logo.jpeg
