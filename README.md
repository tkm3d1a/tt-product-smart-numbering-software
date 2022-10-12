# tt-product-smart-numbering-software

About:
This is a personal project I am building to recreate some features I like and have used in previous auto-numbering systems.  It won't have a real
current purpose other than to emulate applications I have used that give "Smart Numbering" based on some various settings input by the user.  The idea
is mostly catered around building physical products, but there will be item types that can apply to any general project.  I plan to work on and complete this
as a main showcase of design and programming skills.  Please do not judge whatever the art ends up looking like...

Features: <<To be built using WPF/C#>>
- Main Screen allowing the user to make a new project
    - Project will require the following input to be created
        - Title
        - Description
        - Project Type
            - This will be from a predetermined list of...
                - Personal
                    - Private
                    - Public
                - Professional
                - Other (May remove this option?)
    - Creation of the project will give the user a dedicated project code to be used with that project
- *Future screens still tbd*

Version: v0.0.1
Date: 09-27-2022

## Internal resources
- basic-structure.txt
    - contains info/layout of the basic structure for program
    - Structure to be
        - Line 1: version number written as 'vX'
        - Line 2: date of last update writtenas 'mmddyyyy'
        - Till EOF: structure information

## Reference resources

[WindowsChrome for WPF non-client area modification](https://docs.microsoft.com/en-us/dotnet/api/system.windows.shell.windowchrome?view=windowsdesktop-6.0)

[Windows in WPF overview](https://docs.microsoft.com/en-us/dotnet/desktop/wpf/windows/?view=netdesktop-6.0)

[Video on switching views?](https://www.youtube.com/watch?v=xUwk2-_tRzo&ab_channel=ToskersCorner)

## Update Logs

**10/11/2022**
- Attempting to setup in VS
    - Setting up VS solution from existing folder is not simple
    - Need to investigate why solution explorer is not working (only showing folder view)
- Adding .gitignore info to cover
- Basic hello world c# file written to remember setup
    - Not compiled or setup though
- Need to set a goal for coming days to get some basic MVP working

## Copy-Paste from Notion

This will need to be cleaned and transposed to proper information at a later date.

```
Info:

Thinking of building an app for version control numbering. Build as a single language mvp first. Port to a web app later?

Questions:

- What language? C#/WPF
    - Why that language
    - Recommendation for small windows application to start
- Whats it for?
    - Personal project building
- What needs to be made to store the data

Features:

- Smart numbering
- No duplicates
    - Do a check before adding a number?
    - Or prevented by using sequencing?
- XxYy_Zzzz style? No, see below for final format: **pppp.tt.xxxx.aa**
    - What is being numbered?
        - Project number
            - 4 digit?
        - Item type
            - 2 digit?
        - Sequential number
            - 4 digit?
        - Revision number
            - Number or letters?
            - Letters give most options in shorter space
    - With above, example becomes:
        - Pppp.Tt.Xxxx.Aa
        - 10000 project options
        - 100 type options
        - 10000 numbers per type
            - Can be expanded with dash options?
            - Maybe reserve last digit for dash numbering?
                - Means 1000 numbers per type with 10 version per number?
                - Seems limiting
        - 676 revisions per item
            - 0A - ZZ
- Drop down menus for selections
    - Setup needed to make some drop downs?
- Json data file format?
- Gui format
- Create user
    - User roles, account, find issued numbers
- Save record of all numbers issued for searching
- Allow old records to be edited
    - Limited edits/data
    - Mainly to add “branches” to base part number
        - Branches done by adding “dash” number to individual records
- Export csv file of database
    - Means needs to have a database?
```
