# World-Cloud-Google-FinalProject
***
![Google Logo](https://d3njjcbhbojbot.cloudfront.net/api/utilities/v1/imageproxy/http://coursera-university-assets.s3.amazonaws.com/b6/a7ddd772194a22b3e8e8cb27d29702/500x500_Google.png?auto=format%2Ccompress&dpr=1&w=56px&h=56px&auto=format%2Ccompress&dpr=2&w=&h=)
- This is a final project at __[Crash Course on Python by Google](https://www.coursera.org/learn/python-crash-course/home/welcome "https://www.coursera.org/learn/python-crash-course/home/welcome")__
***
## Description :
    For the input file, you need to provide a file that contains text only. For the text itself, 
    you can copy and paste the contents of a website you like. Or you 
    can use a site like Project Gutenberg to find books that are available online. 
    You could see what word clouds you can get from famous books, like a Shakespeare 
    play or a novel by Jane Austen.
    Things to remember 

    Before processing any text, you need to remove all the punctuation marks. To do this, you can go through each line of text, character-by-character, using the isalpha() method. This will check whether or not the character is a letter.
    ->To split a line of text into words, you can use the split() method.
    ->Before storing words in the frequency dictionary, check if they’re part of the "uninteresting" set of words (for example: "a", "the", "to", "if"). Make this set a parameter to your function so that you can change it if necessary.
**After Creating A Dictionary Of Most Relevant Words (Of Cousre Acc. to Their Frequency) Pass It To Following Code**
``` python
cloud = wordcloud.WordCloud()
cloud.generate_from_frequencies(<nameOfYourDictionary>)
cloud.to_file("myfile.jpg")
```

**Remark :** _All the modules which are essential for the project are already available in Course Lab_
