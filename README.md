# Data Analysis Projects (in progress and completed)
- ## UC Berkeley UE Data Team 
  -   ### **Pulse Survey Data Source & Tableau Dashboard Generation (COMPLETED)**
      - <ins>Tools</ins>: Python, Tableau, scikit-learn library 
      - <ins>Description</ins>: The student pulse survey website is being converted to Tableau dashboards. These dashboards will be filterable. An example of the Tableau dashboard are the UCUES results on the website for the Office of Planning and Analysis.
      - <ins>NOTE</ins>: I worked on this project with my amazing coworkers (Meer Wu, Alex Nguyen, Ashley Alvarez, and Maricruz Montes de Oca-Sanchez). The multiselect_transformers file was initally created by me and edited by my peers. The singleselect_transformers and cleaning_transformers files were initially created by my coworkers and edited by me. They are included so that the data_source_generation file can be easily comprehended. The data source generated from this file is put into a Tableau workbook to create the completed published dashboards on https://ue.berkeley.edu/reports-data/student-surveys/student-pulse-survey!
  -   ### **Data 8 and Data 100 Webscrape (COMPLETED)**
      - <ins>Tools</ins>: Python, BeautifulSoup
      - <ins>Description</ins>: A team of researchers with a National Science Foundation grant have been studying the diversity of data science students at UC Berkeley. As part of this grant, we (UE Data Team) administer surveys to students who are involved in data science. Each term we create a seed file for the survey. One part of the seed file is undergraduate students who are teaching for Data 8 and Data 100. We obtain the names and email addresses of these undergraduates from the Data 8 and Data 100 websites.
  -   ### **Discovery Reading & Composition and Foreign Languages Student Survey Qualitative Analysis (COMPLETED)**
      - <ins>Tools</ins>: Python, nltk, matplotlib, pandas
      - <ins>Description</ins>: We conducted a pre-survey on students’ understanding of and feelings toward research, as well as their relationship to Discovery experiences. This survey was distributed to students enrolled in courses that are part of the Reading and Composition (R&C) and Foreign Languages requirement at UC Berkeley. For a larger report, we will need open-ended responses to be cleaned and processed, and then a subset to be analyzed. The main tasks are as follows:
        - Generate a word cloud (i.e. frequency analysis for most common terms or phrases) in response to the following questions:
           - What comes to mind when you hear the word “research”?
           - What sets of skills, strategies, or values do you think are necessary to succeed in college?
           - What does the phrase “discovery experience” mean to you? 
        - This frequency analysis should be conducted in a batch across all students surveyed, but also in batches that only include responses of students in specific courses. Filter out terms/phrases that only appear once and include the percentages that represent how many times those terms/phrases are said out of the total responses for that batch.
  -   ### **Student Pulse Survey Natural Language Processing (COMPLETED)**
      - <ins>Tools</ins>: Python, NLTK
      - <ins>Description</ins>: Certain questions on the student pulse survey for a past semester asked students about their plans for summer enrollment. This project dissected the reasons behind why student chose NOT to enroll in UC Berkeley classes over the summer using natural language processing techniques like text tokenization, word frequency analysis, and sentiment analysis through testing and training sets. 
  
- ## Personal Projects
  - ### **Spotify Streaming History Analysis (COMPLETED)**
    - <ins>Tools</ins>: Python, BeautifulSoup, selenium, requests, sci-kit learn, matplotlib, seaborn, Spotify API, spotipy
    - <ins>Description</ins>: The primary aim of this project is to conduct a detailed analysis of my Spotify streaming history from the past year.
        - By examining the data, the goal is to identify any patterns or correlations between specific time periods (such as months or days) and the genres, beats per minute (BPM), or other characteristics of the songs I listened to during those periods. The project seeks to uncover whether there is a consistent association between certain periods of time and the musical preferences that align with my personal mood during those periods. For example, it aims to determine if there are specific genres or BPM ranges that tend to be more prevalent during times when I am feeling a particular way, such as energetic, relaxed, or reflective. By delving into this analysis, the project hopes to provide insights into my musical preferences and the emotional states that may have influenced my listening habits throughout the year. This information can contribute to a better understanding of how my mood fluctuates over time and how music plays a role in reflecting and influencing those emotional states.

