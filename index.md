---
title: QuYing — Data Science Portfolio
description: Portfolio site of QuYing, a data science student
---

# QuYing

Data Science Student

## About Me

I am a data science student interested in turning raw, messy data into clear and
honest answers. My current focus is on exploratory data analysis and data
visualisation — understanding how to ask a well-defined question, clean and
validate the data behind it, and present findings in a way that a non-technical
reader can immediately follow.

I am building this portfolio to document my projects end to end: the question,
the data, the method, the result, and — just as importantly — the limitations of
each analysis.

## Technical Skills

| Category | Tools |
|---|---|
| Programming | Python |
| Data Analysis | pandas |
| Visualisation | matplotlib |
| Environment | Jupyter Notebook, Git, GitHub |
| Techniques | Data cleaning, exploratory data analysis (EDA), data visualisation |

## Project Showcase

### Netflix Content Analysis

**Research question:** What trends can be observed in the composition, growth,
geographic origin, and audience targeting of Netflix movies and TV shows?

![Netflix Content Added by Year](https://raw.githubusercontent.com/qyyyyy123/data-science-project/main/visualization2.png)

**What the visualisation shows:** The number of titles added to Netflix each year
between 2008 and 2021. Additions were negligible before 2014, accelerated sharply
from 2015, and peaked at roughly 2,000 titles in 2019. The apparent decline in
2020–2021 is not a real drop in production — the dataset's most recent entry is
dated 2021-09-25, so 2021 covers only about nine months.

**Why it matters:** This chart is a good example of why a data scientist must
check the boundaries of a dataset before drawing conclusions. A casual reading of
the downward slope would suggest Netflix was shrinking its catalogue; the actual
explanation is an artefact of when the data was collected.

**Other findings from this project:**
- Movies make up about 70% of the catalogue, far outnumbering TV shows.
- Production is heavily US-centric, with the United States contributing close to
  2,800 titles — nearly three times second-place India.
- The library targets mature audiences: TV-MA and TV-14 dominate, while
  family-friendly ratings such as TV-Y and TV-G are marginal.

**Limitation:** Country counts are taken from the raw `country` field without
splitting co-production entries, so figures reflect "country mentions" rather
than exclusive country of origin.

- **Project repository:** [github.com/qyyyyy123/data-science-project](https://github.com/qyyyyy123/data-science-project)
- **Status:** Completed

## Contact

GitHub: [github.com/qyyyyy123](https://github.com/qyyyyy123)
