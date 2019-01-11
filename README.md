# final-assignment
In this final assignment i have tried to solve the AcceccViz exercise. I did not manange all parts of it. For each part of the code I have written markdown cells with explanations of what the code is supposed to do, and what did not not work to well. At some parts I also have some code in the markdown cells, which did not work in the code script. This is to show what I have been thinking.

The code, notebooks and documentatation is created in a private repository. I got tipsed that the easiest way to solve this is to post the link to the repsoitory is here. The link to the repsoitory is: https://github.com/sagmoen/final-assignment-sagmoen.

How to use the code:
1. git clone https://github.com/sagmoen/final-assignment-sagmoen.git

2. download the data from Helsinki Region Travel Time Matrix into the folder 'data/TravelTimes': (link: http://www.helsinki.fi/science/accessibility/data/helsinki-region-travel-time-matrix/2018/HelsinkiRegion_TravelTimeMatrix2018.zip

  >$ wget http://www.helsinki.fi/science/accessibility/data/helsinki-region-travel-time-matrix/2018/HelsinkiRegion_TravelTimeMatrix2018.zip<br /> 
  >$ unzip HelsinkiRegion_TravelTimeMatrix.zip

3. Download the MetropAccess_YKR_grid into the folder 'data/MetropAccess_YKR_grid' folder: (link: http://www.helsinki.fi/science/accessibility/data/MetropAccess-matka-aikamatriisi/MetropAccess_YKR_grid.zip)

  >$ wget http://www.helsinki.fi/science/accessibility/data/MetropAccess-matka-aikamatriisi/MetropAccess_YKR_grid.zip)<br />
  >$ unzip MetropAccess_YKR_grid.zip

4. Open the Final-assignment.ipynb-file

5. Specify which YKR_ID you would like to use the AcceccViz tool on, ib the cell that says "specify YKR_ID here!"

6. Specify which travel mode you would like to visualise and whether you would like to create a static or interactive map in the cell that says "Specify travel mode and type of map here!"

7. Run the code script

You can use the part 5 of the code to get a (very!!) small clue on which YKR_ID you need if you are searching for a specific place in Helsinki. This code works independendent of the other part of the script, but you have to download the MetropAccess_YKR_grid before you can do it.
