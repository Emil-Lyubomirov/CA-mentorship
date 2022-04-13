# CA python project documentation template

* ## Project Summary
*Summarize, with your own words, what is the project supposed to do, without technical details.*

*For example:*  
The purpose of this project is to get recipes from a cooking recipes website, then to sort this data based on given criterias...

* ## Requirements
*What are the requirements needed to be able to run this project.*

*For example:*  
This script uses [virtualenv with python3](https://docs.python.org/3/tutorial/venv.html)...  
To run the script successfully you must have access to...  
To run the script successfully you must have first installed...

* ## Usage
*Write down how the script is supposed to work from an outside view, without giving away unnecessary technical details.*

*For example:*  
The script is used to gather data from https://recepti.gotvach.bg/.
You can write the following command in your terminal:
  ```
  python main.py [-h] [-a <allergens>]
                 [-n <number of dishes>] [-l <last cooked>]
                 [-n <number of dishes>] [-p <products>]
                 [-n <number of dishes>] [-d <dish>] 
  ```
About the optional arguments:
  * -h,                    show this help message and exit
  * -n <number of dishes>  give number of dishes as an input
  * -a <allergens>         give list of allergens as an input
  * -l <last cooked>       give input search criteria option "last cooked"
  * -p <products>          give a list of products as a search criteria
  * -d <dish>              give a name of a dish as a search criteria  
  ...
  
* ## Tests
*Describe what type of tests are available for the project (unit tests, integration, system). How to run them? What coverage do they have?*  
*Without unnecessary technical details!*
  
* ## Technical Details
*Describe all the dechnical details*
  
*For example*  
To get data from https://recepti.gotvach.bg/, the script uses...
To send the data to ***, it uses...
  
### Workflow:
*Describe the workflow, step by step, of the script.*  
*This includes all the technical details!*  
*When and how is an input and output expected? When and how is data transfered or saved? When and how are any alghoritms used?*

*For example*  
1\. When you start the script you will be asked for an input...\
2\. Based on the input it will...\
3\. Then it will sort the gathered data based on...\
  ...\
*\. At the end an output is given that shows...
