- can we design a script that scans a repo and outputs a markdown file that describes the possible outcomes of each trigger?
- Starting with the message bus, it should iterate over each message and event, building a list of downstream events. Each number under a message signifies a possible outcome. Within each outcome, there should exist a description of what takes place in the domain (db actions, kafka actions, 3rd party actions i.e. s3).
- There should exist 3 ways of reading the docs.
	- Bullet points and references
	  logseq.order-list-type:: number
	- A written description of the flow (if this, then that)
	  logseq.order-list-type:: number
	- a flowchart showing the possible pathways
	  logseq.order-list-type:: number