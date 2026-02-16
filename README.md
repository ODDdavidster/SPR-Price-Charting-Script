# SPR-Price-Charting-Script
This is a Tamper Monkey Script used for price charting so that we don't have to do a bunch of math to find what price items should be.
This script has only ever worked with Tamper Monkey and Firefox / Librewolf.
I cannot get it to work with chrome and Tamper Monkey for some reason. 
I cannot be sure if it will work with Grease Monkey

## How to Use 
1. Install Tamper Monkey to Firefox from this link: https://www.tampermonkey.net/
2. Download the latest version of the script from the [Releases](https://github.com/ODDdavidster/SPR-Price-Charting-Script/releases) tab.
3. If Tamper Monkey doesn't automatically open to install the script, click on the "extensions" icon
  - Click on Tamper Monkey
  - Click on "dashboard" 
  - Click on the utilities tab
  - Click Browse next to Import from file
  - locate file and Install. 
    - You can update the script the same way.
4. Set the variables to the values you want. 
  - Click on the "extensions" icon of Fire Fox
  - Click on Tamper Monkey
  - Click on "dashboard" 
  - Select the SPR price "Price Charting Pricing Change... ...v#.#"
  - scroll down to the area labeled as User Variables and assign a multiplier value to each list. 
5. Load any game's page in www.pricecharting.com
## Important Notes
This is a repository to store my scripts as they where stored on discord and I don't wanna loose them. 
Because of that notes on each release might say something like "Changed Multiplier" when all multipliers are set to 0
The public versions of these scripts are all set to 0 so that anyone else who want's to use them can. I also plan to annotate my scripts better but I will never go back though old version to make them cleaner. 
There is a Magic Number system that will round any value listed on the page to one of a few values. Those being 2,5,8,10,12,15,18,20,25,30. These are numbers that we believe people gravitate to. 
You can change this by editing this variable 'magic_Number_List'
Values above 30 will always round to the nearest 5
