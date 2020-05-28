[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->

<br />
<p align="center">
  <a href="https://github.com/DarioCabas/ROS_Webpage">
    <img src="https://lh3.googleusercontent.com/proxy/82M0XSttc2WCNOEhkk9hxXRaWMDVvxPcPr-CarQiwjisQ0CmVNvKhTGhKtCPSzLLyLbmBG8pnm2GB-lVDXqtfN-I8LqpVx93JnFkTCEgCZK5FUyaQe4" alt="Logo" width="80" height="80">
  </a>
</p>

# WEB INTERFACE FOR ROS 

_This is a short description about the content of my proyect. In this project I create an interface using a web page trough  HyperText Markup Language (HTML) and using some basic communication between the page and the robot that I made in RVIZ that is a 3D visualization tool for ROS. The objetive is control a two wheeled robot with the page web interface._

## Table of contents
* [Getting Started](#Getting-Started)
* [Prerequisites](#Prerequisites)
  * [Installing](#Installing)
* [Running the tests](#running-the-tests)
  * [Break down into end to end tests](#break-down-into-end-to-end-tests)
  * [And coding style tests](#and-coding-style-tests)
* [Deployment](#deployment)
* [Built With](#built-With)
* [Contributing](#contributing)
* [Versioning](#versioning)
* [Authors](#authors)
* [License](#license)
* [Contact](#contact)
* [Acknowledgments](#acknowledgments )


## Getting Started🚀


_These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See_ **_Deployment_** _for notes on how to deploy the project ._


## Prerequisites:clipboard:

_You need to install all packages of_ **_ROS Melodic_** _and in the same way you need to use the_ **_Rosbridge server_** _for enabled the communication so you need a mobile robot or in another case visit my another repository to use mine, you can find it in the next link:_


https://github.com/DarioCabas/2wheel_robot


### Installing🔧

#### Clone

- Clone this repo to your local machine using `https://github.com/DarioCabas/ROS_Webpage`

#### Setup

- Create a virtual environment for Python 3:

```

virtualenv venv --python=python3

source venv/bin/activate

```

- Run the webserver for static pages:

```
cd ros_webpage

python -m http.server
```
- Run ROSBridge Websocket Server:

```
roslaunch rosbridge_server rosbridge_websocket.launch
```


## Running the tests ⚙️

Explain how to run the automated tests for this system

### Break down into end to end tests 🔩

Explain what these tests test and why

```
Give an example
```

### And coding style tests ⌨️

Explain what these tests test and why

```
Give an example
```

## Deployment📦

Add additional notes about how to deploy this on a live system

## Built With🛠️

* [ROS Melodic Morenia](http://wiki.ros.org/melodic) - The robot framework used
* [Bootstrap](https://getbootstrap.com/) - Template starter page
* [Vue.js](https://vuejs.org/) - Progressive JavaScript Framework 
* [Gazebo](http://gazebosim.org/tutorials?tut=ros_overview) - Simulator

## Contributing🖇️

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning📌

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors✒️

* **Dario Cabascango** - *Initial work* - [ROS_Webpage](https://github.com/DarioCabas)

## License📄

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**


## Contact:e-mail:

Dario Cabascango  - hz-hertzio@hotmail.com

Project Link: [https://github.com/DarioCabas/ROS_Webpage](https://github.com/DarioCabas/ROS_Webpage)

## Acknowledgments🎁 

Created by [@flynerdpl](https://www.flynerd.pl/) - feel free to contact me!

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/DarioCabas/ROS_Webpage.svg?style=flat-square
[contributors-url]: https://github.com/DarioCabas/ROS_Webpage/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/DarioCabas/ROS_Webpage.svg?style=flat-square
[forks-url]: https://github.com/DarioCabas/ROS_Webpage/network/members
[stars-shield]: https://img.shields.io/github/stars/DarioCabas/ROS_Webpage.svg?style=flat-square
[stars-url]: https://github.com/DarioCabas/ROS_Webpage/stargazers
[issues-shield]: https://img.shields.io/github/issues/DarioCabas/ROS_Webpage.svg?style=flat-square
[issues-url]: https://github.com/DarioCabas/ROS_Webpage/issues
[license-shield]: https://img.shields.io/github/license/DarioCabas/ROS_Webpage.svg?style=flat-square
[license-url]: https://github.com/DarioCabas/ROS_Webpage/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/dario-cabascango-9724431a3
[product-screenshot]: images/screenshot.png
