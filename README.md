# Spider Task 1 Submission

## Ilamparithi M | 107124046 | EEE

***

## Repository Overview

### Selected Tasks
1. [Cybersecurity](common/cybersecurity/README.md)
2. [Computer Networking](common/networking/README.md)
3. [Developer Operations (DevOps)](common/devops/)
4. **Domain Specific Task:** [DevOps](domain_specific/devops/)

### [Cybersecurity - Dorking with Google](common/cybersecurity/README.md)

Using search operators like `site:`, `inurl:`, `intitle:`, `intext:`, `filetype:`, `ext:`, `AND`, `OR`, `-`, and `" "`, we can run deep and targeted searches on certain websites, in the intention of finding accidentally leaked files/endpoints/information. This is called **Dorking**. For educational purposes, we take [tesla.com](https;//tesla.com) and list all (potentially) unintentionally public files and links.

### [Computer Networking - Packet Capture Analysis](common/networking/README.md)

`wireshark` is a free and open-source (🎉) utility that can capture all packets that are sent and received by the device, using a packet capture library installed on the system. These can be saved to a file called packet capture (`.pcap`) which can be used for later analysis, or distribution. One such file is given to us to be analysed. This repo contains the answers to the questions asked in the problem definition.

### [Developer Operations - Vault Sweeper](common/devops/)

A bash script named vault_sweeper that can:
- Recursively scan specified directories for sensitive or malformed environment files.
- Validate and sanitize the contents of these files based on security constraints.
- Create a directory called logs/ and add the respective logs in it. Create a user called maintainer and ensure the directory can be accessed only by the same.
- Collect and log metadata such as file user, permissions, ACLs, and modification details inside the logs/ directory.
- Generate secure output files from valid data.

### [View Domain Specific Task for Developer Operations - Dockerization of a Fullstack Project](domain_specific/devops/)
