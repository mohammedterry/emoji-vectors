# emoji-vectors
Using keywords used to tag emojis on the internet (i.e. from emojipedia)
as well as other sites (i.e. sentiment values for emojis, sexual connotations for emojis, etc)
and then adding commonly colloquated words into the mix (i.e. using a twitter dataset)
i managed to create vectors to represent each emoji 

![](https://raw.githubusercontent.com/mohammedterry/emoji-vectors/master/a.png)
![](https://raw.githubusercontent.com/mohammedterry/emoji-vectors/master/b.png)

The method of converting keyword categories into vectors is both simple and effective! i did it to create word vectors too and if i use the same categories for both the emojis and words - i can essentially embed the emojis into the same hyperspace as the wordvectors!  Thus emojis are related to words too.  

I used this to create an emojify() function that converts any word into its closest emojis
![](https://raw.githubusercontent.com/mohammedterry/emoji-vectors/master/emojify.png)

I can also use the emoji vectors to create a fun game - guess the odd one out!
![](https://raw.githubusercontent.com/mohammedterry/emoji-vectors/master/c.png)
![](https://raw.githubusercontent.com/mohammedterry/emoji-vectors/master/d.png)
![](https://raw.githubusercontent.com/mohammedterry/emoji-vectors/master/e.png)
![](https://raw.githubusercontent.com/mohammedterry/emoji-vectors/master/f.png)

