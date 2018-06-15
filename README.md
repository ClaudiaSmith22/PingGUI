#Ping GUI

This script opens a GUI that enables the user to run ping scripts and analyze ping activity. When the GUI first opens, the user has the option to select a connected IP Address from the drop down list, or enter the desired address in the text box. Once the IP Address is selected,the "Run Ping" button will start the script. As the script runs, the ping results will print to the GUI screen and be plotted to a seperate screen in real time. Additionally, the bottom in the top right corner will be filled green when the script is pinging succesfully; else it will be filled red.

Other buttons on the GUI enable the user to analyze previous ping csv files. "Success Graphs" will prompt the user to select a ping csv file, then plot the ping success and failures to the screen; "Latency Graphs" will prompt the user to select a ping csv file, then plot the ping latency times to the screen. "History" prints user-selected ping csv results onto the GUI screen, with the files total pings, success rate, and maximum consecutive failures printed at the bottomof the results. 

"Compare Graphs" gives the user the opportunity to plot two ping csv files onto the same screen with seperates axes. "Combine Graphs" will plot two ping csv files onto the same screen with a shared axis. When clicked, both will prompt a message box to the screen.If the user wishes to plot latency times of the files, select "Yes." If the user wishes to plot success/failures of the files, select "No" then "Yes."For all graphs, yellow points indicate a ping command that timed out and red points indicate a ping command that returned a "General Error."

To clear the GUI screen, press "Clear". If a ping script is running, CTRL + C will stop the script.To exit the GUI, press CTRL + C in the command window.

LANGUAGE: Python2.7
INSTALLATIONS: pingparsing, matplotlib, image      ("pip install {INSTALLATION NAME}")
