[Back to Portfolio](./)

Job Web Scraper
===============

-   **Class:** CSCI-325
-   **Grade:** A
-   **Language(s):** Java
-   **Source Code Repository:** [CSCI-325-final-project](https://github.com/Gabriel-TiradoRobles/CSCI-325-final-project)  
    (Please [email me](mailto:gjtiradorobles@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

The program simulates a system to manage a store's inventory, tracking any shipments, and generating various reports about the store. For the part that manages the store's inventory, the user has the ability to load an inventory through a formatted text file, create inventory items through the program, and edit data on individual items. The user also has the ability to look through and view the entire store's inventory and save the inventory onto a text file.

For tracking shipments and generating reports, when the user attempt to view the shipment list, the program will load all shipments from a predetermined text file. Afterwards the user can look through any shipments and delete any shipment they wish to remove as well. For generating reports, the user has a choice between generating a sales report, shipment report, or an inventory report.

## How to compile and run the program

How to run the program.

```bash
cd ./finalProject

pip install requests
pip install beautifulsoup4
python webscrappingProject.py >> output.txt
```

## UI Design

When the program is run without specifying an output file, the program will simply print the output to the command line (see Fig 1), when an output file is specified, the program will write down all output into the file (see Fig 2). If either there were no jobs found by the web scraper or the website given was invalid, the program will output stating that no jobs were found (see Fig 3).

**Fig 1. Example output to command line after website was successfully scraped.**
![screenshot](images/CSCI301/outputCLIWebScraper.png)  


**Fig 2. Example output to a file after website was successfully scraped.**
![screenshot](images/CSCI301/outputFileWebScraper.png)  


**Fig 3. Feedback when no job results were found.**
![screenshot](images/CSCI301/errorWebScraper.png)  

## 3. Additional Considerations

The two libraries listed in the **How to Compile** section must be installed before running the python script. To output to a file, you must add **>> fileName.txt** following the script name.

[Back to Portfolio](./)
