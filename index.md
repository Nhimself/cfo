## Charlie Foxtrot Ops Client download

Download the CFOclient that you need to keep your mods updated

###Download Cfsync.zip
1. Download the [zip file](https://cfsync.freedom-fighters.eu/cfsync.zip)
2. Unzipand it to a folder e.g. C:\CFSync

#### Edit the config.csm
1. You must edit the BasePath in config.csm file to match the folder of your mods. 
2. Any \'s must be doubled, for example C:\\MyFolder\\CFMods
```config.csm
{
    "BasePath":"c:\\CFMods",
    "RepositoryURL": "https://repo-cfsync.freedom-fighters.eu",
    "UpdatesURL": "https://cfsync.freedom-fighters.eu",
    "ModlistFile":"modList.cfm"
}
```

###Run cfsync.exe
1. Run CFsync.exe and the GUI will start
`When you run cfsync tool for the first time the tool will synchronise/download the mods needed to run the game please click the update button.`

![update](https://user-images.githubusercontent.com/2422220/152661476-e3aee837-5f3d-4a0b-b41f-60c79ab664ce.PNG)


####Keeping your mods updated
1. If you mods needs to be updated the top will show an update button
2. Click update and the mods will be downloaded including any new Servers or configuration for them

![updating](https://user-images.githubusercontent.com/2422220/152661480-e4595b47-a479-4300-9ca7-d39583d340ae.PNG)

##Joining the Server
1. Click on ```join``` button to connect to the server
If you click the Launch button Arma will start and give you the main menu with all the mods loaded and you will have to find the server manually.
If something goes wrong check out the logs in the logs tab. 

###Updating the tool
The tool will update itself when ever a new version is released. You will see the GUI disappear - then a command line / prompt will appear showing the updater running. When the update is complete the CFsync GUI will reappear.

### Support or Contact

Having trouble with CFsync? Check out our [documentation](https://nhimself.github.io/cfo) or reach out on Discord and we’ll help you sort it out.
