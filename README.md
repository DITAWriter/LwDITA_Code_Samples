# LwDITA_Code_Samples
A set of code samples designed to demonstrate what is possible for each of the "flavors" of Lightweight DITA. All examples are based on  sections of various TRS-80 manuals from the late-1970s/early-1980s that have either lapsed out of copyrihgt or have been donated to the Public Domain. Includes sample marketing material, computer hardware content, software samples, legal frontmatter and glossary.

These files represent one interpretation as to how Lightweight DITA markup ought to be done, based on information available in the current version of the [Lightweight DITA Committee Note](http://docs.oasis-open.org/dita/LwDITA/v1.0/cnprd02/LwDITA-v1.0-cnprd02.pdf), and the sample files that come with it.  

The following sets of files build in complexity, so that the reader can understand the key working differences between each flavor of LwDITA. 

It is recommended that you use 3.x or higher version of the [DITA Open Toolkit](https://www.dita-ot.org/) to process the files, and to use the [latest LwDITA DTDs](https://www.oasis-open.org/news/announcements/invitation-to-comment-on-lightweight-dita-an-introduction-from-the-dita-tc-ends-m/LwDITA-v1.0-cnprd02-grammars.zip) to validate your own LwDITA content where possible. 

## TRS-80 Expansion Module (MDITA Core)
These files were created using MDITA Core markup. This is the "base" version, and contains only what is allowed in an MDITA Core LwDITA set of content. Tables utilize standard GitHib markup, with one including valid HTML (not HDITA) code to distinguish points within a table cell. 

## TRS-80 Expansion Module (MDITA Expanded - No Keys) 
These files were created using MDITA Expanded markup, building upon the previous version by including YAML headers and mixed HDITA markup for things like the definition lists that appear in the glossary. 

## TRS-80 Expansion Module (MDITA Expanded - With Keys) 
This set of sample files are the same as the previous example, but with the addition of keyrefs. The values are set in the "map" file (index.md) and are expressed in the individual MDITA topics using HDITA markup.

## TRS-80 Expansion Module (HDITA) 
These files are functionally the same as the "MDITA Expanded version" with keys, but is based entirely HDITA markup. It is based on HTML5, and all files end with the ".html" suffix.

## TRS-80 Expansion Module (XDITA)
These files are functionally the same as the "MDITA Expanded version" and the "HDITA version", but uses XDITA markup. These files should be directly usable in any DITA 1.3 compliant setup, though note that the multimedia elements "three_expanded_systems.dita" may not work using DITA 1.3 DTDs instead of those for LwDITA. Also note that the tables follow simpletable formatting, as required within LwDITA. *This is still a work-in-progress, but the existing code is workable.*

## TRS-80 Expansion Module ("Full" DITA 1.3) [TBD]
This version of the files is done using "full" DITA 1.3, so the topics are typed, and follow DITA writing best practices.
