## Installing the Plugin

Installing the Omeka S plugin is a multi-step process.

### **Part 1: Preparation**

1. Navigate to Tropy's GitHub repository [here](https://github.com/tropy/tropy-omeka/releases/latest).
2. Download the source code for the Omeka S plugin. Windows users should select .zip; Linux users should select tar.gz; Mac users can select either.

### **Part 2: In Omeka S**

1. Navigate to your Omeka's admin panel and click on _Users_. In the list of users, each name has a pencil next to it. Click on the pencil to open the user profile.
2. In the user profile, click on _API keys. _
3. You now need to add a new key. Type a name into the _New key label_ field and hit _Enter._
4. You should get a box that generates a _key\_identity_ and a _key\_credential. Do not close this browser page until you have finished the process of installing and configuring the Tropy plugin._

### **Part 3: In the Configuration File**

1. In Tropy, navigate to _Help_ and click on _Install plugin._ When the dialog box opens, navigate to where you saved your file from the GitHub repository. Click _Open._
2. Once you have done that \(it will look like nothing happened\), navigate back to _Help _and click on _Show Plugins Folder. _
3. The _plugins_ folder contains a configuration file \(config.json\). Open that file in the text editor of your choice \(e.g., Notepad, Atom, TextWrangler\).
4. Copy and paste this text into the file. You can delete the brackets that are there when you open the file.

`[{`

`"plugin": "tropy-omeka",`

`"name": "Omeka",`

`"options": {`

`"api": {`

`"url": "http://<omeka_url>/api",`

`"key_identity": "<your_identity>",`

`"key_credential": "<your_credential>"`

`}`

`}`

`}]`

In the config file, you'll need to fill in a few pieces of information that you can get from your Omeka S installation. Every part of the file where you see carets \(&lt;&gt;\) is a piece of information you need to fill in \(remove the carets when you copy your own information in, but leave the quotation marks\).

* url: The URL of your Omeka site.
* key\_identity: Copy and paste from the Omeka users page.
* key\_credential: Copy and paste from the Omeka users page.

Finally, **save your config file**. And you are done with the installation and configuration! There's no need to restart Tropy in order to start using the Omeka export.

## Using the Plugin

Once you have everything set up, using the Omeka plugin is similar to the JSON-LD export. To export from Tropy, right-click on an item in the item table. From the right-click menu, select \_Export Item &gt; Omeka. \_This action will send your item straight to your items list in your Omeka installation.

You can export one or multiple items at a time by selecting multiple items before right-clicking.

