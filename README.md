
---

### README.md

---

# Netflix Titles Analysis

An in-depth analysis of the titles available on Netflix, exploring the growth, diversity, and distribution of content ratings.

**Full code located in file "3. Netflix EDA.ipynb"**

## Overview

This repository contains a data analysis project focusing on the titles (movies and TV shows) available on Netflix. We aim to understand the platform's growth over time, its global reach, and the diversity of its content.

![Netflix Logo](https://duet-cdn.vox-cdn.com/thumbor/0x0:3151x2048/1200x800/filters:focal(1575x1024:1576x1025):format(webp)/cdn.vox-cdn.com/uploads/chorus_asset/file/15844974/netflixlogo.0.0.1466448626.png)

## Dataset

The dataset includes information on various titles available on Netflix:
- `show_id`: Unique identifier for the show/movie.
- `type`: Movie or TV show.
- `title`: Title of the movie/show.
- `director`: Director of the title.
- `cast`: List of cast members.
- `country`: Country of production.
- `date_added`: Date the title was added to Netflix.
- `release_year`: Release year of the title.
- `rating`: Content rating.
- `duration`: Duration of the movie or number of seasons for TV shows.
- `listed_in`: Genre or category.
- `description`: Brief description.

## Key Insights

- **Growth**: Rapid expansion in the number of titles added over the years, with a noticeable uptick in TV shows in recent years.
- **Global Reach**: The U.S. is the dominant producer of content, but countries like India, the UK, and Canada also have a significant presence.
- **Diverse Audience**: Netflix provides content for all age groups, from kids to adults.

## Tools Used

- Python
- Pandas: For data manipulation and analysis.
- Matplotlib: For data visualization.

## Setup

1. Clone this repository:
```
git clone https://github.com/your_username/netflix-titles-analysis.git
```

2. Navigate to the project directory:
```
cd netflix-titles-analysis
```

3. Install the required packages:
```
pip install -r requirements.txt
```

4. Run the analysis script:
```
python netflix_analysis.py
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

