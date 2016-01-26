#Analyzing Text Analysis

There are some limitations to text analysis that become obvious before you even start to use the programs themselves because of restrictions on text formats. For example, you can't analyse images within a text like those in Rockwell's article. Further, because text analysis often relies on isolating word patterns, elements of a text like tone or irony don't tend to register in either corpus analysis or topic modeling. Despite these drawbacks, however, there is much to be said for taking a different look at a group of texts. 

 By allowing the reader to shift their perspective, AntConc and topic modeling open the door to forming new insights into texts. They can be great tools when used in conjunction with more critical modes of analysis. Though it may be all too easy to use what Tressie McMillan Cottom calls, "quantitative textual analysis that is very popular with powerful actors precisely because it does not theorize power relations," these tools can greatly assist one's research methods so long as said researcher engages critically with them.

 I've decided to use DIGH5000's January 12th readings on text analysis as my corpus in order to venture a commentary on the texts addressing text analysis itself. 

##AntConc

In an article titled, "Algorithmic Culture" Ted Striphas traces the conditions of emergence for what he sees as a shift in the way we now conceive of culture. To do so, he analyzes keywords that have a particularly strong connection to the meaning of the word culture and by tracking the shifting signification of these keywords, he grapples with the shift in our understanding of culture in the age of computers. Though his approach is focused on etymology and evolving word usage, his identification of keywords is integral to programs like AntConc, which conducts text analysis based on the user's word searches.

The task of selecting which words to search for is the first hurdle. Of course you can simply select words and run them through at random, but in order to conduct a meaningful critique, some thought should go into the word selections. I decided to use the keywords outlined in Striphas' article as a kind of first step toward exploring DIGH5000's January 12th class on text analysis and how it might relate to current and shifting conceptions of culture. 

Striphas identifies these words as some of the "keywords today": **algorithm 3, analog 3, application 4, cloud 1, code 1, control 3, convergence, copy 2, crowd, data 5, design 2, digital 5, format, free 1, friend, game 2, graph, hack, human 5, identity 1, information 3, machine 2, message, mobile 1, network 2, noise, peer 2, platform 1, protocol, search 4, security, server 1, share 3, social 4, status, web 3**

The numbers beside each word represent the the number of texts (out of six) that the words appeared in. After running all these keywords through the Concordance Plot function, we can see that the words that appear in the most texts (though none appeared in every text) were "application," "data," "digital," "human," "search," and "social."

Interestingly, Lev Manovich's text by far had the highest incidences of most of the keywords that appeared. Of course, his text is also by far the longest of the six texts being examined, so there is a bias according to sheer number of words. 

It remains unclear exactly what kind of conclusions should be drawn from the fact that these words appear in the text. It is tempting to infer that word occurences correlate with the focus of the texts. However, this is entirely too simplistic. The word "web" for instance appears in Clement et al., Rockwell, and Manovich's texts. It does not appear in Jean-Baptiste's text at all even though that article is focused on examining links within the corpus of books hosted on the Internet by Google Books. The word web relates to that article in at least two ways if we consider web as in an interlinking structure, and web as in World Wide Web.

![web](https://github.com/SAllieW/screencaps/blob/master/web.png?raw=true)

This tool does not address negative results except to note that they exist - it cannot address a word that has no outright instances in the text, even if the concerns of the text may be addressing the topic implicitly. For instance, the word "network" does not appear in "How Not to Read a Million Books" by Tanya Clement et al. but one of the primary concerns of the article -- tracing connections and patterns across a vast archive of books -- is clearly about addressing intertextual networks. 

![network](https://github.com/SAllieW/screencaps/blob/master/network.png?raw=true)

However, AntConc does more than note instances of words in these examples - the lines that appear also mark the location within the text that they are written. In the "network" example, we can see that Manovich's three uses of the word are sprinkled here and there, while the four times that Cottom used the word are clustered cheek to jowl in the final third of the article. This suggests that the two writers have handled the topic differently, Cottom perhaps raising the idea in a more focused manner. This kind of visual representation could be a useful flag for a researcher to launch a more sustained inquiry into the treatment of this topic.

When used together, the various tabs in AntConc can produce results that surprise or intrigue you. The Cluster and Collocates tabs allow you to do more than count or visualize instances. You can compare the contexts in which they appear. This is key. When I looked at the Concordance Plots of "network" I was under the assumption that the instances it found were concerned with digital networks, networked computers or perhaps social networks online. Surprisingly, half the cluster tokens are followed by "television" or "tv" and the number five and six collocates are "cable" and "television." 

##Topic Modeling

Unlike AntConc, where I believe a good deal of consideration must precede the use of the tool in order to select meaningful words to search for, Topic Modeling offers a starting point. The topics are a grouping from which to direct a critique of the text using other methods of examination such as close reading, queer reading, historical reading, etc. The strength of topic modeling is its potential for drawing attention to patterns that may not have caught the reader's attention if she were only engaged in more conventional forms of reading.

Interestingly, I ran into some problems running the six articles as separate documents. It created topics but the links within the topics to the texts were broken. This program forces you to treat a corpus as a single text - a handy metaphor for the way that distant reading seems to create such an intertextual approach to a vast body of written works as to fray the edges of the individual works.

Another issue was with how the program handles certain forms of text. It's difficult to say whether the problems below affect the topics that get produced, but it does raise questions concerning what kinds of expressions the program is meant to handle.
![error](https://github.com/SAllieW/screencaps/blob/master/error.png?raw=true)

I ran the combined texts through various configurations of topic numbers, numbers of iterations, and topic proportion thresholds until the topics produced seemed to reflect the ideas in the text.
![chosenTopics](https://github.com/SAllieW/screencaps/blob/master/ChosenTopics.png?raw=true)

Topic 5, for example, seemed to closely reflect the ideas in "Quantitative Analysis of Culture Using Millions of Digitized Books" because 8/10 of the topic words are in the text. When I opened the topic and opened the docs, however, there were actually far fewer examples from the text than expected. Doc 154, for example, was taken from the text but only 3/20 of the docs were from the text.
![OutWithTheOld](https://github.com/SAllieW/screencaps/blob/master/Out%20with%20the%20old.png?raw=true)

These results suggest that this topic represents a significant area of overlap in the six articles. This is the strength of this program - not that we can reach conclusions based on the topics, but that they can serve to point us in a direction for other kinds of analysis.

##Conclusion

In Jodi Dean's book "Blog Theory" she addresses some of essential concerns with text analysis in discussing the limitations of word-clouds: "What's lost? The ability to distinguish between contestatory and hegemonic speech. Irony. Tonality. Normativity - how can there be an ethics of the address if the words are not part of an address, if they are extracted from their position within speech acts to become artifacts and toys? Critique."

AntConc moves through the smokescreen of a word-cloud to provide the user with tools to grapple with words in-context, and topic modeling should be approached in the same way. Registering that a word appears or doesn't is not enough, nor is it enough to simply note which words tend to appear together. These are first steps toward greater projects. I would consider the [project on Agatha Christie's body of works](http://www.theguardian.com/books/2009/apr/03/agatha-christie-alzheimers-research) done at the University of Toronto to be a stellar example of what text analysis can do when used in conjunction with other analytical approaches (in this case: close reading, psychological diagnosis, and computer science methods).  
