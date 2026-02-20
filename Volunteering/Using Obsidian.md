#### 1) Why use Obsidian?
The current thought is to leverage Obsidian as the website infrastructure for a few primary reasons:
- a key aspect of FACstamp is to meet people where they are and not force a change in belief system or life philosophy of choice.  As such the major religions and non religions as well as individual variations need to be supported, and the current thought is to use a mind-melding second generation note taking tool such as Obsidian to support individualized choice and paths through the material contained within.  There will be/are many variations to the basic FACstamp material and the reader needs with minimum effort switch and choose the variation that makes the most sense to them.
- it is highly convenient for the website infrastructure to support automatic backlinks and their updates
- it is also convenient if the website page organization can be refactored at will without manual link maintenance
#### 2) What is Obsidian?
[Obsidian](https://obsidian.md/) is a [note-taking knowledge base tool](https://en.wikipedia.org/wiki/Obsidian_(software)) that supports turnkey cross linking of documents, tags, and ideas.  Though the app itself is not open source, Obsidian is markdown file based, meaning that there is no lock-in of any data stored in the application.  If WordPress supported an Obsidian like capability, that solution might be preferable.

Obsidian has a subscription service called publish which supports uploading pages to a CloudFlare supported website.  FACstamp employs this publish feature and the URL is [https://publish.obsidian.md/facstamp](https://publish.obsidian.md/facstamp).

There is a plethora of JavaScipt/CSS community plugins that extend Obsidian capabilities.  The security of Obsidian plugins is ultimately left as a TBD to the end user.  FACstamp can be developed without any community plugins; however, you may find the following three useful (in addition to perhaps a custom theme of choice, which is just another plugin):
	1) https://obsidian.md/plugins?id=dataview
	2) https://obsidian.md/plugins?id=obsidian-advanced-uri
	3) https://obsidian.md/plugins?id=custom-sort

The last plugin, custom-sort, can be used to sort the files and folders in the vault to match the layout of the published website (what you may be reading now).  The publish application supports limited web publishing features, one of which is the ordering of files and folders in the navigation pain on the left.  In this vault the default filename is used for custom sorting, namely 'sortspec.md' - that is the markdown file that defines the ordering of folders in files in the navigation panel to match the published site.
