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

### **Part 3: In the Plugins Pane**
1. Open Tropy and navigate to Preferences in the top menu. 
2. In Preferences, click on Plugins. At the bottom of the Plugins pane, click on _Install Plugin_. Navigate to wherever you saved the plugin file from the GitHub repository; select it and click _Open._
3. Now your Omeka plugin should appear in the Plugins pane. Click on _Enable_ to continue setup.
4. In the form that opens when you enable the plugin, you now have to fill in all the fields in order for your plugin to work properly.
<blockquote> Name: You can name your instance of the Omeka plugin anything you like. We recommend that you give it the same name as your Omeka site.</blockquote>
<blockquote>API URL: Copy and paste the URL of your Omeka site between the < > (removing the angle brackets). The URL you paste in will always end in "omeka-s".</blockquote>
<blockquote>Identity key and credential key: These two fields come from the page you should still have open in your Omeka installation. Copy and paste them into the appropriate fields.</blockquote>

Once you've filled in these fields, you're all set---you can now close the Preferences window.


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







