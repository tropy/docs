---
description: >-
  This page describes how you can help Tropy re-associate images if you move
  them to a different location.
---

# Moving photos

Generally, we recommend that you put your photos into a permanent home before you put them into Tropy. However, sometimes you have to move your photos once you've put them in. 

Tropy does not make a copy of your photos--it only maintains a link to where they are stored on your computer. So if you move your photos, you'll need to tell Tropy their new location. You'll know that Tropy can't find your photos if you click on them in the photo pane and see an exclamation point flag. 

#### Re-associating Photos

To re-associate your photos, right-click on one of the photos and click _Consolidate Photo._ A dialog box will pop up asking you to identify the new location of the photo file. 

![Right-click on the photo name and select Consolidate Photo.](../.gitbook/assets/consolidation-box.png)

Once you've selected the new location, click _OK._ Another box will pop up asking "Do you want Tropy to automatically check and resolve further missing photos at this location?" If you click _Yes,_ Tropy will use the location you've just provided to re-associate all the other photos it can find based on their relationship to your newly identified photo. 

![The dialog box asks whether you want Tropy to look for your other photos as well.](../.gitbook/assets/auto-consolidation-check%20%281%29%20%281%29.png)



For example, let's say you import the photos straight from your Desktop into Tropy and then later move them to a more permanent location, so some photos go from `/Users/ariadne/Desktop` to `/Users/ariadne/Pictures/A` and the rest to `/Users/ariadne/Pictures/B`. To re-associate all the photos, you need to consolidate one photo at each new location, that is, one that went to folder `A` and one that went to folder `B.`Tropy can then consolidate all the other files in both folders.

Or let's say you get a new computer and you move your project and your photos over to the new computer; but on the new computer some paths are different, for example, let's say you have a different home directory and so now your pictures are at `/home/ariadne/Pictures/A` and `/home/ariadne/Pictures/B`. In this case you can consolidate a single photo in either of the two folders: Tropy should still be able to re-associate all the photos, because, relative to each other, they all moved to a single new location.

**Bulk re-association works only if you have not changed file names when you moved your folders. If you change file names, you will have to consolidate each photo individually.**

