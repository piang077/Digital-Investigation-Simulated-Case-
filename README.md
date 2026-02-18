# Digital Investigation (Simulated Case)
## Overview
This lab simulates a digital forensic investigation associated with a student’s death. The objective is to analyse digital evidence from multiple devices, including disk images, memory dumps, network captures, and mobile devices. All analysis and documentation follow accepted digital forensic procedures and best practices, ensuring that findings are structured in a way that could be considered court-admissible. The investigation focuses on reconstructing events, identifying relevant artefacts, and documenting findings to support a structured forensic case study.

The investigation includes the following pieces of evidence:

- **Evidence A** – Desktop computer found in the student’s dorm room  
- **Evidence B** – Network capture from the dormitory network  
- **Evidence C** – Memory dump of a personal laptop found in the student’s bedroom  
- **Evidence D** – Disk image of a damaged mobile phone found in the student’s apartment  

Click on each link below to view a detailed analysis of each piece of evidence:

- [Evidence A – Desktop Computer](Evidence-A.pdf)  
- [Evidence B – Network Capture](evidence-b.md)  
- [Evidence C – Memory Dump](evidence-c.md)  
- [Evidence D – Mobile Phone Disk Image](evidence-d.md)

## Recommendations when collecting digital evidence
When collecting digital evidence, it is crucial to ensure the integrity and validity of the data obtained. Here are tailored recommendations for the forensic       team regarding the specific evidence items:

Disk Images (Evidence A & D):

Method: Use a write-blocker to prevent alterations to the original media when creating disk images. Always calculate checksums (e.g., MD5) immediately after acquisition to confirm data integrity.

Collection: When imaging, document all relevant metadata, including serial numbers and conditions of the devices.

Network Captures (Evidence B):
Method: Use reliable network capture tools (e.g., Wireshark) to record traffic, ensuring that timestamps are synchronised with other evidence timelines.
Collection: Verify the integrity of the capture files by calculating and documenting checksums. Capture all relevant data packets, focusing on communication patterns.
Memory Dumps (Evidence C):
Method: Utilize memory acquisition tools that can create an exact copy of the volatile memory (e.g., FTK Imager). Ensure the acquisition occurs as soon as possible to prevent data loss.
Collection: Employ tools like Volatility to analyse memory dumps and extract necessary artifacts while maintaining a clear chain of custody for the data.
Mobile Phone Evidence (Evidence D):
Method: Use forensic tools specifically designed for mobile device analysis (e.g., Cellebrite, Oxygen Forensics). Attempt to extract data through both physical and logical methods, depending on device capabilities.
Collection: As with disk images, calculate checksums and document all procedures, ensuring access to critical files is performed through root privileges when needed.
By following these identification and collection methods, the forensic team can ensure that the evidence remains reliable and admissible for further analysis or potential legal proceedings. Regular training on the latest forensic tools and methods will enhance the team's effectiveness in digital investigations.
