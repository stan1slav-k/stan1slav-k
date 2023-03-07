<h1 align="center">Hi there, I'm Stanislav</a> 
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
<h3 align="center"> Passionate about Data analytics and Data visualization </h3>

### My skills and tools 🚴🏼

![Python](https://img.shields.io/badge/-Python-DEDBD2?style=for-the-badge&logo=python)
![Jupyter](https://img.shields.io/badge/-Jupyter_Notebook-DEDBD2?style=for-the-badge&logo=Jupyter)
![Clickhouse](https://img.shields.io/badge/-Clickhouse-DEDBD2?style=for-the-badge&logo=Clickhouse)
![SQL](https://img.shields.io/badge/-SQL-DEDBD2?style=for-the-badge)
![TABLEAU](https://img.shields.io/badge/-TABLEAU-DEDBD2?style=for-the-badge&logo=TABLEAU)
![POWER BI](https://img.shields.io/badge/-POWER_BI-DEDBD2?style=for-the-badge&logo=powerbi)
![Airflow](https://img.shields.io/badge/-Airflow-DEDBD2?style=for-the-badge&logo=apacheairflow)
![API](https://img.shields.io/badge/-API-DEDBD2?style=for-the-badge)
![Redash](https://img.shields.io/badge/-Redash-DEDBD2?style=for-the-badge)
![GIT](https://img.shields.io/badge/-GIT-DEDBD2?style=for-the-badge&logo=GIT)
![EXCEL](https://img.shields.io/badge/-EXCEL-DEDBD2?style=for-the-badge&logo=microsoftexcel)

### Contact 🤳🏼

<a href="">[![Telegram](https://img.shields.io/badge/-Telegram-27A7E7?style=for-the-badge&logo=telegram)](https://t.me/stan_kill)</a>

### Projects 👨🏼‍💻

#### 1. Telegram memes channels reposts analysis

<img src="https://github.com/stan1slav-k/stan1slav-k/blob/main/graphs.gif?raw=true" height="400"/></h1>

In this project, I create graph of reposts between memes channel in Telegram. To achieve this goal i made this steps:
- Get access to Telegram via teleton library
- Start from first input channel, I parse messages and get lists of unique reposted channels
- Add new channels in list and continue parsing them (traversing tree in width with setted depth)
- In the end we receive table with channels repost (from - to)
 -With this data I create relation graph with Network module form pyvis library, which use JS under the hood and provide in result interactive graph in HTLM
- Additionally I received list of top reposted channels and most reposting channels

Results: I created repost relation graph. Got acquainted with teleton, pyvis and asyncio libraries. Realized that at some amount of data common graph representation lose sense. And discover some new memes channel.
