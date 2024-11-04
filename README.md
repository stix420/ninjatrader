[Instructions for how to install this extension:](https://www.youtube.com/watch?v=Ti0WFwj6CS8&ab_channel=TraderOracle)

CS file included at top level.

If you're importing the zip file as an addon, but you're getting an "import failed... duplicate method ... " message, then firstly, check this directory:

> Documents\NinjaTrader 8\bin\Custom

for the Newtonsoft.json.dll file. If you're getting the import failed error it's highly likely you've already installed the json parser prior.
If it's there, simply take the Gexbot.cs file (it's both in the zip as well as in the top level of this repostiroy) and place it into your

> Documents\NinjaTrader 8\bin\Custom\Indicators

folder. You should see a bunch of other cs files in there, just place the Gexbot.cs file (and nothing else from the zip!) in there. Then you should be able to add it onto your chart normally.