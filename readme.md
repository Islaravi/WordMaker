WordMaker

 A program that generates made-up words based on a provided list of actual words. It uses Markov chains to learn which letters are commonly used together, and then it generates new words based on these patterns. By learning from different word lists, the words that it generates can be very different! 

You can view multiple demos here:

* [Islaravi Words](https://islaravi.github.io/WordMaker/islaravi.html)
* [English Words](https://islaravi.github.io/WordMaker/english.html)
* [Elements](https://islaravi.github.io/WordMaker/elements.html)
* [Latin Words](https://islaravi.github.io/WordMaker/latin.html)
* [Popular Male Names](https://islaravi.github.io/WordMaker/male_names.html)
* [Popular Female Names](https://islaravi.github.io/WordMaker/female_names.html)
* [Advanced Options](https://islaravi.github.io/WordMaker/advanced.html)



This project is built using the following:
* Bootstrap 4 alpha for the responsive design and pretty components
* jQuery to read the input fields and make the buttons do stuff
* Plain JavaScript to do the actual word-making, nothing special about it

THIS IS TOTALLY PLAGARIZED FROM Joe Di Febo 
https://jdifebo.github.io/WordMaker/english.html
I JUST CO-OPTED IT TO A CONLANG. ALL CREDIT GOES TO JOE.

In the source code, the file ```js/wordmaker.js``` has all of the code to actually make words.  The other files are just for attaching event listeners to the DOM and DOM manipulation.  You
can find all of the datasets in ```resources/```.
