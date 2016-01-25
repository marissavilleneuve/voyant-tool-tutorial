# Voyant: A text-analysis tool

Voyant is a powerful tool that can be used for analyzing text.  In this tutorial we will look at Voyant: what it is, details on how to use a few of its many features, and why it can be useful for humanities research.  

[Voyant](http://voyant-tools.org) runs online so it is not necessary to download any software.  To begin, you can either upload one or more text files or paste in a text or link, then click 'reveal'.  For this tutorial, we will be looking at [The Travels of Marco Polo](https://archive.org/stream/marcopolo00polouoft/marcopolo00polouoft_djvu.txt).

### Understanding and Using Voyant's Interface
Once Voyant has 'revealed' your chosen text, it will look something like this:
![interface](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202016-01-19%20at%207.19.55%20PM.png)

The text will be on the right while the left has a word cloud and statistics for the most frequent words within the text.  For our text, the words 'of', 'the', 'and' and 'in' were the most frequent.  Those words do not elucidate much about the text.  A good first step after inputting a corpus into Voyant is to clean it up a little.

To start, hit the cog in the left-hand corner next to 'Cirrus' to get the search options.  Here, you can edit the 'stop-words', the words which will not be taken into consideration in the text analysis.  You can manually put in words as well as choose from preexisting lists, depending on the language.  For English, the Taporware list exists.  Click the box 'Apply Stop Words Globally' and then click ok.  

![stop words](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202016-01-19%20at%207.34.38%20PM.png)
A new word cloud should appear.  Now for our text, the words 'city', 'country', 'great', 'grand' and 'khan' are the most frequent and reveal a lot more about the text than the previous list had.

(more of the basic features)



### Using Different Tools within Voyant
Voyant can be used to manipulate texts and extract key elements, which can then be analyzed or exported for use in other programs.  We will go over a few differents tools Voyant contains.  Depending on the strengths of your computer, many of these will fail.  A second shot will sometimes work but some may be simply beyond your computer's abilities.  As long as you don't mind possibly breaking your browser and needing to restart it, it never hurts to try though.  Some of the tools will flicker intensely if they do not load up correctly, so it is suggested you not use Voyant if you have epilepsy.    

To access other tools select the save button in the top right corner of the screen. From the list of saving options select the very last one: "a URL for a different tool/skin and current data", this will take you to a drop down selection box with many visualization options. Selecting one will bring up a URL. Copy and paste it into the navagation bar and that will bring up the tool. 

#### RezoViz

RezoViz allows for insight into different connections between elements (like people or places) within a text.  It can also be used to export that information to a .net file ready for network analysis in a program like [Gephi](https://gephi.org).  The tool can take a while to process, and depending on the size of the corpus and your computer's processing power, might not start at all. If it does the visualization should look like a web, with the most common term in the centre. 

The bottom left has options for altering the visualization, where you can limit the number of terms, as well as tension, replusion and friction. 
![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/options.jpg)

<<<<<<< Updated upstream

After making choices about terms, and correcting any errors in the program's catagorization, you can save your network analysis as a .net file. Clicking the save button in the top right corner and selecting "all data in Pajek (.net) syntax" creates the file which can then be used in Gephi!

![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/fornetfile.jpg)

Gephi enables a greater level of control and options for network analysis, but the program can be tricky. ((((Link gephi in, somebasics about it)))

To get started ((((mention how that sometimes you need to tell the program where it's located or something, I'll find that tomorrow)) simply select new project and under file select open. After finding the .net file, open and you'll see something like this

![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/gephi.jpg)

If instead of a visualization you're shown the message that there isn't enough memory you can follow some simple steps to increase it:
Find Gephi under "Program files (x86)" in your C: drive. In the "etc" folder there should be a file called "gephi.conf", open this in a text editor like Sublime Text, or Atom, and find the line "Xmx". replace the number following that with 5708, making sure the m follows directely after. Save the file and restart Gephi, it should work now. (For other ways of changing this, and more instructions [click here](https://gephi.org/users/install/#memory)
![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/editingin.jpg)

=======
>>>>>>> Stashed changes


####Knots
If you ever wanted to see how the use of different words within a text compare in the style of childrens' drawings, Knots it the tool for you!  When it is run, it will start a line visulization of the word through the text.  
![knots 1](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202016-01-24%20at%207.53.02%20PM.png)

If you click on a point along the line, it will open up the sentence with that particular use of the word.  More words can be added using the search bar in the top-left corner.  Once another word is selected, the tool will reload and the visualization will start over with both words, each colour-coded.
![knots 2](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202016-01-24%20at%208.07.26%20PM.png)

You have the ability to control the build speed, starting angle, and tangles at the top, in order to make the visualization more legible.  Short lines indicate little space between uses of the word while longer lines indicate large gaps.  It is possible with this tool to hone in on parts of the text where a word is used more frequently, or see if certain words appear together frequently by comparing the lines.  


####Word Trends

As the name implies, word trends shows the terms as a graph with frequency over the document. Since it's displayed as a simple line graph, the information is easy to extract. For a general view into the text you can limit the number of segments shown. Alternatively, for a more detailed view into the frequency through parts of the text you can increase the number of segments. 

![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/w2w.jpg)

![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/thjegrave.jpg)

You can also collapse the terms so you're left with just one line.

![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/rrrr.jpg)


For more information you can hover above the lines and the exact number of times a term or terms were used in the segment will appear!


####Bubblelines

Bubblelines is quite similar to Word Trends, but a lot prettier! Here instead of a boring old line graph, we're presenting with cute little bubbles representing terms over the duration of the text. Again, hovering above the graph will reveal the number of times a term, or terms have come up in the segment, and you can alter the detail by changing the granularity at the top.

 ![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/rretrer.jpg)
 
 Like Word Trends you can collaspe the graph to just one line, but the bubbles retain their colour so the terms are still distinct. 
 
 ![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/rrere.jpg)



### Conclusion and Thoughts on Voyant's disparate and powerful uses
Using Voyant effectively requires patience and a decent computer, but if you are willing to try it can help reveal some interesting aspects of the text not otherwise evident.  something something something


### Links

+ [Voyant's Documentation](http://docs.voyant-tools.org/): Provides a quick walkthrough for using Voyant and descriptions of all the tools it contains.
+ Gephi
+ Gephi Tutorial
