<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/roebi/01-05-dev-env-setup-basestep-for-jvm">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">01-05 development environment setup basestep for jvm (Java Virtual Machine)</h3>

  <p align="center">
    development environment setup basestep for jvm (Java Virtual Machine)
    <br />
    <a href="https://github.com/roebi/01-05-dev-env-setup-basestep-for-jvm"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/roebi/01-05-dev-env-setup-basestep-for-jvm">View Demo</a>
    ·
    <a href="https://github.com/roebi/01-05-dev-env-setup-basestep-for-jvm/issues">Report Bug</a>
    ·
    <a href="https://github.com/roebi/01-05-dev-env-setup-basestep-for-jvm/issues">Request Feature</a>
  </p>
</div>


<!-- TABLE OF CONTENTS -->
<!-- to create the correct #anchor: use Markdown Header in lowercase -->
<!-- and replace spaces with hypens -->
<!-- and replace special chars with hypens -- >
<!-- then two or more hyphens in a row are converted to one -->
<!-- special case is here with special chars - see example with & -->
<!-- https://stackoverflow.com/questions/43273842/what-are-the-rules-of-converting-one-markdown-title-into-an-html-anchor -->
<!-- Example: '### Prerequisites' -> '#prerequisites' -->
<!-- Example: '## Getting Started' -> '#getting-started' -->
<!-- Example: '## About The Project' -> '#about-the-project' -->
<!-- Example: '## Credit & Thanks' -> '#credit--thanks' -->
<details>
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
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
    <li><a href="#credit--thanks">Credit & Thanks</a></li>
    <li><a href="#readme-templates">README templates</a></li>
    <li><a href="#markdown-basic-syntax">Markdown basic syntax</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Built With

* sdkman
* zulu fx java 17
* gradle 8
<!--
* [![Next][Next.js]][Next-url]
* [![React][React.js]][React-url]
* [![Vue][Vue.js]][Vue-url]
* [![Angular][Angular.io]][Angular-url]
* [![Svelte][Svelte.dev]][Svelte-url]
* [![Laravel][Laravel.com]][Laravel-url]
* [![Bootstrap][Bootstrap.com]][Bootstrap-url]
* [![JQuery][JQuery.com]][JQuery-url]
 -->
<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

To setup a development environment (needed basestep) for jvm (Java Virtual Machine) (Java, Scala, Kotlin, Groovy) you have three choices

* local
* Podman Dockerfile (local ide and Podman Desktop, tools and libs in a Dockerfile)
* Cloud (remote development, remote ide, i.E. GitPod)

We focus on **local**.

let start local development

### Prerequisites (skdman)

assumend, you have installed
* git
  * on windows
  * git for windows
  * tortoise git
* and a ide, for example intellij

first we install [sdkman][sdkman-url]
* git bash
  ```bash
  curl -s "https://get.sdkman.io" | bash
  ```
  this downloads a bash script from sdkman.io and execute it in a bash. This installs sdkman. Follow the instructions in the terminal.

### Installation (zulu fx java 17 and gradle 8)

* optional - clone / fork / or use it as template - the repo if you need the README.md
   ```bash
   git clone https://github.com/roebi/01-05-dev-env-setup-basestep-for-jvm.git
   ```
* Install the latest zulu java fx 17 LTS
   ```bash
    // sdk list java // list all available java
    sdk install java 17.0.8.fx-zulu
   ```

* Install the latest gradle non rc  fx 17 LTS
   ```bash
    // sdk list gradle // list all available gradle
    sdk install gradle 8.2.1
   ```

   #### Remark
   In the first time you use the whole **Gradle** Installation. This is used for your first project. In this Project then Gradle install a smaller **Gradle Wrapper**. This Gradle Wrapper, started with **gradlew* is then used to run gradle tasks.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- USAGE EXAMPLES -->
## Usage

to setup Gradle Projects

you simply start with the **Gradle init Task**

setup a gradle project
```bash
gradle init
```
then Gradle comes up with some questions...

