[Instructions for how to install this extension:](https://www.youtube.com/watch?v=Ti0WFwj6CS8&ab_channel=TraderOracle)

CS file included at top level.

NOTE:
If you're importing the zip file as an addon, but you're getting an "import failed... duplicate method ... " message,
then it's highly likely you've already installed the json parser (Newtonsoft.json.dll, which is included in the zip file), and it's in this directory:

> Documents\NinjaTrader 8\bin\Custom

If the Newtonsoft.json.dll is in that directory, then take JUST the Gexbot.cs file (either extract from zip or take from the top level of this github repo) and place it into this directory:

> Documents\NinjaTrader 8\bin\Custom\Indicators

Then you should be able to add it onto your chart normally.