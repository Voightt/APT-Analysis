# APT-Analysis
Analyzing Advanced Persistent Threats on a live network
---------------------------------
This project was my independent study final thesis for my last semester at college. Dr.Leune of the computer science department at Adelphi was my mentor and assisted me. This spanned across two semesters, where the first semester consisted of discovering what my thesis was going to be and planning, so that the second semester would involve conducting the research and coming to a conclusion based off of the findings.

I investigated how advanced persistent threats can be detected on a live network. Based on indicators of activity, I attempted to develop a proof-of-concept that applied these indicators to a live network.

For the "IoC-lists" branch:
Each of these files were used to evaluate my research and help make a step towards the thesis. The files were created chronologically from the top-down in the list below which goes along with my thoughts and findings in the paper:

- IP Addresses & Domains for APT groups.xlsx
- IP List 2.xlsx
- APTS 11_19.xlsx
- Talos list 11_27.xlsx
- threat iocs.xlsx


For the "IoCs-in-plaintext" branch:
The files are split into two folders.

For the Domains folder:
This is a list of the domains that were compiled from all of the lists in the "IoC-lists" branch, and then multiple formats of the same lists were created in case Don Becker needed it when running it against the live network. The formatted file is how the domains had to be formatted and was requested to be put in that by Mr. Becker so that it could be compared. This was done using the pyhton script in the appendix of the paper.

For the IP Addresses folder:
This is a list of the IP addresses that were also compiled from the "IoC-lists" branch. It was also all done in multiple formats, but these were all in CIDR format since that was needed to compare against the live network.

My results are found in the pdf that is in the main branch!
