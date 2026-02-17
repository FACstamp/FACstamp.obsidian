#### 1) Why use Obsidian?
The current thought is to leverage Obsidian as the website infrastructure for a few primary reasons:
- a key aspect of FACstamp is to meet people where they are and not force a change in belief system or life philosophy of choice.  As such the major religions and non religions as well as individual variations need to be supported, and the current thought is to use a mind-melding second generation note taking tool such as Obsidian to support individualized choice and paths through the material contained within.  There will be/are many variations to the basic FACstamp material and the reader needs with minimum effort switch and choose the variation that makes the most sense to them.
- it is highly convenient for the website infrastructure to support automatic backlinks and their updates
- it is also convenient if the website page organization can be refactored at will without manual link updating.

#### 2) What is Obsidian?
[Obsidian](https://obsidian.md/) is a [note-taking knowledge base tool](https://en.wikipedia.org/wiki/Obsidian_(software)) that supports turnkey cross linking of documents, tags, and ideas.  Though the app itself is not open source, Obsidian is markdown file based, meaning that there is no lock in of any data stored in the application.  If WordPress supported an Obsidian like capability, that solution might be preferable.

Obsidian has a subscription service (called publish) which supports uploading pages to a CloudFlare supported website located at publish.obsidian.md/facstamp.

#### 3) How is Obsidian used?
This website is essentially an Obsidian vault stored as a Git repository, FACstamp.obsidian, on GitHub located at https://github.com/FACstamp/FACstamp.obsidian.  The current collaboration idea is that all development and collaboration occurs on GitHub leveraging standard GitHub features and development best practices.  See [Using Git & GitHub](Volunteering/Using Git & GitHub.md).  Currently the Obsidian publish and website hosting service is leveraged to host and develop this website.  See [Using Obsidian](Volunteering/Using Obsidian.md).

As the security of Obsidian plugins is ultimately left as a TBD by the end user, you may reasonably decide not to load any.  Regardless, three plugins that may be useful are:
	1) https://obsidian.md/plugins?id=dataview
	2) https://obsidian.md/plugins?id=obsidian-advanced-uri
	3) https://obsidian.md/plugins?id=custom-sort

The last plugin, custom-sort, can be used to sort the files and folders in the vault to match the layout of the published website (what you may be reading now).  The publish application supports limited web publishing features, one of which is the ordering of files and folders in the navigation pain on the left.  In this vault the default filename is used for custom sorting, namely 'sortspec'.
