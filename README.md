# KAN network for NLP tasks

<a name="readme-top"></a>

<div align="center">
  
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

  
</div>

<br />
<div align="center">
  <a href="https://github.com/Mattgugo/shared-repo">
    <img src="https://github.com/MattiaGug/NLP_KNN/blob/c3f6dbd2e80267db2366506483b8ea57284b9c9d/Logo_Universita%CC%80_Padova.png" width="300" height="300">
  </a>

<h3 align="center">Kolmogorov-Arnold Networks application to NLP</h3>

  <p align="center">
    Course: Natural Processing Language
    <br />
    <a href="https://arxiv.org/abs/2404.19756"><strong>Explore the KAN paper »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Mattgugo/shared-repo">View Demo</a>
    ·
    <a href="https://github.com/MattiaGug/shared-repo/issues">Report Bug</a>
    ·
    <a href="https://github.com/MattiaGug/shared-repo/issues">Request Feature</a>
  </p>
</div>

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
  </ol>
</details>

### In this Repo the projects and documentation will concern: 

* [![Python][Python.org]][Python-url]
* [![PyKAN][pykan-shield]][pykan-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Important Notice

AGGIUNGi


## Installation
Pykan can be installed via PyPI or directly from GitHub. 

**Pre-requisites:**

```
Python 3.9.7 or higher
pip
```

**Installation via github**

```
python -m venv pykan-env
source pykan-env/bin/activate  # On Windows use `pykan-env\Scripts\activate`
pip install git+https://github.com/KindXiaoming/pykan.git
```

**Installation via PyPI:**
```
python -m venv pykan-env
source pykan-env/bin/activate  # On Windows use `pykan-env\Scripts\activate`
pip install pykan
```
Requirements

```python
# python==3.9.7
matplotlib==3.6.2
numpy==1.24.4
scikit_learn==1.1.3
setuptools==65.5.0
sympy==1.11.1
torch==2.2.2
tqdm==4.66.2
```

After activating the virtual environment, you can install specific package requirements as follows:
```python
pip install -r requirements.txt
```

**Optional: Conda Environment Setup**
For those who prefer using Conda:
```
conda create --name pykan-env python=3.9.7
conda activate pykan-env
pip install git+https://github.com/KindXiaoming/pykan.git  # For GitHub installation
# or
pip install pykan  # For PyPI installation
```

## Documentation
The documentation can be found [here](https://kindxiaoming.github.io/pykan/).


## Project Roadmap

- [x] Math background summarization
- [x] NLP dataset research
- [x] KAN implementation for NLP tasks
    - [x] IMNDB Dataset
    - [x] Clinical Reviews Dataset

<p align="right">(<a href="#readme-top">back to top</a>)</p>

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

## Contact

Mattia Gugole - mattia.gugole@studenti.unipd.com
<br>
Mattia Roccatello - mattia.roccatello@studenti.unipd.com
<br>
Devis Marzola - devis.marzola@gmail.com
<br>
Lisa Milan - - lisa.milan1@studenti.unipd.com
<br>
Aysenur Oya Ozen  - tommaso.piraldi@gmail.com

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/MattiaGug/shared-repo.svg?style=for-the-badge
[contributors-url]: https://github.com/MattiaGug/shared-repo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/MattiaGug/shared-repo.svg?style=for-the-badge
[forks-url]: https://github.com/MattiaGug/shared-repo/network/members
[stars-shield]: https://img.shields.io/github/stars/MattiaGug/shared-repo.svg?style=for-the-badge
[stars-url]: https://github.com/MattiaGug/shared-repo/stargazers
[issues-shield]: https://img.shields.io/github/issues/MattiaGug/shared-repo.svg?style=for-the-badge
[issues-url]: https://github.com/MattiaGug/shared-repo/issues
[license-shield]: https://img.shields.io/github/license/MattiaGug/shared-repo.svg?style=for-the-badge
[license-url]: https://github.com/MattiaGug/shared-repo/blob/master/LICENSE.txt
[Python.org]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://www.python.org/
[pykan-shield]: https://img.shields.io/badge/pykan-blue?style=for-the-badge
[pykan-url]: https://github.com/KindXiaoming/pykan
