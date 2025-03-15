# cda2_4Da FHNW Challenge

## Policy Advices zur Energieerzeugung ohne Treibhausgasausstoss

Devs: Marius Läubli / Weiping Zhang

## Repository Structure


- Arbeitsprotokoll
    - Containing the Arbeitsprotokoll where our process is documented so the thought process and decisions are traceable later on.
- Challenge development
    - Containing Files that were used during the process of the challenge but were then abandoned or redundant.
- Data
    - Containing Datafiles either directly from a source or downloaded/manipulated via python and used for visualisation in Tableau
- Notebooks
    - Containing the Main notebook needed to extract current data from different sources, transforming it for later use and loading in in to data files in ../Data
    - Also there are log files aswell as the requiremet file and the credential file (which would not be uploaded in a public repository but is used here to reconstruate)
- Tableau
    - Containing the local dashboard and story files  

## How to use the Files
If the Credentials are correct and there is an actice internet connection the notebook can be executed and currend data is loaded in to Data Files.
Those Data files are used by the Tableau files. If the Tableau File is in an twbx Format, make sure to refresh or relink the needed File manually. If it is a twb file it should do so automatically unless the path cannot be found. Using the files on different Computers might result in the change of referencepaths used in the Tableau files.
Tableau would prompt the user to reconnect if this scenario occurs.

## Goal of the Challenge

This Repository is created to tackle the Challenge "Policy Advices zur Energieerzeugung ohne Treibhausgasausstoss".
We focus on the energy improt of Switzerland and analysed related data to present a policy advice for the reduction of non-renewable energy sources in europe.

The published stroy of the Challenge can be viewed here:[Link to story](https://public.tableau.com/app/profile/weiping.zhang/viz/story_16868385567880/Story1?publish=yes)


If the context is clear, this published Dashboard gives a good overview: [Link to dashboard](https://public.tableau.com/app/profile/weiping.zhang/viz/dashboard_16868207595000/Dashboard2)