```bash
Starting a Gradle Daemon, 1 busy and 1 incompatible and 1 stopped Daemons could not be reused, use --status for details

Select type of project to generate:
  1: basic
  2: application
  3: library
  4: Gradle plugin
Enter selection (default: basic) [1..4]
```
cancel the task here, with Ctrl-C

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## target reached

**Now you are ready to setup a gradle project**

**for**

**a JVM Application**

**a JVM Library**

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ROADMAP -->
## Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
    - [ ] Nested Feature

See the [open issues](https://github.com/roebi/01-05-dev-env-setup-basestep-for-jvm/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- LICENSE -->
## License

Distributed under The Unlicense. See `LICENSE.txt` for more information.

Do not forget do mention Best-README-Template from Github User othneildrew, if you reuse the REAMDME.md file from  this Git Repo.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Your Name - [@roberthalter](https://twitter.com/roberthalter) - email@email_client.com

Project Link: [https://github.com/roebi/01-05-dev-env-setup-basestep-for-jvm](https://github.com/roebi/01-05-dev-env-setup-basestep-for-jvm)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CREDIT & THANKS -->
## Credit & Thanks

* the base Structure of this README.md and BLANK_ROEBI_README.md and BLANK_README.md is based on the
 [Best-README-Template from Github User othneildrew][readme-credit-url] licensed by [MIT][readme-license-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- README templates -->
## README templates

feel free to use a other README.md template in your project:

* [Github Search by topic 'readme-template'][readme-template-topic-url]
* [Awesome README - a curated list of awesome READMEs][awesome-readme-template-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN-BASIC-SYNTAX -->
## Markdown basic syntax
 * [Markdown Basic Syntax][markdown-basic-syntax]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES - DO NOT DELETE - used as link references -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

<!-- shields.io Links start -->

<!-- Docu of Badges ifrom shields.io -->
[shields-badges-url]: https://shields.io/badges

<!-- shields.io/github Links -->

[contributors-shield]: https://img.shields.io/github/contributors/roebi/01-05-dev-env-setup-basestep-for-jvm.svg?style=for-the-badge
[contributors-url]: https://github.com/roebi/01-05-dev-env-setup-basestep-for-jvm/graphs/contributors

[forks-shield]: https://img.shields.io/github/forks/roebi/01-05-dev-env-setup-basestep-for-jvm.svg?style=for-the-badge
[forks-url]: https://github.com/roebi/01-05-dev-env-setup-basestep-for-jvm/network/members

[stars-shield]: https://img.shields.io/github/stars/roebi/01-05-dev-env-setup-basestep-for-jvm.svg?style=for-the-badge
[stars-url]: https://github.com/roebi/01-05-dev-env-setup-basestep-for-jvm/stargazers

[issues-shield]: https://img.shields.io/github/issues/roebi/01-05-dev-env-setup-basestep-for-jvm.svg?style=for-the-badge
[issues-url]: https://github.com/roebi/01-05-dev-env-setup-basestep-for-jvm/issues

[license-shield]: https://img.shields.io/github/license/roebi/01-05-dev-env-setup-basestep-for-jvm.svg?style=for-the-badge
[license-url]: https://github.com/roebi/01-05-dev-env-setup-basestep-for-jvm/blob/master/LICENSE.txt

<!-- shields.io/-LinkedIn Static Badge -->

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/https://ch.linkedin.com/in/robert-halter-814818a4
[product-screenshot]: images/screenshot.png

<!-- shields.io/ 'Built With' Badge -->

[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/

[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/

[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/

[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/

[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/

[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com

[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com

[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com

<!-- shields.io Links end -->

<!-- readme credit Links -->

[readme-credit-url]: https://github.com/othneildrew/Best-README-Template
[readme-license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt

[readme-template-topic-url]: https://github.com/topics/readme-template
[awesome-readme-template-url]: https://github.com/matiassingers/awesome-readme

<!-- Markdown Links -->

[markdown-basic-syntax]: https://www.markdownguide.org/basic-syntax

<!-- more Links here -->

[sdkman-url]: https://sdkman.io/
