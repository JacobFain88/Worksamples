# Worksamples

This repository contains some relevant work samples from the last year competing in sports analytics case competitions and in my regressions and machine learning classes.

## SABR Diamond Dollars Case

The objective of the case competition was to devise an updated version of Bill James gamescore. My team from the University of Chicago Booth School of Business used statcast data scraped from `baseballsavant` using the package `baseballr` developed by Bill Petti.

Our goal was to create a metric that would quantify starting pitching performance independent of factors outside of the pitchers controls (such as park factors, umpires, and team defensive performance). In the end we developed the 4 tools pitching metric that scored pitchers on their ability to avoid hard contact, their command, their "stuff", and their ability to control the game. The RMD file titled `ModelingCode` contains the code that was used to scape, clean, and preprocess the data as well as the code for applying the various machine learning models used to devise the metric and the code to create the graphics used in the presentation.