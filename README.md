<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
<div align="center">
  
  [![Contributors][contributors-shield]][contributors-url]
  [![Forks][forks-shield]][forks-url]
  [![Stargazers][stars-shield]][stars-url]
  [![Issues][issues-shield]][issues-url]
  [![MIT License][license-shield]][license-url]
</div>


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/stayintarkov/SIT.Manager.Avalonia">
    <img src="SIT.Manager/Assets/sit-logo-5.png" alt="Logo" height="240">
  </a>

<h3 align="center">SIT.Manager.Avalonia</h3>

  <p align="center">
    An Avalonia based manager for SIT
    <br />
    <a href="https://github.com/stayintarkov/SIT.Manager.Avalonia/releases/latest"><strong>Latest Release »</strong></a>
    <br />
    <br />
    <a href="https://github.com/stayintarkov/SIT.Manager.Avalonia/issues">Report Bug</a>
    ·
    <a href="https://github.com/stayintarkov/SIT.Manager.Avalonia/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
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
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contactsupport">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

![Project Screen Shot][project-image]

This project is a rewrite of the [SIT.Manager](https://github.com/stayintarkov/SIT.Manager) in an attempt to create a long lasting, maintainable and helpful manager for SIT. In addition to bringing the functionality from the previous manager this project plans to bring multiple new features to improve the experience.



### Built With

* [![.NET][dotnet-shield]][dotnet-site]
* [![Avalonia][avalonia-shield]][avalonia-repo]

<br>

## Supported Platforms

* Windows 10
* Windows 11
* Ubuntu 22
 * Arch*

 \* = Additional steps may be required

<!-- GETTING STARTED -->
## Getting Started

This installation guide is the recommended way of structuring your SIT install

### Installation

1. Create a new folder to contain your SIT installation
2. Create 3 new folders inside your new folder. `sit-game`, `sit-manager` and `sit-server`
3. Download the [latest release](https://github.com/stayintarkov/SIT.Manager.Avalonia/releases/latest)
4. Extract the zip into your `sit-manager` folder
5. <b>(OPTIONAL)</b> Find the file called `SIT.Manager.Avalonia.Desktop.exe` and create a shortcut


<!-- USAGE -->
## Usage

You can find all the information you need on how to setup and run SIT in the [docs](https://docs.stayintarkov.com)

_For questions about usage and support please refer to the [SIT Discord](https://discord.gg/f4CN4n3nP2) for now_


<!-- ROADMAP -->
## Roadmap

- [x] Revamped installation system
    - [ ] Overhauled mod installation
- [ ] New play page
    - [ ] Server bookmarking/saving
    - [ ] Character manager
    - [ ] Character editor
- [ ] Character backups
- [x] Log package generator

See the [open issues](https://github.com/stayintarkov/SIT.Manager.Avalonia/issues) for a full list of proposed features (and known issues).


<!-- CONTRIBUTING -->
## Contributing

Any contributions you make are **greatly appreciated** by all of us <3

If you have a suggestion that would make this better, please fork the repo and create a pull request or open an issue with the tag "enhancement"


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* A huge thanks to [Artehe](https://github.com/artehe) for all their contributions that helped bring the manager to life
* [J0nathan550](https://github.com/J0nathan550) For all their work on the localization system, Russian & Ukrainian localizations, fixes, and tweaks
* [JimWails](https://github.com/JimWails) For adding Chinese localizations
* [Plootie](https://github.com/Plootie) For starting the development of the avalonia manager and various contributions


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.


<!-- CONTACT -->
## Contact/Support

Support is best found in the [SIT Discord](https://discord.gg/f4CN4n3nP2)


<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- Credits -->
## Project Credits
* [Avalonia](https://avaloniaui.net/) for our UI framework
* [FluentAvalonia](https://github.com/amwx/FluentAvalonia) for additional controls and themes
* [adams85 filelogger](https://github.com/adams85/filelogger) for our file logging
* [MegaApiClient](https://github.com/gpailler/MegaApiClient) for downloading mega files
* [PeNet](https://github.com/secana/PeNet) for reading executable data
* [SharpCompress](https://github.com/adamhathcock/sharpcompress) for better compression methods


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/stayintarkov/SIT.Manager.Avalonia.svg?style=for-the-badge
[contributors-url]: https://github.com/stayintarkov/SIT.Manager.Avalonia/graphs/contributors

[forks-shield]: https://img.shields.io/github/forks/stayintarkov/SIT.Manager.Avalonia.svg?style=for-the-badge
[forks-url]: https://github.com/stayintarkov/SIT.Manager.Avalonia/network/members

[stars-shield]: https://img.shields.io/github/stars/stayintarkov/SIT.Manager.Avalonia.svg?style=for-the-badge
[stars-url]: https://github.com/stayintarkov/SIT.Manager.Avalonia/stargazers

[issues-shield]: https://img.shields.io/github/issues/stayintarkov/SIT.Manager.Avalonia.svg?style=for-the-badge
[issues-url]: https://github.com/stayintarkov/SIT.Manager.Avalonia/issues

[license-shield]: https://img.shields.io/github/license/stayintarkov/SIT.Manager.Avalonia.svg?style=for-the-badge
[license-url]: https://github.com/stayintarkov/SIT.Manager.Avalonia/blob/master/LICENSE.txt

[project-image]: images/manager-sc.png

[avalonia-repo]: https://github.com/AvaloniaUI/Avalonia
[avalonia-shield]: https://img.shields.io/badge/Avalonia-8b44ac?style=for-the-badge

[dotnet-site]: https://dotnet.microsoft.com/en-us/
[dotnet-shield]: https://img.shields.io/badge/dotnet-512BD4?style=for-the-badge&logo=dotnet&logoColor=white
