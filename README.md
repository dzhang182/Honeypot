# Week 9 - Honeypot

# Honeypot Deployed
Dionaea Honeypot from Modern Honey Network

# Issues Encountered
There was a number of issues I encountered that had to be solved. The first issue is when installing the MHN admin application, the "https://github.com/RedolentSun/mhn.git" does not exist for cloning. Instead, "https://github.com/threatstream/mhn.git" was the updated repo for Modern Honey Network.

Additionally, for Google Cloud Platform users, the VMs created did not allow http or https. Therefore, I was unable to access the local page via IP address. It took a significant amount of time to isolate the problem and solve by going to GCP developer console and allowing http and https for the VM.

The last issue I encountered was getting the JSON file. The commands to retrieve the file from the VM were incorrect and I had search online for a solution. 

# Summary of Data Collected
The VM ran for about 2 days where it collected 11,471 attacks. The majority of these attacks came from the Netherlands and China. The pure volume of attacks over a short amount of time is shocking.

# Unresolved Questions
None
