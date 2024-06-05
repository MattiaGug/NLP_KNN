# NLP_KNN

<a name="readme-top"></a>

<div align="center">
  
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url1]
[![LinkedIn][linkedin-shield]][linkedin-url2]
  
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
    <a href="https://github.com/MattiaGug/shared-repo"><strong>Explore the docs »</strong></a>
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

## Computation requirements

Examples in [tutorials](tutorials) are runnable on a single CPU typically less than 10 minutes. All examples in the paper are runnable on a single CPU in less than one day. Training KANs for PDE is the most expensive and may take hours to days on a single CPU. We use CPUs to train our models because we carried out parameter sweeps (both for MLPs and KANs) to obtain Pareto Frontiers. There are thousands of small models which is why we use CPUs rather than GPUs. Admittedly, our problem scales are smaller than typical machine learning tasks, but are typical for science-related tasks. In case the scale of your task is large, it is advisable to use GPUs.

## Documentation
The documentation can be found [here](https://kindxiaoming.github.io/pykan/).


## Project Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
    - [ ] Nested Feature

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

Mattia Gugole - [@twitter_handle](https://twitter.com/twitter_handle) - mattia.gugole@icloud.com
<br>
Mattia Roccatello - [@twitter_handle](https://twitter.com/twitter_handle) - tommaso.piraldi@gmail.com
<br>
Devis Marzola - [@twitter_handle](https://twitter.com/twitter_handle) - tommaso.piraldi@gmail.com
<br>
Lisa Milan - [@twitter_handle](https://twitter.com/twitter_handle) - tommaso.piraldi@gmail.com
<br>
Aysenur Oya Ozen - [@twitter_handle](https://twitter.com/twitter_handle) - tommaso.piraldi@gmail.com

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
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url1]: https://linkedin.com/in/mattia-gugole
[linkedin-url2]: https://linkedin.com/in/mattia-gugole
[Python.org]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://www.python.org/
[pykan-shield]: https://img.shields.io/badge/pykan-blue?style=for-the-badge
[pykan-url]: https://github.com/KindXiaoming/pykan
