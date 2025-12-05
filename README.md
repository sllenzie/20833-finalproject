# Race-Based Movie Reviews: When Did the Culture Shift?

## Project Overview

This project examines how film reviews of race-centered movies have evolved over time in response to major cultural moments of racial tension and protest in the United States. By analyzing reviews from six films released between 1989 and 2018, we investigate whether critical discourse shifted in tone and focus following key incidents in 1992 (Rodney King riots), 2014 (Ferguson unrest), and 2020 (George Floyd protests).

**Research Team:** Stella Lenzie, Charlotte Stephenow, Samantha Steensland  
**Course:** WRIT 20833  
**Term:** Fall 2025

## Films Analyzed

- **Do The Right Thing** (1989)
- **The Help** (2011)
- **Selma** (2014)
- **Hidden Figures** (2016)
- **The Blind Side** (2009)
- **The Hate U Give** (2018)

## Methodology

Our analysis uses computational text analysis methods to examine film reviews scraped from Rotten Tomatoes:

1. **VADER Sentiment Analysis** - Measures the emotional tone of reviews over time
2. **Term Frequency Analysis** - Identifies what topics and themes reviewers focused on

All analysis code and datasets are available in our [Google Drive folder](https://drive.google.com/drive/folders/1wwMq2huxN_oi2FskChBgsIB31mNGqzLL?usp=sharing).

## How to Access

### View the Website

1. Clone this repository:
   ```bash
   git clone https://github.com/sllenzie/20833-finalproject.git
   ```

2. Open `index.html` in your web browser by either:
   - Double-clicking the file in your file explorer
   - Right-clicking and selecting "Open with" → your preferred browser
   - Using a local development server (see below)

### Using a Local Server (Recommended)

For the best viewing experience, use a local development server:

**With Python:**
```bash
cd 20833-finalproject
python3 -m http.server 8000
```
Then visit `http://localhost:8000` in your browser.

**With VS Code:**
- Install the "Live Server" extension
- Right-click `index.html` and select "Open with Live Server"

## Project Structure

```
20833-finalproject/
├── index.html          # Main project webpage
├── css/
│   └── styles.css      # Styling
├── js/
│   └── script.js       # Interactive features
├── images/             # Visualizations and historical images
│   ├── background/
│   ├── do-the-right-thing/
│   ├── hidden-figures/
│   ├── selma/
│   ├── the-blind-side/
│   ├── the-hate-u-give/
│   ├── the-help/
│   └── timeline/
└── README.md           # This file
```

## Key Features

- **Interactive Timeline** - Explores historical context from 1820 to 2020
- **Sentiment Analysis Visualizations** - Pie charts showing emotional tone distribution
- **Term Frequency Analysis** - Bar charts revealing thematic focus areas
- **Historical Background** - Contextualizes the Rodney King riots, Ferguson unrest, and George Floyd protests
- **Global Perspective** - Examines how the 2020 protests resonated internationally

## Contact

For questions or feedback, contact: [stella.lenzie@gmail.com](mailto:stella.lenzie@gmail.com)

## License

© 2025 Research Project. All rights reserved.

