Something about me
----

Nothing

[Subscribe to our newsletter](#){ .md-button }

[Send :fontawesome-solid-paper-plane:](#){ .md-button }


Usage¶
Highlighting changes¶

When Critic is enabled, Critic Markup can be used, which adds the ability to highlight suggested changes, as well as add inline comments to a document:
Text with suggested changes

Text can be {--deleted--} and replacement text {++added++}. This can also be
combined into {~~one~>a single~~} operation. {==Highlighting==} is also
possible {>>and comments can be added inline<<}.

Text can be {--deleted--} and replacement text {++added++}. This can also be
combined into {~~one~>a single~~} operation. {==Highlighting==} is also
possible {>>and comments can be added inline<<}.

{==

Formatting can also be applied to blocks by putting the opening and closing
tags on separate lines and adding new lines between the tags and the content.

==}

Highlighting text¶

When Caret, Mark & Tilde are enabled, text can be highlighted with a simple syntax, which is more convenient that directly using the corresponding mark, ins and del HTML tags:
Text with highlighting

- ==This was marked==
- ^^This was inserted^^
- ~~This was deleted~~

  This was marked
  This was inserted
  This was deleted

Sub- and superscripts¶

When Caret & Tilde are enabled, text can be sub- and superscripted with a simple syntax, which is more convenient than directly using the corresponding sub and sup HTML tags:
Text with sub- and superscripts

- H~2~O
- A^T^A

  H2O
  ATA

Adding keyboard keys¶

When Keys is enabled, keyboard keys can be rendered with a simple syntax. Consult the Python Markdown Extensions documentation to learn about all available shortcodes:
Keyboard keys

++ctrl+alt+del++

Ctrl+Alt+Del
