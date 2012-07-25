# ECCO-TCP XML and SGML files

## What does ECCO-TCP mean?

ECCO means Eighteenth Century Collections Online. From the internet webs:
>ECCO includes every significant English-language and foreign-language title printed in the United Kingdom during the 18th century, along with thousands of important works from the Americas. --[ECCO-TCP Website](http://www.textcreationpartnership.org/tcp-ecco/)

## What is the TCP?
>The Text Creation Partnership creates standardized, accurate XML/SGML encoded electronic text editions of early print books. We transcribe and mark up the text from the millions of page images in ProQuest's Early English Books Online, Gale Cengage's Eighteenth Century Collections Online, and Readex's Evans Early American Imprints. --[Text Creation Partnership Website](http://www.textcreationpartnership.org/)

## What is this?

I have taken the [raw XML and SGML files](http://www.textcreationpartnership.org/docs/texts/ecco_files.html) and fudged them into a directory structure that may or may not make sense. 


## So what is the situtation here?

For each batch release available [at this link](http://www.textcreationpartnership.org/docs/texts/ecco_files.html) I have created a `commit` adding all of the files from that release to the repository. [Each commit includes my guess as the date of that release in the commit message.](http://github.com/lofhm/ECCO-TCP/commits/master/) As is probably obvious, I have put the XML files in the xml folder and the SGML files into the sgml folder. Finally, I have added directories containing the header and schema files at the root of the repository. This is probably not a sensible way to organize the repository. [Please file an issue](https://github.com/lofhm/ECCO-TCP/issues) if you have issue with this structure (or better yet a [pull request](https://github.com/lofhm/ECCO-TCP/pulls)!).


## Why are you doing this

I am trying to explore how the Digital Humanities might best take advantage of Git and GitHub as tools for generating, sharing, and maintaining knowledge.