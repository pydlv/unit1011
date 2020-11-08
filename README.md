# Honeypot Assignment

**Time spent:** **4** hours spent in total

**Objective:** Create a honeynet using MHN-Admin. Present your findings as if you were requested to give a brief report of the current state of Internet security. Assume that your audience is a current employer who is questioning why the company should allocate anymore resources to the IT security team.

### MHN-Admin Deployment (Required)

**Summary:** I deployed MHN-Admin onto a Vultr cloud computing VPS. I was running Ubuntu 18.04 LTS on it.

<img src="admin.gif">

### Dionaea Honeypot Deployment (Required)

**Summary:** Dionaea is a honeypot designed to capture malware submitted to the server in an attempted exploit. I put my Dionaea honeypot on another Vultr VPS.

<img src="dionaea.gif">

### Database Backup (Required) 

**Summary:** It would appear that MHN-Admin uses MongoDB, which is a non-relational database. The exported information is a list of attacks including the source IP, the honeypot that it was attacking, the ports, the time, and a unique identifier.

[session.json](session.json)

### Deploying Additional Honeypot(s) (Optional)

#### Cowrie Honeypot

**Summary:** Cowrie is a medium to high interaction SSH/telnet honeypot that is used to monitor how attackers are brute forcing ssh, and if they are able to get access, it monitors what they try to do.

<img src="cowrie.gif">

### Malware Capture and Identification (Optional)

#### X Malware

**Summary:** How did you find it? Which honeypot captured it? What does each malware do?

MD5 Hash: *Run `md5sum` on the file and record the hash here.*

SHA1 Hash: *Run `sha1sum` on the file and record the hash here.*

<img src="x-malware.gif">

## Notes

Describe any challenges encountered while doing the assignment.
