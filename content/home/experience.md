---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: 'Data Scientist Intern'
    company: 'Xiaomi Technology'
    company_url: 'https://www.mi.com/about'
    company_logo: Xiaomi_logo
    location: 'Wuhan, China'
    date_start: '2019-10-01'
    date_end: '2020-01-23'
    description: |2-
        Responsibilities include:
        
        * Built a word2vec word vector NLP model to calculate the similarity between finance words. Expanded 5,000 words, and enhanced the recall of the tagging process by 3%. 
        * Deployed a Web Crawler to collect music entities, added more than 10,000 entities, and 87% of them were utilized for tagging users to make advertising more precise. 
        * Operated hive SQL to query music data, analyzed the popularity of them with Pandas, and helped increased DAU by 5000.
        * Coded in Scala, helped improve the data mining logic, and improved the accuracy of tagging process to 90%.

  - title: 'Analyst Intern'
    company: 'Wuhan Bureau Of Statistics'
    company_url: 'http://tjj.wuhan.gov.cn/'
    company_logo: org-x
    location: 'Wuhan, China'
    date_start: '2019-08-01'
    date_end: '2019-09-15'
    description: |2-
      Responsibilities include:
      
        * Estimated the total factor productivity (TFP) leveraging Cobb–Douglas production function. Helped researchers understand the impact of technological innovation on Wuhan’s economy from a quantitative perspective.
        * Applied the Time Series Regression to predict the potential economic growth of Wuhan, and contributed to a theoretical paper about the influence of technology development on the economy.

design:
  columns: '2'
---
