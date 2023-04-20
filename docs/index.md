# Overview

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

``` mermaid
graph LR
  A[Start] --> B{Error?};
  B -->|Yes| C[Hmm...];
  C --> D[Debug];
  D --> B;
  B ---->|No| E[Yay!];
```


## Chapter 3


Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut pellentesque leo erat, sit amet pulvinar dui volutpat vitae. Nulla mollis ante sed sem condimentum rhoncus et sed lacus. Donec consectetur fringilla lectus, nec dignissim risus ultrices eleifend. Suspendisse potenti. Morbi pretium, tortor vitae iaculis iaculis, nisi orci suscipit justo, quis consequat quam libero eu velit. Fusce nec libero a justo tristique pellentesque. Proin porta lectus sit amet dolor condimentum, ut finibus lacus tristique. Phasellus mollis volutpat augue quis facilisis.

In faucibus felis nulla, sed luctus purus condimentum sodales. Pellentesque eget facilisis justo. Morbi elementum porttitor erat sed tincidunt. Phasellus nec sodales ante. Nullam ornare lectus non sem ullamcorper vulputate eget at nulla. In accumsan ut velit at consectetur. In dictum mauris ac lectus auctor bibendum. Nunc vitae arcu a augue ornare dignissim. Donec viverra erat at scelerisque bibendum. Sed convallis ante tellus, id ullamcorper ex aliquam sed. Morbi sagittis faucibus velit ac congue. Donec bibendum dictum dictum. Lorem ipsum dolor sit amet, consectetur adipiscing elit.

Aliquam erat volutpat. In vitae malesuada ipsum. Fusce sit amet tellus a nunc efficitur elementum eget vitae est. Donec scelerisque nulla nisi, non ullamcorper est hendrerit ut. Duis porttitor aliquet sapien eu aliquet. Donec viverra, sem eget laoreet hendrerit, massa dolor ultrices magna, molestie ullamcorper tellus eros fringilla enim. Integer velit ex, lobortis et accumsan id, molestie vel velit. In aliquet eros a rhoncus finibus. Aliquam erat volutpat. Quisque ac sodales leo. Nullam malesuada ipsum eu velit consequat, fermentum congue erat pellentesque. In neque odio, tempor in ante nec, placerat elementum odio. Mauris tempor est eu pulvinar mattis. Mauris porta feugiat placerat. Etiam in ornare metus, eget ullamcorper tortor.

Cras vel lobortis enim, sed tempus ipsum. Curabitur placerat aliquet augue vitae bibendum. Aliquam laoreet id orci non ornare. Aliquam finibus tellus in eros molestie, a porta eros eleifend. In varius, ipsum vel aliquet elementum, orci lorem euismod diam, volutpat euismod ligula eros in mauris. Phasellus sit amet semper tellus, vitae porttitor mi. Quisque turpis dui, sollicitudin vitae rutrum a, sollicitudin ut ex. In id interdum ligula. Morbi consequat, nunc a rutrum mattis, metus magna tempor mauris, vitae malesuada diam nunc sed augue. Fusce id diam massa. Nam sollicitudin quam a vulputate consectetur. Morbi velit ligula, fringilla non porta a, placerat quis libero. Ut et venenatis justo. Cras vestibulum metus nec risus suscipit placerat. Sed porta diam vel pulvinar scelerisque. Sed sit amet dolor in nulla scelerisque pretium.

Morbi non dui turpis. Morbi malesuada nisi in massa congue, et posuere dolor blandit. Pellentesque euismod fermentum massa id semper. Morbi blandit risus vitae enim pulvinar blandit. Fusce sit amet lobortis turpis. Nunc in rhoncus justo. Quisque facilisis, felis non bibendum euismod, magna erat posuere nulla, quis bibendum enim augue in quam.





## Commands 4
Lorem ipsum dolo


Text can be {--deleted--} and replacement text {++added++}. This can also be
combined into {~~one~>a single~~} operation. {==Highlighting==} is also
possible {>>and comments can be added inline<<}.

