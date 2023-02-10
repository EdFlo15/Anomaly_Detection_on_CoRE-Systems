# Anomaly_Detection_on_CoRE-Systems

Records of Operations on the CoRE Systems
Source data: https://data.mendeley.com/datasets/9k3pkspfxm/1

Description The data is about the behaviors and activities of how participants use the CoRE system (http://core.cs.iastate.edu) and attack the system, such as clicking the buttons and links, filling out a form on the website, submitting request to the system server and searching information about the system.

There are two spreadsheets, data of the first-round experiment and data of the second-round experiment. In each spreadsheet, there are two sheets, "raw records" and "processed data". In the sheet of raw records, each row is a snapshot of user’s action and system context information when the user performed an operation on the CoRE system. Each raw record has the following information:

(1) Time: the time point when the user performs an operation;

(2) Login ID: user’s login ID provided by the CoRE system;

(4) Action: including mouse click on a button or a link, and selection on a drop-down menu;

(5) Page: the current webpage where the action occurs;

(6) Next Page: the next page that the system will be directed to;

(7) Content: contents on the webpage (user’s submitted input, system’s responses to the user’s action);

(8) Goal: users' self-reported goal.

The processed data is processed from the raw records. Each row in the sheet of processed data has the follwoing information: (1) Observation: including user's action and content in the raw records;

(2) Time Interval: the time interval between the time points of user's consecutive actions;

(3) Goal: users' self-reported goal.
