## Using Metadata

When you take photos of archival materials, you can collect a large amount of information about your sources that will aid you in using them for your projects. It’s important to record that information as soon as possible, as it’s very easy to forget key pieces. Tropy gives you the chance to attach information to your research photos rather than keeping that information somewhere separate from your photos. But it’s still important to record the right information, in the right format.

### What is metadata and why is it important?

Metadata is descriptive information; in other words, it’s information that describes sources such as documents, images and objects.

It’s crucial that you record metadata about your sources for several reasons.

* First, metadata such as the location in the archives will allow you to craft citations that allow others to find your sources.
* Second, metadata will allow you to find specific sources and sources with particular attributes when you come to analyze and write about your research.

Structured metadata is categories or fields, such as title, date, or creator, that you fill in for every item. Tropy templates are forms created to describe particular kinds of material or material from specific collections or archives. Templates control the information you create by limiting it to a set of categories. The categories you include in a template should be the characteristics that are important to you as you use the material.

In addition, Tropy also offers tags, which provide a means of creating unstructured metadata: you can use any word or set of words, no matter how idiosyncratic, as a tag, rather than following a set of fields. You can also add as many or as few tags as you want to an item, rather than the specified set of information in a template.

### Where does metadata come from?

If you’ve been able to find sources to photograph in an archive or library, then you’ve already used metadata. Library catalogs and finding aids are full of metadata that is useful for you. Librarians and archivists craft descriptions of their collections to help researchers who use their collections, and you should absolutely take advantage of their work. Some of the metadata you’ll want to record in Tropy comes straight from the catalog or finding aid, such as archive name, collection name, and organizational elements such as identifier, box and folder.

