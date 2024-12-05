# Grateful Dead Lyrics Analysis Project

This project performs a comprehensive analysis of Grateful Dead song lyrics using data collection, natural language processing, and AI-powered insights.

## Project Overview

The project consists of four main steps:
1. API Data Collection
2. Data Cleaning and Preparation
3. Exploratory Data Analysis
4. AI-Powered Insights

### Data Collection
- Uses the Genius API to collect lyrics from 15 Grateful Dead albums
- Stores lyrics in individual JSON files per album
- Albums analyzed include classics like "American Beauty", "Workingman's Dead", and more

### Data Cleaning
- Removes metadata and annotations (e.g., [chorus], [verse])
- Cleans song titles
- Removes duplicates
- Standardizes lyric formatting

### Exploratory Analysis
The analysis includes:
- Word count statistics per song
- Word cloud visualization
- Distribution of song lengths
- Average word count per album
- Generated visualizations:
  - `lyrics_wordcloud.png`
  - `word_count_distribution.png`
  - `words_per_album.png`

### AI Analysis
Uses OpenAI's GPT-3.5-turbo to analyze each song for:
- Literary style comparison (similar authors)
- Poetic metre analysis
- Theme identification
- Tone analysis

## Requirements
- Python 3.x
- Required packages:
  - lyricsgenius
  - pandas
  - json
  - re
  - wordcloud
  - matplotlib
  - seaborn
  - openai

## API Keys Required
- Genius API token
- OpenAI API key

## File Structure
- `*.json` - Individual album lyric files
- `*.png` - Generated visualizations
- Python scripts for analysis

## Usage
1. Set up API keys
2. Run data collection
3. Perform cleaning and analysis
4. Generate visualizations
5. Run AI analysis

## Note
API keys in the code should be kept secure and not shared publicly. Please use your own API keys when running the analysis.

## Visualizations
The project generates several visualizations to help understand the lyrical patterns:
- Word cloud of most common lyrics
- Distribution of song lengths
- Average word count comparison across albums

## AI Insights
The AI analysis provides unique perspectives on:
- Literary influences
- Poetic structure
- Thematic elements
- Emotional tone

For more information or to contribute to this project, please contact the repository owner. 