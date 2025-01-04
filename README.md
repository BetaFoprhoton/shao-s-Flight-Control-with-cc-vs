<a id="readme-top"></a>
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![project_license][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/super95shao/shao-s-Flight-Control-with-cc-vs">
  <!--让AI画了个临时logo :) -->
    <img src="image/temporary-logo.png" alt="Logo" width="80" height="80">
    
  </a>

<h3 align="center">Shao's Flight Control</h3>

  <p align="center">
    A powerful universal flight control designed for VS ships
    <br />
    <a href="https://github.com/super95shao/shao-s-Flight-Control-with-cc-vs"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/super95shao/shao-s-Flight-Control-with-cc-vs/issues/new">Report Bug</a>
    ·
    <a href="https://github.com/super95shao/shao-s-Flight-Control-with-cc-vs/issues/new">Request Feature</a>
    ·
    <a href="">中文文档</a>
  </p>
</div>

<!-- ABOUT THE PROJECT -->
## About The Project
<!--
此处缺张飞控的帅照 :)
[![Product Name Screen Shot][product-screenshot]](https://example.com)
下面翻译是百度机翻 + 手改，如有问题请指正 :)
!-->
This flight control's goal is to make it **simulate the operational feel of various types of aircraft** and have basic functions such as **autonomous driving**, **pathfinding**, and **obstacle avoidance**.

This universal flight control is a rewrite of [the previous generation quadcopter propeller flight control](https://github.com/BetaFoprhoton/shao-s-Flight-Control-with-cc-vs/tree/oldVersion).
The principle of the previous generation quadcopter flight control was to use [CC:Tweaked](https://github.com/cc-tweaked/CC-Tweaked) to control the speed controller, modify the lift and reverse torque brought by the physical bearing propeller (flap bearing + flap), and thus achieve closed-loop attitude control.
However, as a result, deployment and parameter tuning are **very complicated**, making it difficult to replicate to other models and **having poor universality**.

So this version of the universal flight controller was born, which uses the **[CC: VS](https://github.com/TechTastic/CC-VS) extension API** as its power source, can be used out of the box, deployed with just one click, and is **very convenient**!
The new version no longer relies on CC: VS, but changes all power to **[Void Power Mod](https://github.com/dfdyz/VoidPowerMod).**


<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [![Lua][Lua]][Lua-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

### Prerequisites
Mods Required:

[VS-2](https://github.com/ValkyrienSkies/Valkyrien-Skies-2),

[Create](https://github.com/Creators-of-Create/Create),
[Create: Tweaked Controllers](https://github.com/getItemFromBlock/Create-Tweaked-Controllers)

[CC:Tweaked](https://github.com/cc-tweaked/CC-Tweaked),
[CC-VS](https://github.com/TechTastic/CC-VS) (Not required for new version),
[Void Power Mod](https://github.com/dfdyz/VoidPowerMod) (required for new version),
[MetaPhysics](https://github.com/KallenPeng/MetaPhysics) (**Follow mode, hms_fly mode, switching player names** and other functions need it)
### Installation
Video Tutorial: [Bilibili](https://www.bilibili.com/video/BV1p1qBY7E2z/)

1. A physical structure **(VS ship)** is required, and there **cannot** be any other controllers on it, such as **[Eureka](https://github.com/ValkyrienSkies/Eureka)'s rudder**.
2. Place an **advanced computer** on the physical structure and place a **controller lectern block** (CTC's controller right click with vanilla lectern) next to it.
3. Place an **engine controller** (the one with an arrow added by **Void Power Mod**) anywhere next to the computer, with the arrow pointing towards the direction of your ship, and place a **holographic display**.
4. Enter this in the **advanced computer**:
   ```bash
   wget https://gitee.com/fashaodesu/shao-s-Flight-Control-with-cc-vs/raw/main/newVersion/startup.lua
   ```
   When you see the message "**Download as startup.lua**", restart the computer, and the flight controller starts running.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage
Under construction :)
<!--
未完待续
_For more examples, please refer to the [Documentation](https://example.com)_
!-->

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap
Under construction :)
<!--
开发路径规划
- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
    - [ ] Nested Feature

See the [open issues](https://github.com/github_username/repo_name/issues) for a full list of proposed features (and known issues).
<!-->
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

<!--
### Top contributors:

<a href="https://github.com/github_username/repo_name/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=github_username/repo_name" alt="contrib.rocks image" />
</a>
!-->



<!-- LICENSE -->
## License

MIT. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
<!--
## Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email@email_client.com

Project Link: [https://github.com/github_username/repo_name](https://github.com/github_username/repo_name)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>
-->

[contributors-shield]: https://img.shields.io/github/contributors/super95shao/shao-s-Flight-Control-with-cc-vs.svg?style=for-the-badge
[contributors-url]: https://github.com/super95shao/shao-s-Flight-Control-with-cc-vs/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/super95shao/shao-s-Flight-Control-with-cc-vs.svg?style=for-the-badge
[forks-url]: https://github.com/super95shao/shao-s-Flight-Control-with-cc-vs/network/members
[stars-shield]: https://img.shields.io/github/stars/super95shao/shao-s-Flight-Control-with-cc-vs.svg?style=for-the-badge
[stars-url]: https://github.com/super95shao/shao-s-Flight-Control-with-cc-vs/stargazers
[issues-shield]: https://img.shields.io/github/issues/super95shao/shao-s-Flight-Control-with-cc-vs.svg?style=for-the-badge
[issues-url]: https://github.com/super95shao/shao-s-Flight-Control-with-cc-vs/issues
[license-shield]: https://img.shields.io/github/license/super95shao/shao-s-Flight-Control-with-cc-vs.svg?style=for-the-badge
[license-url]: https://github.com/super95shao/shao-s-Flight-Control-with-cc-vs/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png

[Lua]: https://img.shields.io/badge/lua-20232A?style=for-the-badge&logo=lua&logoColor=61DAFB
[Lua-url]: https://www.lua.org/
