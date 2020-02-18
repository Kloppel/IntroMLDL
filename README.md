# IntroMLDL
Intro to Machine and Deep Learning Course Repository for Winter Semester 1920 MSc Physics

This Repository is of the data used, code and presentation of the group of the contributors of this repository for the introduction to machine and deep learning in physics and beyond from Goethe University Frankfurt physics department with Dr. Jan Steinheimer-Froschauer and Dr. Kai Zhou.

All .csv files are the data used, but not limited to that. Data was downloaded from yahoo finance, and only Adjusted Close prices of selected S&P500 stocks were used. We tried to use only stocks which were available over all of the time period (2007-2017).

Selected Neural Network Architectures were applied to the data subsets to try and obtain information and maybe find a process which can help build a portfolio for investing. To quantify this, several ways to quantify data were devised, based upon known information of stock markets, of which the S&P500 Index is a typical representative. 

The iPython notebooks should be executable cell by cell, and do require Python 3.6.4 (at least, i think) and all packages installed. To obtain this, we recommend using a virtual environment, which you can create using the venv Python package. All packages used are free. Tests were conducted of running this notebook on virtual environments on most of the major operating system distributions (Windows 10, iOS, Ubuntu 18.04) and were running without problems. 

The Slides.slides.html file is the presentation given at the end of the course. It can be created using the settings for slides in the ipynb file and running the command 
jupyter nbconvert Slides.ipynb --to slides --post serve --SlidesExporter.reveal_scroll=True
fro the command line inside the virtual environment and the location in which the iPython notebook is located. 


We know that not all of the networks work as intended (see some learning curves showing weird behaviour, or predictions only happening in certain ranges), so we intend this to be a learning experience when you retrace our work. 