{==

Formatting can also be applied to blocks by putting the opening and closing
tags on separate lines and adding new lines between the tags and the content.

==}


Sub- and superscripts¶

When Caret & Tilde are enabled, text can be sub- and superscripted with a simple syntax, which is more convenient than directly using the corresponding sub and sup HTML tags:
Text with sub- and superscripts

- H~2~O
- A^T^A


Footnotes
--------
Adding footnote references¶

A footnote reference must be enclosed in square brackets and must start with a caret ^, directly followed by an arbitrary identifier, which is similar to the standard Markdown link syntax.

Lorem ipsum[^1] dolor sit amet, consectetur adipiscing elit.[^2]

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut pellentesque leo erat, sit amet pulvinar dui volutpat vitae. Nulla mollis ante sed sem condimentum rhoncus et sed lacus. Donec consectetur fringilla lectus, nec dignissim risus ultrices eleifend. Suspendisse potenti. Morbi pretium, tortor vitae iaculis iaculis, nisi orci suscipit justo, quis consequat quam libero eu velit. Fusce nec libero a justo tristique pellentesque. Proin porta lectus sit amet dolor condimentum, ut finibus lacus tristique. Phasellus mollis volutpat augue quis facilisis.

In faucibus felis nulla, sed luctus purus condimentum sodales. Pellentesque eget facilisis justo. Morbi elementum porttitor erat sed tincidunt. Phasellus nec sodales ante. Nullam ornare lectus non sem ullamcorper vulputate eget at nulla. In accumsan ut velit at consectetur. In dictum mauris ac lectus auctor bibendum. Nunc vitae arcu a augue ornare dignissim. Donec viverra erat at scelerisque bibendum. Sed convallis ante tellus, id ullamcorper ex aliquam sed. Morbi sagittis faucibus velit ac congue. Donec bibendum dictum dictum. Lorem ipsum dolor sit amet, consectetur adipiscing elit.

Aliquam erat volutpat. In vitae malesuada ipsum. Fusce sit amet tellus a nunc efficitur elementum eget vitae est. Donec scelerisque nulla nisi, non ullamcorper est hendrerit ut. Duis porttitor aliquet sapien eu aliquet. Donec viverra, sem eget laoreet hendrerit, massa dolor ultrices magna, molestie ullamcorper tellus eros fringilla enim. Integer velit ex, lobortis et accumsan id, molestie vel velit. In aliquet eros a rhoncus finibus. Aliquam erat volutpat. Quisque ac sodales leo. Nullam malesuada ipsum eu velit consequat, fermentum congue erat pellentesque. In neque odio, tempor in ante nec, placerat elementum odio. Mauris tempor est eu pulvinar mattis. Mauris porta feugiat placerat. Etiam in ornare metus, eget ullamcorper tortor.

Cras vel lobortis enim, sed tempus ipsum. Curabitur placerat aliquet augue vitae bibendum. Aliquam laoreet id orci non ornare. Aliquam finibus tellus in eros molestie, a porta eros eleifend. In varius, ipsum vel aliquet elementum, orci lorem euismod diam, volutpat euismod ligula eros in mauris. Phasellus sit amet semper tellus, vitae porttitor mi. Quisque turpis dui, sollicitudin vitae rutrum a, sollicitudin ut ex. In id interdum ligula. Morbi consequat, nunc a rutrum mattis, metus magna tempor mauris, vitae malesuada diam nunc sed augue. Fusce id diam massa. Nam sollicitudin quam a vulputate consectetur. Morbi velit ligula, fringilla non porta a, placerat quis libero. Ut et venenatis justo. Cras vestibulum metus nec risus suscipit placerat. Sed porta diam vel pulvinar scelerisque. Sed sit amet dolor in nulla scelerisque pretium.


Adding footnote content¶

The footnote content must be declared with the same identifier as the reference. It can be inserted at an arbitrary position in the document and is always rendered at the bottom of the page. Furthermore, a backlink to the footnote reference is automatically added.
on a single line¶

Short footnotes can be written on the same line:


[^1]: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
[^2]: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
