
# MyFranchise

### Installation/Updating Application
- If this your first time downloading the app, simply choose the release with the highest version and grab JUST the MyFranchise-Setup-(version number).exe file.
- You will likely be warned that the file is not safe, choose to KEEP ANYWAY. When installing, you might get a blue pop up that says it is unknown. Click MORE INFO and choose RUN ANYWAY to proceed.
- If you are uncomfortable doing this, it is no problem, but you will not be able to install and use the application.
- Any future updates will automatically alert you inside the app. Once you are alerted a new version is out, click CLOSE AND INSTALL. This will run in the background (No visual installer), after a couple of seconds, click the app to re-open it. You will see you are on the latest version now.
### Loading Franchise File
- You can choose from *CURRENT FRANCHISE FILES* or click *OPEN FRANCHISE* to select a file that is not currently in your Madden save file location.
- Once selected, you will see the file is loading. This might take a minute, please be patient. If the file has not loaded in 30 seconds, please let us know.
- You ONLY can load your file in the following stages:
    - Pre-Season Week 1 - Pre-Season Week 4 (Note: Pre-Season Week 4 will have a blank franchise-hub for now, can still view the rest)
    - Regular Season Week 1 - Regular Season Week 18
    - Playoffs (Exlcuding Pro Bowl)
    - Staff Signing Stage of Off-Season (This is the week AFTER the Super Bowl)
- If you are using custom teams (either through FIFA Mod Manager or Relocation Teams), you will need to create your own logos and wordart to use. More on that below.
### Viewing the Franchise hub
- The franchise hub is the first page you will see when your file is finished loading.
- You can click the games at the tob in the Score Hub to view the *GAME PREVIEW*.
    - Important Note: Pre-Season WILL have the wrong team stats, this is corrected once in Regular Season.
#### Rankings Page
- The current rankings are simply the leagues standing order. The offensive and defensive rankings are the in-game off/def rankings. There are plans to create a custom ranking system for better immersion.
#### Schedule Page
- You can view the league schedule for the current season AND any season you have ran the *EXPORT SEASON* tool on, more on this later. There is a dropdown to change which year you want to view if you have any archived seasons.
- The games list what broadcast is recommended based on the real life contracts for the networks. Feel free to use whatever you want.
- There is a bug when switching from Pre-Season to Playoffs. Remember to go from Pre-Season to Regular Season and Regular Season to Playoffs to avoid any viewing issues.
#### Stats Page
- The league stats page has multiple tabs for each statistical category. Each category has certain things you can sort by. If it has a SORT icon, you can sort by it. If it does not, you CANNOT.
- Kicking and Returns currently cannot sort any further.
- Export Stats button at the bottom will export the current loaded stats table. Ex: If you are viewing the PASSING stats, it will export PASSING stats. Kicking and Returns will prompt you twice to save both tables, the save dialog will tell you at the top left what stats are currently saving.
- The dropdown on the right is to change the year to view any archived seasons using the *EXPORT SEASON* tool.
- You can click on any player to access his *PLAYER CARD*.
#### Standings Page
- Use the tabs at the top to swap between standings view. The dropdown on the right will show you previous standings of any archived seasons.
- Clicking a team name will take you to their *TEAM PAGE*.
- You cannot sort on the standings table, they are sorted by their records.
- Playoff Markings (xyz*) are as follows:
    - x = Clinched Playoff
    - y = Clinched Wild Card
    - z = Clinched Division
    - (*) = Clinched Division and Homefield Advantage
#### Players Page & Free Agents Page
- You can view all players who are on an NFL Roster (Players) or Free Agents (Free Agents). If a column has a SORT icon, you can sort by this field.
- You can use the search field at the top in the middle to search for any players who are on an NFL roster. You can also use the filter on the right to filter by POSITION.
- Clicking a player's name will open their *PLAYER CARD*.
#### Player Card
- You can view a specific player and his attributes, stats, and traits. Abilities are not currently supported but will be in a later update.
- The ACTIONS page will allow you to sign or cut a player from/to a team depending on their current status. To sign a player to another team, you must cut him first, then sign him.
- Currently you cannot sign or cut to/from the practice squad.
- Signing/Cutting does not account for teams exceeding their salary cap, be aware of what you are doing.
- You can set custom portraits under the ACTION tab. Simply click SET PORTRAIT and choose the .png you want to use. It is HIGHLY recommended to use a square ratio, 256x256, 512x512, etc.
- Clicking on another player under SWITCH player will open that player on the PLAYER CARD.
### Tools Page
- The tools page is where you will find any tool that can be ran to further enhance your franchise file. Currently, there are two tools at launch. TDawg's Progression and Export Season.
- There are instructions included on TDawg's Progression tool, READ THEM. 
    - IMPORTANT: Only run the progression module ONCE PER SEASON.
- Export season can only be used the week after the Super Bowl (Staff Hiring - Off-Season). If you fail to run the module at this time, you will lose any season information and not be able to view it in the app.
- If you are coming from TDawg's Excel Tool, you will run the INITIAL PROGRESSION, this will re-roll your potentials but not mess anything up. Make sure to do this in a FRESH season that you have not already ran progression in.
- On the home screen where you load your file, you will see a FOLDER ICON if that franchise has existing progression data. If you are not supposed to have progression data on a franchise and it shows the folder, click the FOLDER ICON in the bottom right of the Homepage and go to PROGRESSION folder and delete the folder matching your franchise file.
- The tool will alert you if you are running the wrong module and at the wrong time, but you can possibly could mess something up. Each loaded file has a backup for this reason. See above to locate your backup.
### Viewing Team Pages
- Team pages all have multiple tabs with team/player information. There is not much else to say, but do want to make a point on some of the things that come in handy:
    - On the roster, depth chart, stats tabs, you can filter to any posiiton and quickly view other teams by simply clicking the logos at the very top of the screen. This would allow you to quickly see what QBs are on what teams, etc.
    - On the SCHEDULE tab, you can click a game that is UNPLAYED and view the *GAME PREVIEW*.
    - There is no sorting on the FINANCES page, this is on the list of things to do.
### Custom Logos/Wordart
- The app will default to NFL Logo for any CUSTOM or RELOCATED team unless you create a custom logo png to place in the AppData Logos folder. 
- Download the templates from this repo to get your sizing to match the embedded logos/wordart. 
- On the home page (Where you load your file), click the bottom right folder to open the AppData for the app. In the LOGOS folder, you will see a folder for each franchise you have loaded. Place your logo in the correct folder(s) and they will be used instead of the default NFL logo.
- The following format MUST be followed for images:
    - The image MUST be a .png file. 
    - The filename MUST be ALL LOWERCASE.
    - The filename MUST match the team's ShortName in the file (Ex. Tampa Bay is TB so tb.png)
    - Wordart file name must have teamname_wordart.png (Ex. tb_wordart.png)
### Reporting Bugs/Issues
- To report any bug or issue, please head over to the Madden Modding Community Discord and be very clear about what is going on.
- Do not simply say "My tool is broken", "This messed my file up". You will be ignored. Always provide clear and concise details on the issue at hand, screenshots help a lot.
