[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/cdwr/simpleSSH">
    <img src="https://www.dmuth.org/wp-content/uploads/2020/01/ssh.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Simple SSH</h3>
  
<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://github.com/cdwr/simpleSSH)

This is an C example for a simple SSH client/server. It's configured to run on the localhost, but can be configured to run over most networks. 

### Built With

The SSH server and client were built for linux usage, and compiled with gcc. All dependencies 

* [gcc](https://gcc.gnu.org/)


<!-- GETTING STARTED -->
## Getting Started

To run the filesystem, you'll need an up-to-date linux distribution. This filesystem was created in Ubuntu, but others should work fine.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* gcc
  ```sh
  sudo apt install build-essential
  ```
  ```sh
  sudo apt-get install manpages-dev
  ```
* ext2fs/ext2_fs.h
  ```sh
  sudo apt-get install e2fslibs-dev
  ```

### Installation

1) Clone the repo
   ```sh
   git clone https://github.com/cdwr/simpleSSH/
   ```
2) Check prerequisites

<!-- USAGE EXAMPLES -->
## Usage

Use case 1 (recommended):
  1) Run the command utility:
     ```sh
     ./a.out
     ```
  2) Use the tools. All tools are simplified versions of Unix filesystem editing commands. Commands include:
     ```sh
     ls
     cd
     pwd
     mkdir
     create
     rmdir
     rmfile
     link
     symlink
     unlink
     open
     close
     pfd
     lseek
     cat
     cp
     dup
     dup2
     write
     mount
     umount
     quit
     ```
     

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- CONTACT -->
## Contact

Chris Wilson - [@Chris Wilson](https://www.linkedin.com/in/chris-wilson-55882816b/)

Project Link: [https://github.com/cdwr/simpleSSH](https://github.com/cdwr/simpleSSH)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/cdwr/simpleSSH.svg?style=for-the-badge
[contributors-url]: https://github.com/cdwr/simpleSSH/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/cdwr/simpleSSH.svg?style=for-the-badge
[forks-url]: https://github.com/cdwr/simpleSSH/network/members
[issues-shield]: https://img.shields.io/github/issues/cdwr/simpleSSH.svg?style=for-the-badge
[issues-url]: https://github.com/cdwr/simpleSSH/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/chris-wilson-55882816b/
[product-screenshot]: https://www.science.unitn.it/~fiorella/guidelinux/tlk/img84.gif
