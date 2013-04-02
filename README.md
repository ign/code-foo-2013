IGN's Code-Foo 2013
=============

For more information on IGN's Code-Foo 2013, visit [code.ign.com/foo] (http://code.ign.com/foo).

To apply to Code-Foo 2013, fork this repository and answer all questions including either the back-end or front-end section. Push your answers to your fork and send us an email at code-foo@ign.com to let us konw you're finished.

All answers must be completed using Java, Scala, PHP, Ruby, or Javascript. Application must be turned in by _Friday, April 26th at 5pm PST_.

1. Create a 2-5 minute video introducing yourself and showing your passion for IGN and the Code-Foo program.
2. How many gamers are in the San Francisco Bay Area? Describe each step in your thought process.
3. Write a program to find the given words from the included word search. Both word search and words can be found at [word-search.txt] (https://github.com/ign/code-foo-2013/blob/master/word-search.txt)

Back-end
--------

4. Write a program that searches a family tree for members that match name and/or generation. How does this algorithm scale?
5. Write a sorting algorithm that can sort _n_ number of high scores (`float` Score, `string` Name) by score. What algorithm did you use? How does this algorithm scale? Can you reduce time and space complexity?
6. Given two three-letter words, write a program that will determine the amount of "moves" it takes to change one word to the other. A "move" is considered changing a single letter of the given word while still keeping it a valid three-letter word. 
_Note: A full list of three-letter words is provided in this repository as [three-letter-words.txt] (https://github.com/ign/code-foo-2013/blob/master/three-letter-words.txt)._

```
EXAMPLE:
How many moves does it take to change 'dog' to 'cat'?
dog -> cog -> cot -> cat. 3 moves
```

Front-end
---------

4. Create a responsive layout using media queries. Must support iPad, iPhone, and common resolutions for desktops. Nest your entire application in this responsive interface.
5. Using the Twitter API, pull and display the last 40 tweets from the 'ign' account. Use [dev.twitter.com] (https://dev.twitter.com) for reference.
6. Using the results from the previous question, determine the most commonly used words. What is the scalability of this algorithm? Would this algorithm still work if you were parsing billions of tweets.

Bonus Question
--------------
Create a game similar to Space Invaders. There are no language restrictions.
