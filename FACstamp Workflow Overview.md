## 1\) Background Information

### 1.1) FACstamp Summary

The project goals of FACstamp are stated in the [[FACID Summary]]

### 1.2) FACID \- a verified online ID usable by FACstamp and other third-parties

As FACstamp requires some type of online authentication and associated digital signing of content by known individuals, FACstamp relies on what is referred to as a FACID \- a verified online ID.  The basic workflow for creating a FACID is for new members to authenticate themselves when in the same location as an existing member, when in person, and when registering themselves against a known and legal name and address.  (There is a FACID smart device app that facilitates this.)  The address and name are primarily taken from public voter registration databases but alternative methods are also supported.  An example of greater authenticity is an integration with applications such as [Clear](https://www.clearme.com/).  However, the case of lesser authenticity is also supported, such for users ineligible to vote and/or without official government ID.

FACID’s introduce additional target goals beyond FACstamps such as the following:

1. support the creation of safe and bamboozlement-free online communities and 'news zones' grounded in our common humanity and historically accurate information  
2. support and extend the historical system-function of safe and local neighborhoods and caring communities into online world wide web communities  
3. raise the consciousness/virtue and discernment of all participants to more expansive and wiser levels, both on an individual as well as collective basis

Also note that FACID’s participate in a live authentication network to limit BOT and corporate/anonymous intrusions.  FACID’s are renewed on a constant interval basis.

FACID’s are the layer that provides the authenticity of FACstamp Licensees and FACstamp Consumers.  FACID’s contain a fundamental end-user License agreement associated with its creation.  The License agreement specifies both a discernment ‘historical accuracy’ clause and a virtuous intention clause (see [[FACID Summary]]).

Note \- with funding, multimedia material will be created to explain and describe how FACstamp can be used in social media, traditional media, and the like with consistent and ‘meet people where they are’ references to the project goals.

### 1.3) Licensee Workflow Overview

Described:

- Sign up for (create) a FACstamp  
- Create a FACID public persona  
- Signing Content (static content)

Not yet described:

- Find out more information about FACstamps, FACIDs, and the whole process  
- Alter a FACstamp color/status  
- Get notified of a warranty fit-for-use claim  
- Respond to a warranty claim

### 1.4) Consumer Workflow Overview

Described:

- Sign up for a FACID  
- Create a FACID public persona  
- Check/validate a FACstamp

Not yet described:

- Find out more information about FACstamps, FACIDs, and the whole process  
- How to submit a fit-for-use warranty claim

### 1.5) Fitness-for-use Warranty Claim Process

Fitness-for-use warranty claims are nominally adjudicated initially by third-party arbitration.  Upon failure of third-party arbitration, the judicial system is used.  Question \- can either federal or state courts can be used?

### 1.6) FACstamp and FACstamp Network Transparency

A key aspect of the physical FACstamp 'network' is the live/active 'colorization' (status) of FACstamps (similar to say GitHub badges) indicating the current state of the FACstamp of interest.  A FACstamp color/status is displayed by contacting the FACstamp cloud based servers to determine the current color (compliance/status) of a specific FACstamp.

Note that FACIDs have a sense/definition of a LAN network based on the bio-location of the user id.  People on the LAN share certain activity feeds by default.  Similar to several hundred years ago when living in a community resulted in some level of transparency, FACIDs bring a similar level of online transparency to the FACID LAN.  The non-LAN anonymity may or may not be revealed in a fit-for-use warranty claim process depending on safety concerns.

As the public aspects of FACIDs and FACstamps are stored in public Merkle Trees, the current and previous states of FACIDs and FACstamps are always available.  FACstamps and their network are query-able via REST APIs.  For example, one possible usage might be one where attorneys monitor the various fit-for-use claims per FACstamp, per persona, etc to decide when to submit an litigation action against a Licensee or Consumer.

### 1.7) FACstamp Reference Chains

Another public access point into the FACstamp network is insight to the chain of references that a FACstamp includes by reference.  If an upstream FACstamp turns green, yellow, red, or gray, so may downstream FACstamps.  If a FACstamp contains multiple upstream references and only one changes color, there is a documented process for determining downstream colors.

Note that this type of network is actually a directed acyclic graph (DAG) and as such, new edges in the graph (references to other FACstamps) that create a cycle are blocked.  In addition isolated islands of nodes are also noted, etc.

Also note that nodes and edges can disappear.  Though this can for example allow a red node to change color to say green due to an upstream red node or edge disappearing, the network graph data is always contained fully in a Merkle Tree with full version history.  As such a node losing a single reference that was red can go green but it could/would have a cautionary marking that indicated that historically it was once red by reference.

## 2\) Workflows

### 2.1) Creating a FACID or a FACstamp

Both Licensee and End user sign up the same way \- by signing either a binding Licensee License Agreement or a binding End User License Agreement (Consumer EULA).  In both cases a FACID needs to be created first.  With a FACID a FACstamp can then be created.  To create either:

1) Download the app  
2) Find someone with a FACID  
3) With smart devices within visual range and nominally within range of the voter registration location, click either the 'create a FACstamp' button or the 'create a FACID' button

