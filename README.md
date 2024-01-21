# Azure-Sentinel-LIVE-CYBER-ATTACKS-

Overview:

I am documenting my current experience using Microsoft Azure to create a cloud-based virtual machine running Windows 10. To enable the virtual machine to have exposure to the internet for the live attacks, I am utilizing Azure Log Analytics Workspace, Microsoft Defender for Cloud, and Azure Sentinel to collect and aggregate attack data. The attack information is visualized on a map using Microsoft Sentinel. Throughout the project, I am leveraging various tools, with PowerShell being crucial. Specifically, I am employing PowerShell to scan the Event Viewer in the exposed VM, focusing on EventID 4625 for failed logon attempts. The script is storing this data in a logfile and transmitting the IP addresses of failed logons to IPgeolocation.io via an API. This data can then be used to map the origin of logon attempts in Microsoft Sentinel. The project is providing hands-on experience with cloud resources, APIs, Security Information and Event Management (SIEM) systems, and Microsoft Azure. I am gaining valuable insights into configuring and provisioning cloud resources and analyzing SIEM logs. Overall, this project is both enjoyable and rewarding, and I hope readers can appreciate the effort invested in it.





