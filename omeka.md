## 

The Omeka S plugin is currently in the beta stage.

## Installing the Plugin

Installing the Omeka S plugin is a multi-step process.

### **Part 1: Preparation**

1. Navigate to the plugin's GitHub repository [here](https://github.com/tropy/tropy-omeka/releases/latest).
2. Download the source code for the Omeka S plugin. Windows users should select .zip; Linux users should select tar.gz; Mac users can select either.

### **Part 2: In Omeka S**

1. Navigate to your Omeka's admin panel and click on _Users_. In the list of users, each name has a pencil next to it. Click on the pencil to open the user profile. Read more about how to add or edit users [here](https://omeka.org/s/docs/user-manual/admin/users/).
2. In the user profile, click on <em>API keys.</em>
3. You now need to add a new key. Type a name into the <em>New key label</em> field and hit <em>Enter.</em>
4. You should get a box that generates a <em>key\_identity</em> and a <em>key\_credential</em>. **Do not close this browser page until you have finished the process of installing and configuring the Tropy plugin.**![](/assets/api-key)

### **Part 3: In the Configuration File**

1. In Tropy, navigate to _Help_ and click on _Install plugin._ When the dialog box opens, navigate to where you saved your file from the GitHub repository. Click <em>Open</em>.
2. Once you have done that \(it will look like nothing happened\), navigate back to Help and click on <em>Show Plugins Folder.</em>
3. The <em>plugins</em> folder contains a configuration file \(config.json\). Open that file in the text editor of your choice \(e.g., Notepad, Atom, TextWrangler\).
4. Copy and paste this text into the file. You can delete the brackets that are there when you open the file.

```[{
  "plugin": "tropy-omeka",
  "name": "Omeka",
  "options": {
    "api": {
    "url": "http://<omeka_url>/api",
    "key_identity": "<your_identity>",
    "key_credential": "<your_credential>"
  }
}]
```

In the config file, you'll need to fill in a few pieces of information that you can get from your Omeka S installation. Every part of the file where you see carets \(&lt;&gt;\) is a piece of information you need to fill in \(remove the carets when you copy your own information in, but leave the quotation marks\).

* url: The URL of your Omeka site.
* key\_identity: Copy and paste from the Omeka users page.
* key\_credential: Copy and paste from the Omeka users page.

Finally, **save your config file**. And you are done with the installation and configuration! There's no need to restart Tropy in order to start using the Omeka export.

## Using the Plugin

Once you have everything set up, using the Omeka plugin is similar to the JSON-LD export. To export from Tropy, right-click on an item in the item table. From the right-click menu, select _Export Item &gt; Omeka._ This action will send your item straight to your items list in your Omeka installation. In the beta phase, there is no progress reporting in Tropy, so you'll need to go to your Omeka items list to see whether your items were exported. The lag time should be fairly short.

You can export one or multiple items at a time by selecting multiple items before right-clicking.

### Bringing Customized Templates into Omeka

Your customized templates in Tropy can be replicated in Omeka by following a few steps. 

#### Vocabularies

If you imported custom vocabularies into Tropy, you'll need to import them into Omeka as well. You can find instructions on how to do that [in the Omeka documentation](https://omeka.org/s/docs/user-manual/content/vocabularies/).

#### Rebuilding Templates

Items are exported from Tropy along with their custom templates. Provided that you have imported all the proper vocabularies, your item should show up in Omeka with all the expected fields. Custom labels, however, do not transfer. In order to retain your custom labels in Omeka, you'll have to make a [resource template](https://omeka.org/s/docs/user-manual/content/resource-template/) that reflects your custom template labels. You can then apply your resource template to your items individually or in bulk.

* To make a resource template, go to your Omeka site's admin page. In the lefthand menu, click on <em>Resource templates.</em> Then click on <em>Add new resource template</em> in the top right.
* Just as in Tropy, you'll need to give your template a name. \(If it makes sense, you might want to name it the same thing as your Tropy template.\)
* Then build your template using the same fields as your Tropy template. You can find your properties quickly by typing them into the <em>Filter properties</em> box on the righthand side. Make sure they are identical to the ones you've used in your Tropy template.
* Once you've compiled all your fields, you can edit the labels by clicking on the pencil next to each field. Add your custom label in the <em>Alternate</em> title box. Make sure you click <em>Set changes</em> once you've added your custom label.
* When you've changed all your custom labels, click <em>Add</em> in the top right to add your resource template to your Omeka resources.
* To apply your custom resource template to your items, return to the item list. Then click on the pencil next to an item to edit it. Set your resource template and then click <em>Save.</em> You can also do this action in bulk by using the <em>Batch actions</em> button at the top.