Note that FACID's are nominally keyed to public voter registration data \- the name and address must match existing public data.  Successful creation generates a FACID private key (in both cases) and a FACstamp private key for a Licensee.  Note that the both are bound to the bio-location of the registration location.  It can be moved via another FACID phone registered in a different location, etc.

A new FACID cannot be created on top of an existing one \- creating a FACID/FACstamp for the same user in a different location is prohibited by the license agreement and by software.

The public keys are uploaded to the respective public Merkle Trees.

### 2.2) FACID \- creating a public persona

FACIDs support creating public persona's.  The public persona may or may not be ‘anonymous’ in the sense that the FACID name and address may be hidden from the FACID WAN network.  Anonymous persona’s allow the end-user with a FACID to publish WAN content anonymously in the case of hostile or dangerous online communities.

### 2.3) FACstamp \- signing content

For simple tweets, blogs, and md/txt/html/pdf content, the Content/file is signed by a persona key.

The generated QR code contains a link back to public FACstamp and persona/FACID Merkle Trees.  Note that public keys behave like PEM files \- they can be revoked and have time limits.  Regardless, they are stored in a public ledger.  The QR code also contains a digest of the content.  It may also contain a restrictive URI for security reasons.

Depending on the Licensee service contract ($), the creation of the FACstamp may also include uploading the Content into the public FACstamp Content Merkle tree.  Doing so has pluses and minuses.  Regardless, if a FACstamp changes color all instances of the FACstamp change color since 'color' is a live look-up in the signing content Merkle Tree regarding FACstamp licensee warranty compliance (Green, yellow, or Red).  Green is good and unchallenged.  Yellow is challenged and in process.  And Red is non FACstamp compliant \- as in, the content does not abide by the fit-for-use warranty.  Gray with a slash indicates something fundamentally wrong with the FACstamp (bad digest, etc).

### 2.4) End-user checking a FACstamp

The act of retrieving a FACstamp retrieves its color/status from the FACstamp servers.  Nominally the colors can be green, yellow, red, and gray with a lightning bolt \- stop/error watermark.  The associated FACstamp statuses are good, in question, not good, and hacked/illegitimate.  The latter is when either the content or the FACstamp/digest etc has been compromised.

As webpages (javascript) can be hacked, it is probably the case that the user may need to either click the FACstamp or use the FACstamp app to visually inspect the stamp.  Or it may be the case that a user needs to enter the URL (or do something else) to securely validate a FACstamp (more is needed here TBD).

### 2.5) Creating a warranty claim

When a FACstamp end-user wishes to start a fit-for-use warranty claim, in the FACstamp app they click the 'submit fit-for-use' warranty claim button, which may use the camera or manual FACstamp entry.  Whether by app or webpage, the end-user enters data including references as evidence that the fit-for-use warranty has been broken.  The warranty claim process follows processes analogous to ubiquitous support ticket workflows.

At a high level there is a time boxed back and forth sequence between the Licensee (Content producer/provider) and the end-user (the Content Consumer).  Several outcomes are supported:  the claim can be dropped, rejected, or accepted.  If accepted the FACstamp color is changed by the Licensee.  If rejected, the Consumer is free to start a litigation of the claim.  Since 'this data' is public and available as database queries, third-parties can also initiate litigation by duplicating the rejected warranty claim.

### 2.6) Responding to a warranty claim

When a Licensee receives a fit-for-use warranty claim, they can decide to ignore it, reject it, or accept it.  Accepting occurs when they change the color/status of the FACstamp.  Ignoring it opens the Licensee to potential litigation.  Rejecting it communicates to the Consumer that the signed Content is claimed to be both ‘true’ and ‘virtuously delivered’.

An orthogonal option is if the Licensee believes that the Consumer is making a fraudulent claim (a claim not based on evidence as defined by the FACstamp Licensee/Consumer license agreements nor aligned with the virtuous FACID community standards), the Licensee may initiate a fraudulent counter-claim against the Consumer.  A counter-claim also has a defined claim process and is directly supported in the App or webpage.

### 2.7) Litigating a warranty claim

When a fit-for-use warranty claim or counterclaim has reached the litigation phase, licensed attorneys and arbitration personnel become involved.

## See Also
[[README]]
[[FACstamp Pitch]]
[[FACstamp Introduction]]
[[FACID Summary]]
[[FACStamps and FACIDs]]
