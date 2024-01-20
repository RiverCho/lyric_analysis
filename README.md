
# Comparative Lyric Analysis: Folk vs. Country Music

## Introduction
This repository focuses on a comparative analysis of lyrics from folk and country music genres. The research aims to explore linguistic differences, cultural nuances, and thematic variations present in the lyrical content.

### Dataset
The dataset comprises lyrics from contemporary folk musicians (Woody Guthrie, Phil Ochs, Joan Baez, Bob Dylan, Neil Young, and Dawes) sourced from Genius. Additionally, it includes top-ranking Billboard Music Award-winning country albums between 2006 and 2023.

### Research Questions
The study aims to address the following research questions:
1. **Lexical and Linguistic Variations:** Compare vocabulary usage, syntactic structures, and linguistic expression styles between folk and country music lyrics.
2. **Cultural and Regional Features:** Explore the presence of region-specific vocabulary, themes, and historical/cultural references within the lyrics.
3. **Emotional and Thematic Differences:** Analyze emotions, themes, and cultural connotations conveyed in the lyrics to understand how these aspects differ between the two music genres.

## Repository Contents
The repository contains:
- Corpus with separate folders for each album containing lyrics in txt files. Albums are organized by artist and album name.
- CSV file (`lyric_analysis.csv`) contains processed data derived from the analysis of folk and country music lyrics. 

#### Variables

## Variables

| Variable         | Description                                                        | Data Type |
|------------------|--------------------------------------------------------------------|-----------|
| Genre            | The music genre (folk or country).                                  | String    |
| Artist           | The musician or band name.                                          | String    |
| Album            | The name of the album.                                              | String    |
| Title            | The title of the song.                                              | String    |
| Filename         | The filename of the song's lyrics.                                  | String    |
| Pageviews        | The number of pageviews or popularity on Genius.                    | Integer   |
| Lyrics           | The lyrics of the song.                                             | String    |
| Tokens           | Tokens extracted from the lyrics.                                   | List      |
| Lemmas           | Lemmatized tokens.                                                 | List      |
| POS              | Parts of speech tags for each token.                                | List      |
| Proper_Nouns     | Count of proper nouns in the lyrics.                                | Integer   |
| Named_Entities   | Count of named entities recognized in the lyrics.                   | Integer   |
| NE_Words         | Words identified as named entities in the lyrics.                    | List      |


### Important Note

**Note 1:**

- The `api_key.py` file containing the Genius API token is not included in this repository.
- To utilize the scraping code or access lyrics from Genius, please generate your own API token from the [Genius Developer site](https://genius.com/developers).
- Once obtained, create a `api_key.py` file in the root directory and assign your API token to a variable named `GENIUS_API_TOKEN`.

##### Example of `api_key.py`:

```python
# api_key.py
GENIUS_API_TOKEN = "YOUR_GENIUS_API_TOKEN_HERE"
```

**Note 2:**

Considering the copyright issues related to song lyrics, this project cannot include the retrieved lyric texts.   Researchers are encouraged to refer to the Jupyter Notebook files for the scraping code and obtain the lyrics or other texts of interest for similar research.
Please use scraping techniques responsibly, ensuring that your actions comply with legal regulations and respect relevant copyrights and usage agreements. 