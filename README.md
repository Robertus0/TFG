<a name="readme-top"></a>


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
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

The objective of this work is to use Deep Learning techniques to detect illegal swimming pools in aerial images, improving efficiency and reducing the costs associated with their identification. To achieve this, fine-tuning of the Transformer DETR model has been carried out using a dataset of aerial images from Catalonia. The results demonstrate the effectiveness of the system in accurately detecting swimming pools, although it faces challenges in detecting partially visible pools as well as smaller pools. This work contributes to the advancement of illegal swimming pool detection by offering a promising alternative to optimize the processes of identification and control of these infrastructures.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![Python][Python.js]][Python-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

### Installation

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
  ```
  git clone https://github.com/Robertus0/TFG.git
  ```
3. Create a virtual environment "env"
  ```
  py -m venv env
  ```
4. Activate the virtual environment
  ```
  .\env\Scripts\activate
  ```
5. Install requirements
  ```
  pip install -r requirements.txt
  ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

The usage of this proyect is to identify pools in aerial images, you can pass an image and it will return the location of each and every pool in the image.

<p align="center">
  <img src="https://github.com/Robertus0/TFG/assets/80832973/6583606d-8241-41d8-b07c-1d02b744bb6a"/>
  <img src="https://github.com/Robertus0/TFG/assets/80832973/b78b4a7c-7c10-4842-a51c-e7bfbb006e40"/>
</p>

For that objective, I used a database extracted from [ICGC](https://www.icgc.cat/) that I prepared and uploaded to [roboflow](https://universe.roboflow.com/student-of-the-universitat-autonoma-de-barcelona/pools-detector/browse) to train, validation and test.

To train a model refer to the Train notebook. For inference to the Evaluation notebook.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- LICENSE -->
## License

Distributed under the Creative Commons License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[license-shield]: https://img.shields.io/github/license/Robertus0/TFG.svg?style=for-the-badge
[license-url]: https://github.com/Robertus0/TFG/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/roberto-manresa
[product-screenshot]: images/screenshot.png
[Python.js]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://www.python.org/
