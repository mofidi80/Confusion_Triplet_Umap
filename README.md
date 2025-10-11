<a id="readme-top"></a>


[![LinkedIn][linkedin-shield]][linkedin-url]

<h3 align="center">Classification with Confusion Analysis using UMAP</h3>

  <p align="center">
    A  deep learning project that implements a CNN model for MNIST digit classification, analyzes confusion patterns between classes, and visualizes embeddings using UMAP dimensionality reduction.
    <br />
    <br />
    <br />
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
        <li><a href="#skills-required">Skills Required</a><li>
      </ul>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#possible-usage">Possible Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## About The Project
In this project we make a CNN model for classification on MNIST dataset, and for this we use both cross entropy loss, and triplet loss and analyze the effect of triplet loss. We also use confusion matrix to analyze the accuracy of the model on each class. Afterwards we use UMAP to vizualize the embeddings of each class.

## Project Overview

This project demonstrates a complete pipeline for:
- Training a Convolutional Neural Network (CNN) on the MNIST dataset
- Generating and analyzing confusion matrices to identify frequently confused digit pairs
- Extracting feature embeddings and visualizing them using UMAP
- Focusing specifically on the most confused digit classes for detailed analysis

## Outcome
- Accuracy: 84% on test subset
- Most Confused: Classes 2 & 5
- Visualization: UMAP shows overlapping embeddings for confused digits

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Built With
* Python
   + Numpy
   + Pandas
   + Scikit-Learn
   + Matplotlib
   + Seaborn
   + Pytorch

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Skills Required
* Exploratory Data Analysis
* Classification ML Models
* Data Visualization

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Installation
1. First intall jupyter notebook from the link below if you haven't already.
   + https://jupyter.org/install
2. Make sure you have all the libraries mentioned in Built With section installed; If not first run your environment then use the following commands:
+ 
  ```bash
pip install torch torchvision pytorch-metric-learning umap-learn numpy matplotlib seaborn scikit-learn
  ```

3. Run noteboook.
<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Possible usage
This project demonstrates techniques useful for:
- Understanding model limitations and failure modes
- Feature space analysis and interpretability
- Educational purposes in deep learning courses
- Baseline for more complex image classification tasks

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

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact
Mohammad Mofidi
* Email: mohammad.mofidi.k@gmail.com
* Linkedin: https://www.linkedin.com/in/mohammad-mofidi-khajeh-2715832b8/
* Instagram: https://www.instagram.com/_mohammadmofidi/


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/mohammad-mofidi-khajeh-2715832b8/












  
