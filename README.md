# Ryan Gaunay
# CodePathWeek9
# Honeypot HW - 11/28

Honeypot Deployed: 
- Ubuntu: Dionaea with HTTP on Google Cloud

Issues:
- The only issue I encountered was cloning the mhn git repository in Milestone 2
  since a repository it was referencing no longer existed.  However, we were provided
  with a fix which resolved the issue.

Summary:
- In all, my honeypot was only attacked once about a minute after it was created.
  I would've liked to have been attacked more, but unfortunately I had to start over 
  as my VM somehow restored to a 3-week old snapshot and wiped everything. The
  attacker seems to be from Ukraine, and somehow managed to attack instantly.

Questions:
- I am very interested in how attackers found my honeypot so quickly. Almost as soon
  as I deployed it, I refreshed the page and there was a Ukranian IP listed. Do they
  scan ports on brute-forced IPs? Also, are there ever any repercussions for attackers, 
  or are their IPs not helpful because they're probably using something like Tor to 
  mask  themselves? Overall, it was very interesting to see.

JSON:
- Attached is the JSON relating to the single attacker as of 11/28.