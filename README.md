Minecraft Server on Google Cloud
================================

Step 1: Create a VM instance
--------------------------------

https://cloud.google.com/compute/docs/instances/create-start-instance

Step 2: Mirror GitHub repository
--------------------------------

https://cloud.google.com/source-repositories/docs/mirroring-a-github-repository?hl=en_US

Step 3: Configure startup script
--------------------------------

https://cloud.google.com/compute/docs/instances/startup-scripts/linux#passing-directly

Suggested startup script:

`#! /bin/bash`  
`sudo chmod +x opt/init`  
`opt/init`
