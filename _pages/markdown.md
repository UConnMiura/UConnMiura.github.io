---
permalink: /markdown/
title: "Markdown"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---
## People

### Pedro Miura, PhD (PI)
* Associate Professor, UConn Health, Dept. of Genetics and Genome Sciences (2022- )
* Associate Professor, UNR, Dept. Biology (2014-2022)
* Assistant Professor, UNR, Dept. Biology (2014-2020)
* Postdoc, Memorial Sloan-Kettering Cancer Center, (2010-2014)
* PhD University of Ottawa (2010)
* BSc Queen’s University (2002)

### Zhiping Zhang, PhD
* Assistant Professor in Residence, UConn Health (2022- )
* Research Assistant Professor, UNR (2020 - 2022)
* Postdoctoral Researcher, UNR (2016 - 2020)
* PhD, IBP, Chinese Academy of Sciences

### Heather Glatt-Deeley, BA
* Research Assistant III, Miura lab (2023- )
* Research Assistant, Pinter lab (2017 - 2023)
* BA in Molecular Biology and Biology, Clark University

## Lab Alumni

### Former Grad Students and Postdocs
* Dr. Bong Min Bae
  * UNR Molecular Biosciences PhD (2016-2021)
  * currently postdoc at Whipple Lab (Harvard).
* Dr. David Knupp
  * Molecular Biosciences PhD (2016-2021)
  * currently Scientist at Invitae (Boulder, Colorado).
* Winston Cuddleston
  * UNR Molecular Biosciences MSc (2018-2020)
  * currently PhD student at Icahn School of Medicine at Mt. Sinai 
* Dr. Hannah Gruner
  * UNR Molecular Biosciences PhD (2014-2018).
  * currently Post-doctoral fellow, Brad Davidson lab, Swathmore College
* Dr. Daphne Cooper
  * Postdoctoral Researcher (2016 - 2018)
  * Currently Sales Consultant at 10X Genomics
* Ryan Peterson
  * UNR Neuroscience MSc. (2015-2017)
  * currently scientist at Charles River Laboratories, Reno, NV
* Dr. Kelly Phelps
  * Postdoctoral Researcher (2015)

### Former Undergrads and technicians
* Maeve Nave
  * Scientific Technician and lab manager (2021-2022)

* Jacob Countryman
  * UNR undergraduate student (2021-2022)

* Bryan Urrieta
  * UNR undergraduate student (2021-2022)

* Clarissa Stout
  * UNR undergraduate student (2019-2022)

* Sydnie Walters
  * UNR Biochemistry undergraduate researcher (2018-2021)

* Kayla Andrada
  * UNR Biology undergraduate researcher (2018-2020)

* Sharab Ahmad
  * Biochemistry undergraduate researcher (2017-2018)

* Matt Bauer
  * High School Student. Davidson Academy (2014-2018)

* Henry Ng
  * UNR Biology Undergraduate Researcher (2015 - 2018)

* Kevin So
  * Undergrad Researcher and Scientific Technician (2014- 2018)
  * Currently PhD student in Cigall Kadoch lab (Harvard)

* Dr. Mariela Cortés López
  * Undergraduate Researcher and Scientific Technician (2015- 2017).
  * Currently postdoc at NY Genome Center.

* Dr. Maebh Lynch
  * International Undergraduate Research Program (IURP) (2015-2016)

* Justin Brasher
  * Biology Undergraduate volunteer (2016-2017)

* Vicente Gapuz
  * UNR MMI undergrad (2014 - 2017)




## Locations of key files/directories

* Basic config options: _config.yml
* Top navigation bar config: _data/navigation.yml
* Single pages: _pages/
* Collections of pages are .md or .html files in:
  * _publications/
  * _portfolio/
  * _posts/
  * _teaching/
  * _talks/
* Footer: _includes/footer.html
* Static files (like PDFs): /files/
* Profile image (can set in _config.yml): images/profile.png

## Tips and hints

* Name a file ".md" to have it render in markdown, name it ".html" to render in HTML.
* Go to the [commit list](https://github.com/academicpages/academicpages.github.io/commits/master) (on your repo) to find the last version Github built with Jekyll. 
  * Green check: successful build
  * Orange circle: building
  * Red X: error
  * No icon: not built

## Resources
 * [Liquid syntax guide](https://shopify.github.io/liquid/tags/control-flow/)

## Markdown guide

### Header three

#### Header four

##### Header five

###### Header six

## Blockquotes

Single line blockquote:

> Quotes are cool.

## Tables

### Table 1

| Entry            | Item   |                                                              |
| --------         | ------ | ------------------------------------------------------------ |
| [John Doe](#)    | 2016   | Description of the item in the list                          |
| [Jane Doe](#)    | 2019   | Description of the item in the list                          |
| [Doe Doe](#)     | 2022   | Description of the item in the list                          |

### Table 2

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|-----------------------------|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=============================|
| Foot1   | Foot2   | Foot3   |

## Definition Lists

Definition List Title
:   Definition list division.

Startup
:   A startup company or startup is a company or temporary organization designed to search for a repeatable and scalable business model.

#dowork
:   Coined by Rob Dyrdek and his personal body guard Christopher "Big Black" Boykins, "Do Work" works as a self motivator, to motivating your friends.

Do It Live
:   I'll let Bill O'Reilly [explain](https://www.youtube.com/watch?v=O_HyZ5aW76c "We'll Do It Live") this one.

## Unordered Lists (Nested)

  * List item one 
      * List item one 
          * List item one
          * List item two
          * List item three
          * List item four
      * List item two
      * List item three
      * List item four
  * List item two
  * List item three
  * List item four

## Ordered List (Nested)

  1. List item one 
      1. List item one 
          1. List item one
          2. List item two
          3. List item three
          4. List item four
      2. List item two
      3. List item three
      4. List item four
  2. List item two
  3. List item three
  4. List item four

## Buttons

Make any link standout more when applying the `.btn` class.

## Notices

**Watch out!** You can also add notices by appending `{: .notice}` to a paragraph.
{: .notice}

## HTML Tags

### Address Tag

<address>
  1 Infinite Loop<br /> Cupertino, CA 95014<br /> United States
</address>

### Anchor Tag (aka. Link)

This is an example of a [link](http://github.com "Github").

### Abbreviation Tag

The abbreviation CSS stands for "Cascading Style Sheets".

*[CSS]: Cascading Style Sheets

### Cite Tag

"Code is poetry." ---<cite>Automattic</cite>

### Code Tag

You will learn later on in these tests that `word-wrap: break-word;` will be your best friend.

### Strike Tag

This tag will let you <strike>strikeout text</strike>.

### Emphasize Tag

The emphasize tag should _italicize_ text.

### Insert Tag

This tag should denote <ins>inserted</ins> text.

### Keyboard Tag

This scarcely known tag emulates <kbd>keyboard text</kbd>, which is usually styled like the `<code>` tag.

### Preformatted Tag

This tag styles large blocks of code.

<pre>
.post-title {
  margin: 0 0 5px;
  font-weight: bold;
  font-size: 38px;
  line-height: 1.2;
  and here's a line of some really, really, really, really long text, just to see how the PRE tag handles it and to find out how it overflows;
}
</pre>

### Quote Tag

<q>Developers, developers, developers&#8230;</q> &#8211;Steve Ballmer

### Strong Tag

This tag shows **bold text**.

### Subscript Tag

Getting our science styling on with H<sub>2</sub>O, which should push the "2" down.

### Superscript Tag

Still sticking with science and Isaac Newton's E = MC<sup>2</sup>, which should lift the 2 up.

### Variable Tag

This allows you to denote <var>variables</var>.
