# Voyant: A text-analysis tool

Voyant is a powerful tool that can be used for analyzing text.  In this tutorial we will look at Voyant: what it is, details on how to use a few of its many features, and why it can be useful for humanities research.  

[Voyant](http://voyant-tools.org) runs online so it is not necessary to download any software.  To begin, you can either upload a text file or paste in a text or link, then click 'reveal'.  For this tutorial, we will be looking at [The Travels of Marco Polo](https://archive.org/stream/marcopolo00polouoft/marcopolo00polouoft_djvu.txt).

### Understanding and Using Voyant's Interface
Once Voyant has 'revealed' your chosen text, it will look something like this:
![interface](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202016-01-19%20at%207.19.55%20PM.png)

The text will be on the right while the left has a word cloud and statistics for the most frequent words within the text.  For our text, the words 'of', 'the', 'and' and 'in' were the most frequent.  Those words do not elucidate much about the text.  A good first step after inputting a corpus into Voyant is to clean it up a little.

To start, hit the cog in the left-hand corner next to 'Cirrus' to get the search options.  Here, you can edit the 'stop-words', the words which will not be taken into consideration in the text analysis.  You can manually put in words as well as choose from preexisting lists, depending on the language.  For English, the Taporware list exists.  Click the box 'Apply Stop Words Globally' and then click ok.  

![stop words](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202016-01-19%20at%207.34.38%20PM.png)
A new word cloud should appear.  Now for our text, the words 'city', 'country', 'great', 'grand' and 'khan' are the most frequent and reveal a lot more about the text than the previous list had.

(more of the basic features)

### How to do some other thing Voyant can do


### Exporting Data
Voyant can be used to manipulate texts and extract key elements, which can then be exported for use in other programs.  We will go over one example this by looking at how to use the RezoViz feature to create a .net file ready for network analysis in a program like Gephi(link to it).  

To access other features select the save button in the top right corner of the screen, from the list of saving options select the very last one: "a URL for a different tool/skin and current data", this will take you to a drop down selection box with many visualization options. Select "RezoViz". This will bring up a URL, copy and paste it into the navagation bar and that will bring up the tool. 

The tool can take a while to process, and depending on the size of the corpus and your computer's processing power, might not start at all. If it does the visualization should look like a web, with the most common term in the centre. 

The bottom left has options for altering the visualization, where you can limit the number of terms, as well as tension, replusion and friction. 
![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/options.jpg)


After making choices about terms, and correcting any errors in the program's catagorization, you can save your network analysis as a .net file. Clicking the save button in the top right corner and selecting "all data in Pajek (.net) syntax" creates the file which can then be used in Gephi!
![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/fornetfile.jpg)

Gephi enables a greater level of control and options for network analysis, but the program can be tricky. ((((Link gephi in, somebasics about it)))

To get started ((((mention how that sometimes you need to tell the program where it's located or something, I'll find that tomorrow)) simply select new project and under file select open. After finding the .net file, open and you'll see something like this

![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/gephi.jpg)

If instead of a visualization you're shown the message that there isn't enough memory you can follow some simple steps to increase it:
Find Gephi under "Program files (x86)" in your C: drive. In the "etc" folder there should be a file called "gephi.conf", open this in a text editor like Sublime Text, or Atom, and find the line "Xmx". replace the number following that with 5708, making sure the m follows directely after. Save the file and restart Gephi, it should work now. (For other ways of changing this, and more instructions [click here](https://gephi.org/users/install/#memory)
![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/editingin.jpg)


(Note to self: include a strong warning about how it might make your computer freeze/unresponsive/bad/blink in a way that isn't good for epileptics)

(I'll write this whole long part Thursday-ish)


### Conclusion and Thoughts on Voyant's disparate and powerful uses


This is obviously a mess but it has some framework and all the potential!
