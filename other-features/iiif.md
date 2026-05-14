# Importing from IIIF manifests

You can import images directly from IIIF manifests shared by cultural heritage institutions.
Start by downloading the [Tropy IIIF plugin](https://github.com/tropy/tropy-plugin-iiif/releases/latest) from GitHub. After the downloading the latest version of the plugin, open Tropy preferences and navigate to the plugins section to install it.

Download a IIIF manifest or copy the link to the IIIF images you wish to import. Select `File > Import > tropy-plugin-iiif` (or the name you configured in the plugin settings) and select the file, or paste the manifest’s link directly in the File Name bar and click *Open*.

As Tropy imports your images, the plugin tries to map the manifest’s metadata to the template selected for items. You may need to create a custom import template that matches the metadata fields describing the images.
See [the plugin documentation](https://github.com/tropy/tropy-plugin-iiif) for more details on using the plugin.

## Sample IIIF manifest for one image

> Grignion, Charles,
> “Decorated initial "T" to Ode on the death of a favourite cat,”
> (graphic, 1753),
> available in Lewis Walpole Library,
> Yale University

[IIIF Manifest](https://collections.library.yale.edu/catalog/16193053)

## Sample IIIF manifest for a manuscript containing multiple images

> Marcucci, Giacomo,
> Grandezze della città di Roma antiche e moderne come al presente si ritrovano, di nuovo ristampato in quattro linguaggi,
> (Roma: G. Mascardi, 1628),
> National Gallery of Art (US) Library

[IIIF Manifest](https://libraryimage.nga.gov/manifest/mms/99682033504896.json)
