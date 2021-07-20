First I created a text box area that would display the text file whenever the user input their text file. This part I coded in the Index.cshtml file, and all I had to do was 
set the size of the "box" and I got the box size that I want. I then created another box for the result and basically when i get the incorrect words, just display them in that box.

Then I created 2 buttons. One is "Check" and one is a Choose File button. Both created in the site.js file. 

I first code the Choose File button as it seems pretty straight forward and took me about 30 mins to do that buttons. 
Using 2 functions, one to check whether the file uploaded is a .txt file or not. I tried to include .docx file, but whenever displaying the file 
on the text box area, it gives me weird symbols so I skipped that for now and just do text file (.txt). 

Then I added the entire dictionary from my words.txt files with 85625 words into an array. After that is just a process of figuring out how the compare the 
words in the user's text file to the dictionary's. Took me about 3 hrs to do that. I still having trouble figuring out how to split the words when it comes like this:

"equal.now" ... Techinically it is not a word, but we know that those are two words connected by a period, which I can just use some kind of a find function to locate the period
and set the first word from the beginning to the index of the period, and the second word from the next index of the period to the last index of the total word. But I couldn't make it work :(.

Fun project!!!

Huy