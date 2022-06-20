# Export to Omeka S

The Omeka S plugin is currently in the beta stage.

## Installing the Plugin

Installing the Omeka S plugin is a multi-step process.

### **Part 1: Preparation**

1. Navigate to the plugin's [GitHub repository](https://github.com/tropy/tropy-plugin-omeka/releases/latest).
2. Download the named Zip file containing the Omeka S plugin, but don't extract it.

### **Part 2: In Omeka S**

1. Navigate to your Omeka's admin panel and click on _Users_. In the list of users, each name has a pencil next to it. Click on the pencil to open the user profile. Read more about how to add or edit users [here](https://omeka.org/s/docs/user-manual/admin/users/).
2. In the user profile, click on _API keys._
3. You now need to add a new key. Type a name into the _New key label_ field and hit _Enter._
4. You should get a box that generates a _key\_identity_ and a _key\_credential_. **Do not close this browser page until you have finished the process of installing and configuring the Tropy plugin.**![Screenshot of Omeka S interface showing the notice after an API key is created.](../.gitbook/assets/api-key.bin)

### **Part 3: In the Plugins Pane**

1. Open Tropy and navigate to Preferences in the top menu \(in Windows, _Edit_ &gt; _Preferences_\).
2. In Preferences, click on Plugins. At the bottom of the Plugins pane, click on _Install Plugin_. Navigate to wherever you saved the plugin file from the GitHub repository; select it and click _Open._
3. Now your Omeka plugin should appear in the Plugins pane. Click on _Enable_ to continue setup.
4. In the form that opens when you enable the plugin, you now have to fill in all the fields in order for your plugin to work properly.
   * **Name**: You can name your instance of the Omeka plugin anything you like. We recommend that you give it the same name as your Omeka site.
   * **API URL**: Copy the URL of your Omeka installation and paste it between the `< >` \(removing the angle brackets\). You should have only one `http://`. Do not link to your individual site within your Omeka installation, but to the root Omeka S installation.
   * **Identity key and credential key**: These two fields come from the page you should still have open in your Omeka installation. Copy and paste them into the appropriate fields.

Once you've filled in these fields, you're all set---you can now close the Preferences window.

## Using the Plugin

Once you have everything set up, using the Omeka plugin is similar to the JSON-LD export.

To export from Tropy, right-click on an item in the item table. From the right-click menu, select _Export Item_.

You should see the name that you gave your plugin instance in the list. Click on the name.

This action will send your item straight to your items list in your Omeka installation. In the beta phase, there is no progress reporting in Tropy, so you'll need to go to your Omeka items list to see whether your items were exported. The lag time should be fairly short.

You can export one or multiple items at a time by selecting multiple items before right-clicking.

### Bringing Customized Templates into Omeka

Your customized templates in Tropy can be replicated in Omeka by following a few steps.

#### Vocabularies

If you imported custom vocabularies into Tropy, you'll need to import them into Omeka as well. You can find instructions on how to do that [in the Omeka documentation](https://omeka.org/s/docs/user-manual/content/vocabularies/).

#### Rebuilding Templates

Items are exported from Tropy along with their custom templates. Provided that you have imported all the proper vocabularies, your item should show up in Omeka with all the expected fields. Custom labels, however, do not transfer. In order to retain your custom labels in Omeka, you'll have to make a [resource template](https://omeka.org/s/docs/user-manual/content/resource-template/) that reflects your custom template labels. You can then apply your resource template to your items individually or in bulk.

* To make a resource template, go to your Omeka site's admin page. In the lefthand menu, click on _Resource templates._ Then click on _Add new resource template_ in the top right.
* Just as in Tropy, you'll need to give your template a name. \(If it makes sense, you might want to name it the same thing as your Tropy template.\)
* Then build your template using the same fields as your Tropy template. You can find your properties quickly by typing them into the _Filter properties_ box on the righthand side. Make sure they are identical to the ones you've used in your Tropy template.
* Once you've compiled all your fields, you can edit the labels by clicking on the pencil next to each field. Add your custom label in the _Alternate_ title box. Make sure you click _Set changes_ once you've added your custom label.
* When you've changed all your custom labels, click _Add_ in the top right to add your resource template to your Omeka resources.
* To apply your custom resource template to your items, return to the item list. Then click on the pencil next to an item to edit it. Set your resource template and then click _Save._ You can also do this action in bulk by using the _Batch actions_ button at the top.

