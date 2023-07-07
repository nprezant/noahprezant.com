+++
title = "dotfiles"
date = 2022-10-01T14:39:14-06:00
draft = true
+++

.dotfiles
=========

Here we describe a journey with dotfiles

.. code-block:: console

    curl -Lks <site>
    # a bit of code to get us started

If I may, I will say a lot of words. It is unclear exactly how many.
Once there was a boy who lived by a creek. The creek was cold, often refreshingly so
in the summer. In the winter it made your toes feel like icicles.

Inline markup
-------------

We have *emphasis*, **strong emphasis**, and ``code samples``

Can also view in a list format:

- there is *emphasis*
- there is **strong emphasis**
- and also ``code samples``

Lists and Quote-Like Blocks
---------------------------

Lists can be marked with dashes or asterisks.

- dash
- dash
- dash

* asterisk
* asterisk
* asterisk

Numbered lists can be numbered manually...

1. this list
2. is manually
3. numbered

or autonumbered.

#. auto number
#. auto number
#. auto number

term (up to a line of text)
   Definition of the term, which must be indented

   and can even consist of multiple paragraphs

next term
   Description.

another term
   A long paragraph description of the term can span
   multiple lines in the source code. To make a new paragraph,
   a blank line must be left.

   So this is a middle paragraph.

   And a final paragraph.

Line blocks can preserve line breaks

| These lines are
| broken exactly like in
| the source file.

Hyperlinks
==========

This is a paragraph that contains `a link`_.

.. _a link: https://domain.invalid/

This paragraph contains an `internal link`_.

.. _internal link: {{< ref "catio" >}}

Admonitions
===========

Admonitions may be a nice alternative to footnotes.

.. note:: This is a note admonition.
   This is the second line of the first paragraph.

   - The note contains all indented body elements
     following.
   - It includes this bullet list.

.. tip:: This is a tip admonition.
   ta da.

Footnotes
=========

Autonumbered footnotes are
possible, like using [#]_ and [#]_.

.. [#] This is the first one.
.. [#] This is the second one.

They may be assigned 'autonumber
labels' - for instance,
[#fourth]_ and [#third]_.


This may be a good way to handle wait
but why's interesting footnotes.

.. [#third] a.k.a. third_

.. [#fourth] a.k.a. fourth_ 

Footnotes can be autonumbered with abitrary labels,
like for example if I needed a footnote about the roman
empire [#romans]_.

.. [#romans] is about romans and
   can be linked back to with romans_

Citations
=========

Citation references, like [CIT2002]_.
Note that citations may get
rearranged, e.g., to the bottom of
the "page".

This may be a good way
to handle wait but why's boring footnotes.

.. [CIT2002] A citation
   (as often used in journals).

Citation labels contain alphanumerics,
underlines, hyphens and fullstops.
Case is not significant.

Given a citation like [this]_, one
can also refer to it like this_.

.. [this] here. 
