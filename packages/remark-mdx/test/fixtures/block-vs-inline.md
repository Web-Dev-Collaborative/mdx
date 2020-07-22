# Block vs. inline

To make this example more readable, uppercase letters are used when JSX is
parsed as a block, wheres lowercase letters are used for inline JSX.

This is inline, it’s a paragraph, because `</x>` is followed by `.`.

<x>_alpha<y/>_</x>.

This is a block, thus its contents is also a block, resulting in a heading: it
doesn’t matter that there are no enters.

<X># heading</X>

Here we also have a block.
And an inline.

<X># heading <y>inline</y></X>

This isn’t very readable, but it is a block, with two paragraphs:

<X>One paragraph.

Two paragraph.</X>

Blocks can be self-closing:

<X/>