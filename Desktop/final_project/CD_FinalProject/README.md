# Review Evolution:A Comparative  Analysis of 'The Dark Knight' and 'Infernal Affairs' Reviews

This is the repository for the group project of Group E of the "Collect Data" course. This study primarily focuses on investigating the changing trends in film reviews over time. The data utilized include Douban and IMDb reviews for two movies, "Infernal Affairs" and "The Dark Knight." The repository files encompass the project's Data Management Plan (DMP) document, a Jupyter notebook tutorial detailing the data collection and processing procedures, CSV files containing information on award-winning films collected during the project, the research report for the project, and a subset of the reviews corpus (shuffled text samples).

## 1.Introduction and Background

The project is about the comparative analysis of two films’ reviews over time.
Based on two criteria—recognition in the industry and audience ratings—two movies were selected: Batman: The Dark Knight and Infernal Affairs
Go further，during 2001-2010，Batman: The Dark Knight is An Oscars-winning work with the highest IMDB rating.Infernal Affairs is a Hong Kong Film Awards-winning-work with the highest Douban rating.

## 2.Research Question

Explore the evolving focus of film reviews over time.

### Source:

In terms of the sources, the review data of "Batman:The Dark Knight" reviews comes from IMDb, an online database of information related to films, television series, podcasts, home videos, video games, and streaming content online. The review data of "Infernal" comes from Douban, the most popular source of movie, TV, and celebrity information platform in China.

### Preprocess and Clean:

Prior to analysis, the data underwent rigorous cleaning and normalization processes to ensure accuracy and reliability. The whole process is presented in the Jupyter Notebook file. 

### Dataset Description:

The corpus includes data scraped using Python, covering: 

Batman: The Dark Knight: IMDb reviews (all 8,000+ reviews from 2008 to present) and Douban comments (60,000+, randomly selected by Douban, since 2008).
Infernal Affairs: IMDb reviews (all 244 from 2008 to present)and Douban comments (60,000+, randomly selected by Douban, since the creation of Douban in 2005 ).

## 3.Document description

### The repository contains:
* The DMP of the project

* Research report

* A Jupyter notebook tutorial documenting the process of collecting and processing data

* A corpus folder which contains sample of the reviews corpus (In consideration of copyright, only part of shuffled text samples are provided.)

* A dataset folder which contains CSV files containing information on award-winning films

## Dataset Variables of CSV file containing information on Hong Kong Film Award-winning movies.

| Variable                  | Description                                           | Data Type   |
|---------------------------|-------------------------------------------------------|-------------|
| **Movie**                 | The title of the movie.                               | Text        |
| **URL**                   | The web address or link associated with the movie.    | URL         |
| **Director**              | The director of the movie.                             | Text        |
| **Writer**                | The writer or writers who contributed to the script.  | Text        |
| **Rating**                | The rating assigned to the movie.                     | Numeric     |
| **Genre**                 | The category or genre of the movie.                   | Text        |
| **Production Country/Region** | The country or region where the movie was produced. | Text        |
| **Release Year**          | The year when the movie was released.                 | Numeric     |
| **Cast**                  | The main actors or performers in the movie.          | Text        |
| **Release Date**          | The date when the movie was officially released.      | Date        |
| **Duration**              | The length of the movie in terms of running time.     | Numeric     |
| **Language**              | The language(s) in which the movie is presented.     | Text        |
| **Ratings**               | Additional ratings or reviews associated with the movie. | Text    |
| **Plot Summary**          | A brief overview or summary of the movie's plot.      | Text        |
| **Awards**                | Any awards or recognitions received by the movie.     | Text        |
| **Cast and Crew**         | Information about the individuals involved in the production of the movie. | Text |

* For information about Oscar-winning films and the data collection process, please refer to another group [project repository](https://toolsandmethods.my.canva.site/) of our team.

## 4.References

Sunteng. (August 2023). Building a Web App to Predict the Oscar Winners.
Retrieved from https://ithelp.ithome.com.tw/m/articles/10334954

RAPHAEL FONTES. (March 2023). Kaggle Dataset: The Oscar Award.
Retrieved from https://www.kaggle.com/datasets/unanimad/the-oscar-award

YUEMING. (2018). Kaggle Dataset: IMDb 5000 Movie Dataset.
Retrieved from https://www.kaggle.com/datasets/carolzhangdc/imdb-5000-movie-dataset

Voyant Tools. (2023). Voyant Tools Documentation.
Retrieved from https://voyant-tools.org/docs/#!/guide/tools

## 5.Project Website

For findings of the project, please visit our project [website] (https://filmproject.my.canva.site/cd).**