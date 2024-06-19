# UEFA Euro Championship - Data Analysis Repository

### Introduction

Welcome to the **UEFA Euro Championship Data Analysis Repository**!

This project aims to provide comprehensive insights into various aspects of the UEFA Euro Championship using interactive visualizations.
[Check out the webapp!](https://uefa-euro-data-analysis.streamlit.app)

I have gathered all the data from past tournaments to build an interactive way to explore:

- Match performances,
- Tournament statistics, and
- Penalty card data

All data is presented through an intuitive web interface.

### Motivation

The primary objective of this project is to demonstrate my ability to use Python, Streamlit, and advanced graphing libraries (Plotly) to build interactive visualizations.

I am rooting for Germany to win the championship in 2024, and this is my way of cheering for them!

**See my [blog post](https://www.kunal-pathak.com/blog/UEFA-Euro-Data-Analysis) for more details!**

### Tools and Technologies Used

- **Pandas**
  - Of course, [Pandas](https://pandas.pydata.org).
  - It is THE data manipulation and analysis library for Python.
  - It provides data structures and functions needed to clean, analyze, and visualize the data efficiently.
- **Plotly**
  - [Plotly](https://github.com/plotly) is an awesome graphing library to plot publication-quality graphs online.
  - These graphs are dynamic and interactive.
  - It's quite versatile, and I use it for several use cases.
- **Streamlit**
  - I used [Streamlit](https://docs.streamlit.io/develop/concepts) to create the front-end to showcase my Plotly graphs.
  - Streamlit is originally a tool to build web applications with Python.

### Overview of Each File

- In this section, I am briefly covering what each file does and how the plots are built.
- I have tried to keep all code sections as stand-alone and non-modular as possible. This allows me or anyone else to adapt them quickly for building other graphs and not spend time going through code clutter. You can just pick up a code block and modify it independently without impacting others.

#### 100-Match_Performance.py

- This script visualizes match performance data, including total points, goals scored, and goals conceded by teams in the UEFA Euro Championship.
- Users can filter data to view the top teams and explore interactive bar charts that display the performance metrics.

#### 200-Tournaments_Statistics.py

- This script focuses on tournament statistics, including the medals tally and host nations.
- Users can explore which teams have won the most medals and which nations have hosted the championship most frequently.
- I have used both bar charts and pie charts.

#### 300-Penalty_Cards.py

- This script provides an analysis of penalty cards issued during the championship.
- It visualizes data on red cards and two-yellow cards across different rounds of the tournament.
- Users can explore which teams received the most penalty cards and in which stages they were most prevalent.

### Acknowledgements

All code in this repository is made possible by the contributions of these open-source initiatives. I fully acknowledge their efforts and attribute the usage of their components to them:

- **[Pandas](https://github.com/pandas-dev/pandas)** - Licensed under the BSD-3-Clause License
- **[Plotly](https://github.com/plotly/plotly.py)** - Licensed under the MIT License
- **[Wikipedia](https://en.wikipedia.org/wiki/UEFA_European_Championship)** - Data licensed under the Creative Commons Attribution-ShareAlike 3.0 Unported License (CC BY-SA 3.0)
- **[Streamlit](https://github.com/streamlit/streamlit)** - Licensed under the Apache-2.0 License

### Installation and Usage

To run this project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/kanad13/UEFA-Euro-Data-Analysis.git
```

2. Navigate to the project directory:

```bash
cd UEFA-Euro-Data-Analysis
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

4. Run the Streamlit application:

```bash
streamlit run Welcome.py
```

### Contributing

- No code is perfect.
- I am sure there will be bugs in my code or issues with the underlying data I have used.
- So please raise an issue or pull request to highlight it to me. I would really appreciate it!

### License

This project is licensed under the MIT License. See the LICENSE file for more details.
