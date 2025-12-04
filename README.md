# 3rd Polish AI Olympiad / III Olimpiada Sztucznej Inteligencji
<p align="center">
  <img src="logo_oai.png" alt="LogoIIIOAI" width="30%">
</p>

Welcome to the repository for the tasks of the 3rd Polish AI Olympiad. The Olympiad is aimed at high school and primary school students from all over Poland who are interested in artificial intelligence. The goal is to increase interest in AI and to select the national teams for international competitions.

## General Information
**Homepage:** [Olimpiada Sztucznej Inteligencji](https://www.oai.edu.pl/o-olimpiadzie)

The third edition of the Olympiad will be held in three stages:
- The first stage, online, 01.12.2025 - 25.01.2026.
- The second stage, regional, in Krakow, Poznan, Warsaw, and Wroclaw, 13 - 15.03.2026.
- The third stage, the final, in Poznan, 17 - 19.04.2026.

The regulations are available on our [website](https://www.oai.edu.pl/dokumenty/regulamin).

The official communication channel with participants will be the Discord platform. Access is given to participants after registration.

## Tasks
In the first stage of the Olympiad, participants will face the following challenges:
1.  **Convolutional Filters** - An introduction to one of the most important methods in computer vision.
2.  **Multi-label Classification** - Processing images containing various objects.
3.  **Whisper or Shout** - Audio data classification.
4.  **Semantic Changes** - Analysis of word embeddings for changes in meaning.
5.  **Multispectral Segmentation** - Segmentation of satellite images.

Note: The order of the tasks has been arranged so that their difficulty gradually increases. However, remember that the perception of difficulty is an individual matter. If you encounter difficulties with a specific task, try tackling a task with a higher number—it might turn out to be easier for you.

## Submission Method
Participants will solve the tasks independently and submit them to the Content Committee via the Competition Platform. Access to it is provided to participants after registration. Each task will require the submission of a Jupyter Notebook file with the solution. All submissions will be automatically graded on the Competition Platform.

## Environment
A list of permissible packages can be found in the `environment.yml` file, separately for each task. The solutions were tested using Python 3.11. For working on the tasks, we recommend using the online environment [Google Colab](https://colab.google/) or creating a local environment using [Anaconda](https://docs.anaconda.com/) (instructions for installing an environment from a YML file can be found [here](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file)).

> Note: The same solution run in a local environment or Google Colab may produce different results than on the Competition Platform. The final grade for your task will be calculated on the Competition Platform.

## Evaluation Criteria
Grades for the tasks will be calculated based on the criteria provided in the task descriptions. For each task in the first stage, participants can earn a maximum of 100 points.

## Licenses
The repository uses the following licensed resources:
- The `HistWords` dataset, Apache 2.0 license

```
William L. Hamilton, Jure Leskovec, and Dan Jurafsky. ACL 2016. Diachronic Word Embeddings Reveal Statistical Laws of Semantic Change.
```
- The `Fashion MNIST` dataset, MIT license
- The dataset for the `Convolutional Filters` task was collected from images available on the `https://unsplash.com/` website, under the [Unsplash license](https://unsplash.com/license)
- The `BigEarthNet` dataset used in the `Multispectral Segmentation` task, available under the [CDLA permissive 1.0 license](https://cdla.dev/permissive-1-0/)

## Contact
In case of questions or doubts, please contact us via the Discord platform or by e-mail: [oai@cs.uni.wroc.pl](mailto:oai@cs.uni.wroc.pl), or through direct messages on the Competition Platform (they can be set to be visible only to the Content Committee, i.e., private messages).

We wish you good luck in solving the tasks!
