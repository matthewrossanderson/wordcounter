This was a recruiting exercise to test my general knowledge of programming concepts in Javascript.

I completed it in about an hour, it was a fun task to undertake.

The challenge instructions are below:



Your task is to print a list of all the words used in an arbitrary sample of text. For each word you must also provide the number of times that word appears. 


Consider the following text from J.D. Salinger’s The Catcher in the Rye:

"Anyway, I keep picturing all these little kids playing some game in this big field of rye and all. Thousands of little kids, and nobody's around - nobody big, I mean - except me. And I'm standing on the edge of some crazy cliff. What I have to do, I have to catch everybody if they start to go over the cliff - I mean if they're running and they don't look where they're going I have to come out from somewhere and catch them. That's all I do all day. I'd just be the catcher in the rye and all. I know it's crazy, but that's the only thing I'd really like to be. "


The challenge is parse this text and print out each word followed by the number of times it appears in the passage, like this sample:
anyway=1 i=8 keep=1 picturing=1 all=5 these=1 little=2 kids=2 playing=1 some=1 game=1 in=2 this=1 big=2 field=1 of=3 rye=2 and=6 ...



The Rules

We request that you not to use any third party code for the purposes of this test. Please return one HTML file with Javascript code inline.

This isn't a grammar test. You may ignore abbreviations, hyphenation, and most other punctuation.

The only punctuation that you do need to be concerned about is the single quote. Contractions should be seen as single words: "can't" should stay "can't" not "can" and "t". By the same token possessives should be maintained: "Jack's" should be counted separately than "Jack".

The tally should be case insensitive. "Hello" and "hello" are the same word.

The output data must consist of each word and the number of instances for each word.

Be prepared to explain your approach.