 [[09 Static FACstamp Data|Previous Slide]]  |  [[What is FACstamp? - a slide presentation|Back to Beginning]] 
Consider the following FACstamp:
![[FACstamp-green-3-5.png|200]]
It contains multiple pieces of live data.

Running vertically on the left hand side is the overall compliance of the three FACstamp license requirements: [[Requirement 0 - Authenticity]], [[Requirement 1 - Historical Accuracy]], and [[Requirement 2 - Virtuous Delivery]].

Running vertically on the right hand side are the number of the currently active warranty claims against this FACstamp followed by the completed, adjudicated warranty claims.  Green indicates that the warranty claims have been rejected, thus the stamp stands as green - see [[What happens when a warranty claim is approved?]].  If a warranty claim as been found to valid, this entry will no longer be green - see [[What happens when a warranty claim is rejected?]].

When a claim is rejected, one or more of the left hand column entries also change from green to some other color/status.

Note that all state changes, being transactions, are recorded as such on the FACstamp public ledger, similar to cryptocurrency transactions.

One of the more subtle but quite interesting FACstamp live statuses is the FACstamp Directed Acyclic Graph status in the lower right.  The left number indicates the number of upstream FACstamps that this FACstamp references.  The number on the right indicates the number of downstream FACstamps that reference this stamp.  These are live counts, supplied by the backend infrastructure that implements FACstamps - see [[What happens when an upstream FACstamp changes state?]].

Here is an example of a revoked FACstamp:
![[FACstamp-red.png|200]]

And here is an example of when an upstream referenced stamp get rejected:
![[FACstamp-upstream-rejcted.png|200]]
