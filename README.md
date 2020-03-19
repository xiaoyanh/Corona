# Corona Visualizations
Tableau Analysis of JHU and Italian PCM data

Data is downloaded from [JHU CSSE!](https://github.com/CSSEGISandData/COVID-19) and the [Italian PCM!](https://github.com/pcm-dpc/COVID-19?fbclid=IwAR3ZdlaE7ro2Jj712CpHeEdyYyQutUtAtzPNWH2PnALM-q0LDLtpLYzJcQk).

You can update the data using the included bash script i.e. running `bash update_data.sh`. The first time doing this, you also need to give permission to run the script by running the following first `chmod +x update_data.sh`.

The data is cleaned using Tableau Prep and visualized using Tableau Desktop. The files are included with `clean_corona.tfl` and `corona_analysis.twb`, respectively. When you open the Tableau Prep flow and the Tableau Desktop notebook for the first time, it will say they can not find the relevant datafiles: you need to reset the location of the `corona_all.csv` file on *your* computer in `corona_analysis.twb`. You need to do the analogous thing for the four raw datafiles in `clean_corona.tfl`. 

You *do not* need to run the Tableau Prep flow to in order to visualize the data: To visualize the data you *only need* `corona_all.csv` and `corona_analysis.twb`.

Both Tableau Prep and Tableau Desktop are free for academics with an .edu email [here!](https://www.tableau.com/academic/students).

Maintainer:
X.Y. Han
Cornell University, ORIE
