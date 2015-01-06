# Bacon-Ipsum Component

Bacon Ipsum is a small component built in polymer that aims to help with managing placeholder text in your templates during your development workflow. After installing the component you have access to the custom tag which generates your placeholder text. There are a few bonuses to using this method:

 - Use one tag to generate any placeholder paragraphs you need
 - Dont need to copy/paste anything
 - Takes up a lot less room than a wall of text in your markup, its only 1 tag
 - Different Content every time
 - Bacon goodness

### Version
>0.0.1

Initial version: Supplies you with the bacon-ipsum tag to generate meaty placeholder text using the bacon-ipsum json api. Also allows for a 'paragraphs' attribute to customise the length of the content.

### Installation

First install the component using Bower:
```sh
$ bower install bacon-ipsum-component
```

Then include the html import into your header:

```sh
<link rel="import" href="/path/to/bower_components/bacon-ipsum/bacon-ipsum.html">
```

###Example Code

```sh
// Standard usage: defaults to 2 paragraphs
<bacon-ipsum></bacon-ipsum>

// Control how many paragraphs you want
<bacon-ipsum paragraphs="5"></bacon-ipsum>
```

### Todo's

 - Write Tests
 - Write better documentation
 - Add sentance, word and character support


License
----

MIT


**Free Software, Hell Yeah!**
