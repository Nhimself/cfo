## CharlieFoxtrotOps Client download

Download the CFOclient that you need to keep your mods updated

###Download Cfsync.zip
1. Download the [zip file](https://github.com/Nhimself/cfo/blob/main/cfsync.zip)
2. Unzipand it to a folder e.g. C:\CFSync

#### Edit the config.csm
1. You must edit the BasePath in config.csm file to match the folder of your mods. 
2. Any \'s must be doubled, for example C:\\MyFolder\\CFMods
```config.csm
{
    "BasePath":"c:\\CFMods",
    "RepositoryURL": "https://nhimself@repo-cfsync.charliefoxtrotops.com",
	  "UpdatesURL": "https://github.com/Nhimself/cfo",
    "ModlistFile":"modList.cfm"
}
```

###Run cfsync.exe
1. Run CFsync.exe and the GUI will start
`When you run cfsync tool for the first time the tool will synchronise/download the mods needed to run the game please click the update button.`

####Keeping your mods updated
1. If you mods needs to be updated the top will show an update button
2. Click update and the mods will be downloaded including any new Servers or configuration for them


Click on join to connect to the server.
Click Launch will run Arma to the main menu with all the mods.
If something goes wrong then you can find the logs and link to historical files from the logs tab. Drop the file onto the discord channel with some note about what happened.
The tool updates itself just by running it. You will see it disappear and a command line appear showing the downloading and running of updates and then your GUI will reappear.

You can use the [editor on GitHub](https://github.com/Nhimself/cfo/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.




### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Nhimself/cfo/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
