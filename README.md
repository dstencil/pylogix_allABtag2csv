## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
Script for using pylogix to save all controller and program tags of Allen Bradley compactlogix,controllogix, and micro800(controller tags only) PLC's into a .csv format with file based version control (ipadress_date.csv).
	
## Technologies
Project is created with:
* Python 3.10: https://www.python.org/
* Pylogix: https://github.com/dmroeder/pylogix
	
## Setup
To run this project, install it locally using Python

```
$ pip install pylogix 
(Linux)
$ python3 ./pylogix_allABtag2csv.py 
(Windows)
$ python3 C:\Users\Downloads\pylogix_allABtag2csv.py
```
### Shell

``` 
$ input IP Address of target Allan Bradley Controller: (xxx.xxx.xxx.xxx)

$ if Micro800 series plc input "y" at next prompt otherwise press any key: 

* printout of filename and location is found at end of script printout

* open file in your preffered .csv software (Excel, notepad, mysql, etc.)
```