Additional metadata comes from each individual source itself, and is known as item-level metadata. Few archival finding aids or catalogs include item-level metadata; it is more common to describe a collection only to the level of each folder in a box, or each box. For example, the [finding aid](http://rs5.loc.gov/service/mss/eadxmlmss/eadpdfmss/2003/ms003007.pdf) for the Pinkerton National Detective Agency Records at the Library of Congress records that Box 79 contains 3 folders of reports of the investigation of the Bonner Manufacturing Co. jewel theft from 1924. Item-level metadata describing those reports could include the name of the agent who wrote the report, the date of the report, the location referred to in the report, whether the report was handwritten or edited and typed, the type of investigative methods used \(shadowing, undercover surveillance, informants, interviews\), and the subject of the report. Features of a source included in a Tropy template are characteristics of every report; features that appear in only some sources could be tags or simply recorded in the notes.

### Using Standards and Vocabularies

Metadata can be as free-form as you want. But it’s generally best to try to record metadata using a standard that already exists. Why? Metadata standards provide consistency both within your own projects and also in the larger community of scholarship about your sources. Each category in a Tropy metadata template must be linked to a category \(property\) from an existing metadata standard.At present you can only use each property once in a template. Several standards, or vocabularies, are included in Tropy; you can also [add more vocabularies](/using_tropy/templates/vocabularies.md). Metadata specialists in almost every field of study have created many vocabularies, so there’s a good chance that whatever property you need already appears in an existing vocabulary. To search for a metadata vocabulary that meets your needs, start with [Linked Open Vocabularies](http://lov.okfn.org/dataset/lov/).

This document provides best practices to create good metadata for the content you upload to Tropy. A template in Tropy provides a means of creating structured metadata about your sources. Each item in a Tropy project can have [its own unique template](/using_tropy/templates/create-template.md), though you’ll probably find that only one or two templates, or a template for each collection from which you have sources, will meet your needs. Three templates ship with Tropy; we’ve designed these basic templates to capture the information most commonly useful to researchers. In most cases, you can create a template for your research by [editing one of those templates](//using_tropy/templates/edit-templates.md) to add additional categories of information \(fields\) or deleting categories that are not important to you.

Descriptive metadata will allow you to quickly and easily locate your sources at the item level. Therefore, each item should have its own unique metadata entry, but images from the same source will often share information like collection name and location, which in Tropy are easy to add in bulk or as default values in a template. There are three main things to remember when writing good metadata:

1. Be as descriptive as possible.

2. Be consistent.

3. Pay attention to the purpose of each category/field.

## Metadata & Tropy Templates

What follows is a brief explanation of the fields used in two of the default templates that are included with Tropy. Tropy also ships with a neutral Dublin Core template, which retains the Dublin Core labels. In the template list, you'll see Tropy Photo and Tropy Photo Selection as well. While you can create additional templates for the photo and selection level, we recommend leaving the default photo and selection templates as default and doing your heavy metadata work on the item level.

### Tropy Generic

Incorporating widely used forms of archival organization \(box, folder, identifier\) and basic features of research material \(author, date, type of source\), this template is intended to provide a framework that applies to many kinds of research. Additional fields can be added to customize the template to include characteristics of specific collections. At present you can only use each property once in a template.

#### Title

_Title_ is the name of the source. Documents such as books, pamphlets, and even memos have obvious titles that can be recorded in this field. Best practice for metadata suggests that you consider including more than just such a title, and use this field for a short description of the document that provides the essential information about it.

A descriptive title might repeat some of the information that you include in other categories in the template \(like author, type of document, subject of the document\) but including it here gives you a brief picture of the source in one place. Such a summary description would be useful in Tropy in allowing you to quickly identify the nature of a source when scrolling through your material in project view.

_Property used_: purl.org/dc/elements/1.1/title

#### Author

_Author_ is the individual or organization responsible for creating a source.

In order to effectively organize and find sources based on names, best practice suggests the following format: Last Name, First Name, Middle Initial.

_Property used:_ purl.org/dc/elements/1.1/creator

_Label_: The Dublin Core metadata standard was designed to be core categories applicable to a wide range of resources, so it uses _creator_ rather than more specific forms such as author, filmmaker, sculptor, etc. This template replaces “creator” with “author” to reflect the specific form of the documents to which it will be applied. You could also re-label the field to “artist,” “architect,” or whatever type of creator you are working with.

#### Date

_Date_ is the date a source was created. If you are unsure of the exact date, it is always better to include a date range than no date at all.

In order to effectively organize and find sources based on date, use a consistent date format like YYYY-MM-DD \(known as ISO format\).

_Property used_: purl.org/dc/elements/1.1/date

_Note_: You may want to describe a source in terms of dates in addition to when it was created, such as the date or dates referred to in the source, or dates when a source was modified or edited. In these cases, there are additional metadata properties that you can use to add additional date fields to your template, such aspurl.org/dc/elements/1.1/coverage,purl.org/dc/terms/created, orpurl.org/dc/terms/modified.

#### Type

_Type_ is the type or genre of source. This could be a type of document \(e.g., correspondence, book, pamphlet, memo, form\) or genre of document \(e.g., autobiography, psychiatric report, trial transcript\). It could also be a type or genre of image or object \(e.g., painting, map, diagram, cartoon\).

In order to effectively organize and finds sources based on type, use consistent terms or a controlled vocabulary. [The Dublin Core Metadata Initiative Type Vocabulary](http://dublincore.org/documents/2003/02/12/dcmi-type-vocabulary/) and [Getty Art and Architecture Thesaurus](http://www.getty.edu/research/tools/vocabularies/aat/) are good resources.

_Property used_: purl.org/dc/elements/1.1/type

#### Archive

_Archive_ is the location at which the source can be found, e.g., the Library of Congress.

_Property used_: purl.org/dc/elements/1.1/source

You could copy and modify this template to create a template for a specific archive. If you added a default value in this field, you would not have to enter the information for each item or group of items.

#### Collection

_Collection_ is the name of the collection of which the source is a part, e.g., the Pinkerton National Detective Agency Records. You should consult a catalog or finding aid to ensure that you use the correct title for a collection.

_Property used_: tropy.org/v1/tropy\#collection

Existing metadata vocabularies do not offer elements that fit the way that archival material is typically organized. For that reason, Tropy includes a limited number of custom metadata elements.

You could copy and modify this template to create a template for a specific archive. If you added a default value in this field, you would not have to enter the information for each item or group of items.

#### Box

_Box_ is the unit in the collection which the source can be found. This category may not be needed for all sources, as not all collections use boxes as a form of organization, or label or number boxes. If that is the case, you could copy and modify this template to create one for such a collection by deleting this field. You could also simply leave this field blank.

_Property used_: tropy.org/v1/tropy\#box

Existing metadata vocabularies do not offer elements that fit the way that archival material is typically organized. For that reason, Tropy includes a limited number of custom metadata elements.

If the archive in which you are working has different terms for how its material is organized \(e.g., folio, or container, rather than box\), you could modify the template and change the label for this field to one appropriate to the collection from which your sources come.

#### Folder

_Folder_ is the folder \(within a box\) in which a source can found. This category may not be needed for all sources, as not all collections use folders as a form of organization, or label or number folders. If that is the case, you could copy and modify this template to create one for such a collection by deleting this field.

_Property used_: tropy.org/v1/tropy\#folder

Existing metadata vocabularies do not offer elements that fit the way that archival material is typically organized. For that reason, Tropy includes a limited number of custom metadata elements.

#### Identifier

_Identifier_ is a call number or URL at which a source can be found. This category may not be needed for all sources, as not all collections use identifiers as a form of organization. This field could also be used to include a link to an online finding aid for a collection.

_Property used_: purl.org/dc/elements/1.1/identifier

#### Rights

_Rights_ is information about how you, a researcher, can use each item. This can include copyright information, as well as specific information from the archive where the image came from. Where possible, best practice is to include a link/URL to the information on rights provided by the archive or library where the source is located.

See Tropy’s [rights documentation](https://docs.tropy.org/beginning/rights.html) for more information on how to assess and describe rights for your sources.

_Mandatory field_: Given how easy it is to share digital images and publish them online, Rights is a required field in all the templates shipped with Tropy in order to emphasize how important it is that researcher know and acknowledge the rights they have to publish their photos.

_Property used_: dc/elements/1.1/rights

### Tropy Correspondence

Incorporating elements from the Tropy Generic template, this template is intended specifically for correspondence, a widely used type of source. Additional fields can be added to customize the template to include characteristics of specific collections.At present you can only use each property once in a template. Most of the Tropy Correspondence fields appear in the Tropy Generic template as well. We’ve highlighted here the fields that have been added to or modified in Tropy Correspondence.

#### Type

_Type_ is the type or genre of source. Although this template is designed for one specific type of source, this information needs to be included so that you can identify the correspondence within your larger collection of material

_Property used_: purl.org/dc/elements/1.1/type

Since this template is designed for one specific type of source, this template includes that type, “correspondence,” as a default value in this field, which means you do not have to enter the information for each item or group of items. You can edit this field to have a more specific value, such as "circular" or "letter excerpt."

#### Recipient

_Recipient_ is the individual to whom a letter is addressed.

In order to effectively organize and finds sources based on names, best practice suggests the following format: Last Name, First Name, Middle initial.

_Property used_: purl.org/dc/terms/audience

_Label_: This template replaces “audience” with the more specific term “recipient” to reflect the specific form of the documents to which it will be applied.

#### Location

_Location_ is the location from which a letter was sent.

To effectively organize sources, use a controlled vocabulary. The [Library of Congress Name Authorities](http://authorities.loc.gov/help/name-auth.htm), [Getty Thesaurus of Geographic Names](http://www.getty.edu/research/tools/vocabularies/tgn/), and [GeoNames](http://www.geonames.org/) are good resources.  
_Property used_: purl.org/dc/elements/1.1/coverage  
_Label_: This template replaces _coverage_ with the more specific term _location_ to reflect the specific form of the documents to which it will be applied. \(The Dublin Core element coverage can refer to spatial or temporal features of a source.\)

## **Tags**

A tag is a freely chosen keyword or phrase; it can be as idiosyncratic as you want. It can refer to any feature of a source, rather than a specific category, as in the structured metadata of a Tropy template. You can [add as many tags](//using_tropy/project_view/tags.md) as you want to an item.

Essentially, there is no such thing as a bad tag; if it’s useful to you, it’s a good tag. However, when you create tags, you need to take care not to use homonyms\(the same tags used with different meanings\) and synonyms \(multiple tags for the same concept\), which can lead to ineffective organization of your material \(e.g., the tag “orange” could refer to the color or the fruit\). Likewise, being careful to use only singular or plural will help produce useful tags.

In Tropy, one distinction between template fields and tags is in how you access the items described. All the items with a tag can be found simply by clicking on the tag in the project view. To find all the items described with a particular term in the metadata template, you need to search for that term in the project view.

## **Photo metadata**

Digital cameras store information about images in the header of the digital file, using the Exif standard. That information usually includes the camera make and models, the camera settings and the date the photograph was taken.

Tropy imports some of that photo metadata, and displays it under the item metadata:

* the file name;
* the date the image was taken;
* the image size in pixels;
* the file size.



