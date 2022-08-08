# tt-product-versioning-software

About:

Features:

Version:

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
