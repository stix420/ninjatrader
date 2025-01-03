UPDATED INSTALL INSTRUCTIONS (1/2/24):

First, download the GexBot.cs file, and the Newtonsoft.Json.dll.

Open a new Ninjascript Editor. Right click the blank space and go to "References". In your list of references, if you do not have a reference to "newtonsoft.Json.dll", then click "add" and go to the file location to where you downloaded or placed the Newtonsoft DLL. Add it and click OK.

Next, click the "+" sign at the bottom of the Ninjascript Editor to create a "New Indicator". Name it "Gexbot" (or whatever you want), you can fill in the description. Hit Generate (no need to bother with the other settings).

Now take the Gexbot.cs text and copy paste it into the Editor (overwrite everything in there). Hit compile. You should now have access to the Gexbot indicator on your chart.

Possible issue: if you've compiled/downloaded an old version of the indicator and attempted to remove it by deleting the files from your file directory, Ninjatrader might be holding onto a reference to an older version of it. In which case you might not see the indicator in your list in the "Ninjascript Explorer" inside the editor, but you would still be able to add it to your charts (when hitting ctrl + I).

In order to clear references to old indicators, open a new Ninjascript Editor, ensure that the indicator you would like to clear is NOT in the list of indicators to the right, and then hit compile. This will ensure NT will recompile all indicators in your bin/Custom folder, and remove any old references. Then you can proceed as normal.