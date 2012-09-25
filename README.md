Start typing in the blue box...

**Hi, this is a great day**,*isn't it*  

aa

<div>
This is a div&
</div>

a&amp;

This is H1
==========
This is H2
---------

#Or, this is also H1

##And this is H2

###Try the silimar things by appending different numbers of \#(s)

>Block quoting
>Looks great

>is't it

>>and it can be nested

>>> haha, interesting

>>>> Ouch, I hit my head, don't push me

> And within block quote, other markdown usage are applicable

>##Let me show you how

>1. One 

>2. Two

>3. Three

##And with different indentation
>1.Zero indent

>2. One indent

>3. One indent(##Nested, see?##)

>3.  Two indent (failed..)

> #Go!!
>return shell_exec("echo $input | $markdown_script");

>return func("asdadqwe");

# Ordered and unordered list
* Hey
* Hey
* You
* You
+ I
+ can
+ be
+ your
- girlfriend!

## This seems wierd but it true
1. One 
5. Five
4. Four

##List with multiple paragraphs
1. Lorem ipsum dolor
   
   sit amet, consectetuer adipiscing elit. Aliquam hendrerit

   mi posuere lectus.

2. Lorem asdqwe....
3. with block quote

>Block quote content

>I seem to be lazy, am I?
4. Put code here(with 2 tabs or 8 spaces)

        Code,blah,blah
        print "Woo,cool".

It is easy to trigger a list like this:

1990. I was born in that year

You need to escape the **period**

1990\. I was born in that year.

#Code block

    import nltk
    print "Ouch"
    
    print "<div>My parent it not processed!</div>"
    print "'Me too!', said &copy;"

the 4 spaces are removed from the code block

And regular markdowns are not processed in code block

#Horizontal rules

    ***
turns into:


***

    -----------
turns into:

------------

#Span elements

span elements are wrapped by `[]`
##Inline link

###Link with titles
[Google](http://google.com "Google")

###Link without titles
[Google](http://google.com)

(hover on the link to see the difference)

For local resources

[Local](/local/)


##Reference link

This reference link points to [philosophy][id_philosophy]

[id_philosophy]: http://philosophy.com 'Philosophy'(hehe, bug)

[id_philosophy]: http://philosophy.com "Philosophy"

This is cool

>I get 10 times more traffic from [Google] [1] than from
>[Yahoo] [2] or [MSN] [3].

  [1]: http://google.com/        "Google"
  [2]: http://search.yahoo.com/  "Yahoo Search"
  [3]: http://search.msn.com/    "MSN Search"

>I get 10 times more traffic from [Google] [] than from
>[Yahoo] [] or [MSN].

  [Google]: http://google.com/        "Google"
  [Yahoo]: http://search.yahoo.com/  "Yahoo Search"
  [MSN]: http://search.msn.com/    "MSN Search"

#Emphisis
*single asterisk*

_sindle underline score_

**double asterisks**

__double underline scores__

Emphasis can be used **within** words

Like this Ya**hoo**

This is a literal asterisk: **\***

#Code
Python:
>`print "Great article"`

C
>`printf("Great article");`

PHP
>`echo "Great article";`

>``This mark, " ` ", is called backtick``

`` ` ``

This is not a stain on the screen

`&#8212;` is the decimal-encoded equivalent of `&mdash;`.

##Direct url style
Here is a image:

![Food1] (https://lh4.googleusercontent.com/1spUpgEUnAyL0MeozGYib3ty7loPztFzlslHGsvvs1htm2ZIPFoZmVzjqBqFbfMh5c_WWdsesAI "Food") 


##Reference style
![Food][]

[Food]: https://lh3.googleusercontent.com/eVIv2DtJaEvKmLyACNpR-YztbUgrEshA_D2C_9KCSyKEASPgxo85Olkvc0hnTCUhqmN8_tPnRII "Food"

#Miscellaneous

##Direct link
<https://google.com>

<address@example.com>

#Thans for this great [post](http://daringfireball.net/projects/markdown/license) from [Daring Fireball](http://daringfireball.net)
