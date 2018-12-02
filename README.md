# dolphins (pre-alpha)
WORK IN PROGRESS - THIS CODE IS EXPERIMENTAL AND NOT READY TO USE YET
DataFrames for easy, performant data analysis (like pandas and R)

# Why dolphins?
In 2018, Python, R and Java had come to dominate the world of data analysis, science, data engineering, machine learning and AI.  This is due largely to excellent tooling and mature libraries which data scientists and researchers know and have invested heavily into.  dolphins was created by a team of data scientists, AI experts and software engineers who love Javascript and wanted the language to have tools and data analysis infrastructure to match or succeed what is available in other languages.  dolphins represents an attempt to bring the best parts of pandas and R to JavaScript.

Dolphins is designed to be perfomant on both servers and browsers and is extendable so that it can easily integrate with other popular tools like d3, React, Angular, TypeScript or Rx.

# Installation
```
npm i dolphins
# or
yarn add dolphins
```

# Getting started
dolphins can create a DataFrame from a many different sources of data:
```
# create a daraframe from a csv file:
const csvDf = dolphins.readFile();
# create a dataframe from a json file:
const jsonDf = dolphis.readFile();
# create a dataframe from an xls or xlsx file:
const excelDf = dolphins.df('');
# create a dataframe from an array:
const df2 = dolphins.df();
# create a dataframe from an indexed Javascript object:
const df = dolphins.df();
# TODO - implement numpy arrays
```

dolphins can perform common data analysis tasks with simplicty and efficiency:
```


```

# Contributing
One reason why pandas and R have been so successful is because hundreds of data analysts and engineers have contributed to those projects and continue to do so.  These libraries didn't write themselves and there is a lot of work to be done!  Please see the Contribution guide if you you have some time to contribute and share our visiion of bringing top-notch data analysis tools to the JavaScript community!  We are well organized and have a Trello board and a Slack team!
