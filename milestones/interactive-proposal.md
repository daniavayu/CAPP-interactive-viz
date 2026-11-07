# Daniela Avayu

## Description

Lately, I’ve been really interested in the idea that young people are changing significantly compared with previous generations. I’m particularly interested in exploring the intersection between health and lifestyle trends, such as drug consumption, sleep patterns, physical fitness, and general habits, as well as changes in religion, high cost of life, fertility, and family formation.

I want to explore how significant these trends actually are, how widespread they are across different cultures and countries, and whether they represent broader generational changes or are specific to certain contexts. I’m also interested in conducting some form of cohort analysis, comparing groups of people born in different periods to better understand how behaviors and attitudes have changed over time and what factors might be driving these changes.

Things I have read/listened to:
1. https://open.spotify.com/episode/3911bUMgN0P9W5WEoUAM5v
2. https://www.parents.com/why-teens-are-socializing-less-12024663
3. https://www.cnbc.com/make-it/2024/08/16 why-more-americans-dont-want-kids.html
4. https://steffanpiper.medium.com the-vanishing-teenage-social-life-or-just-a-different-one-9783ce19aede
5. https://www.npr.org/2026/10/24/nx-s1-6012804/birth-rate-population-cdc

## Technical Plan re: Option A/B/C/D

I plan to pursue Option A: Large Interactive and use D3.js, along with HTML, CSS, and JavaScript, to build the visualization and its interactive controls. The centerpiece will show how selected aspects of young adults’ lives in Chile vary by age and survey year. Users will choose an age (18, 20, 25, or 30), a survey year, and an indicator. If the data support it, they will also be able to select a region within Chile. The main chart will update to show the estimated share of people in that group with the selected characteristic and compare it with people of the same age in another survey year. Supporting text and smaller charts will provide context.

I originally imagined comparing profiles of people aged 18, 20, 25, and 30 across different countries, including indicators such as partnership, parenthood, and health habits. I will focus first on Chile and consider adding other countries only if I can find comparable data. This will keep the initial project manageable while leaving room to expand.

## Mockup

I was inspired by [1in8](https://1in8b.life/en/), which lets users explore demographic patterns through an interactive interface. I want to build on that idea by showing how selected aspects of young adults’ lives and habits vary across age groups and time.

I created this mockup with Claude to explore the layout and interactions. Users can select an age, year, and country. The profile panel summarizes a hypothetical person, while the main chart compares indicators such as partnership, parenthood, and health habits with those of people the same age 30 years earlier. Selecting an indicator updates the trend chart. All values in this prototype are placeholders, not real estimates.

The mockup includes several countries to demonstrate the broader concept, but the first version of the project will focus on Chile. If the data allow, I may compare regions within Chile; I would consider adding other countries later if I find comparable data.

![Screenshot of the interactive mockup](../mockup/mockup.jpg)

[Open the interactive HTML mockup](../mockup/mockup.html)

## Data Sources
I plan to begin with Chile. I have worked with data from CASEN and INE before, and I expect these sources to provide relevant measures for my topic. I am still identifying the specific datasets and survey years, and checking which indicators are available consistently over time.

### Data Source 1: CASEN

URL: https://observatorio.ministeriodesarrollosocial.gob.cl/encuesta-casen

Dataset and size: Specific survey years and row and column counts are to be determined after I select the relevant files.

The Encuesta de Caracterización Socioeconómica Nacional (CASEN) is a major household survey in Chile that measures poverty, income distribution, and living conditions. I will check which relevant indicators are available consistently across survey years.

### Data Source 2: INE Vital Statistics

URL: https://www.ine.gob.cl/estadisticas-por-tema/demografia-y-poblacion/estadisticas-vitales

Dataset and size: The specific tables, years, and row and column counts are to be determined.

The Instituto Nacional de Estadísticas (INE) is Chile’s national statistical office. Its Vital Statistics include information on births, deaths, marriages, and civil union agreements, with territorial and sociodemographic details. These data may complement CASEN for indicators related to family formation.

## Questions

1. Does this project seem too ambitious? Should I narrow the scope by limiting the number of variables or countries? Since most of the data I want to use is specific to Chile (with the exception of measures such as fertility and income), would it make sense to begin by comparing regions within Chile and consider cross-country comparisons later? I worry that a Chile-focused analysis may be less insightful if regional differences are relatively small compared with differences between countries or cultures. What do you think?
2. Do you think this is an interesting topic for an interactive visualization?
3. What other visualization approaches might work well for this idea?