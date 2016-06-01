PHP Emoji class
===============
A handy dumb class for using Emojis in your php project. In some IDEs emojis don't show up.
They are 🎉 💩-ers. But their editor is so good.

Now you can use Emojis in your code without your IDE crapping out on you.


Installation
------------
Just use:

`composer require webdevvie/emoji`


Usage:
------
Two ways to use it prepended with C_ or not:

First use Emoji:

`use Webdevvie\Emoji\Emoji;`

now use the emoji class:
`Emoji::FLAG_FOR_NETHERLANDS` to get the Dutch flag 🇳🇱

or if you want to display it in a console command use :
 `Emoji::C_FLAG_FOR_NETHERLANDS` to get the Dutch flag with a space after it so it shows up properly in the console.

or maybe you are more of a Unicorn person 🦄:
`Emoji::UNICORN_FACE`


This is nothing special. Just a simple helper class.
There are no tests, there are no methods.

CHEATSHEET
==========
Want a cheatsheet
[Go here](CHEATSHEET.md)


Acknowledgement
===============
All information for this class was taken from
[Unicode.org](http://unicode.org/emoji/charts/full-emoji-list.html)

Also
====
If you like this library. Find me on twitter [@webdevvie](http://twitter.com/webdevvie) or my personal site [johnbakker.name](http://johnbakker.name) and throw me a 👍 😀
