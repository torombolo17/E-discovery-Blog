# Quick Resources Guide for Legal Professionals in E-Discovery and Digital Evidence
### Author: José R. de la Vega
---
There are hundreds of tools available for legal professionals in digital evidence. Some of these tools are forensically sound, while others aren't, which makes those in that category not the best options for digital forensics examiners. The first thing to know as a digital forensics examiner is that the whole process of digital forensics is divided in four major steps: _Acquisition_, _Preservation_, _Analysis_ and _Presentation_.

## Acquisition
Acquisition is the process of collecting and creating a forensically sound copy of the electronic evidence collected. This is the first step on the digital forensics process since this is when the digital forensics expert first comes in contact with the evidence itself. This step is crucial because if the data is acquired incorrectly (_e.g._ if the data is not copied with a forensically sound tool) then it's authenticity will be questioned. To perform a proper acquisition the forensic copies must be done with a forensically sound tool. Some of the tools that can be used are:
* Forensic Toolkit (FTK) (<https://accessdata.com/products-services/forensic-toolkit-ftk>)
* EnCase (<https://www.guidancesoftware.com/encase-forensic>)
* Logicube (<https://www.logicube.com/?v=0fe75a5189c2>)
* Wibetech (<https://www.cru-inc.com/cru-wiebetech/>)

Acquisition tools need to be able to create a forensically sound copy of the original evidence, and they usually give the user a way to verify that the forensic copy is the same as the original by comparing the hash of the copy to the hash of the original. The hash of a file or hard drive image is a mathematically function that given an file or image as an input it gives you a unique _"hash"_ that identifies that given input. if both the original and the copy have the same _hash_ value then they have the same content. Bear in mind that when we are working with acquisition on digital evidence we may use software tools or hardware tools. The hardware tools used are usually write blockers. Write blockers prevent that the expert writes on the original device by accident while making a forensic copy. _Logicube_ and _Wibetech_ are hardware tools that provide a write block function. _FTK_, and _EnCase_ are tools that have multiple uses. Tools like these will be mentioned later on, since they not only serve as acquisition tools, but they also have functions like verification, search, reporting, etc.

## Preservation
Preservation is the process of creating a chain of custody for every piece of digital evidence. The chain of custody is a document stating when, who, and how data was handled since before the evidence is collected until the evidence is returned to the owner or destroyed.If the chain of custody is broken, the validity of the evidence can be questioned. The chain of custody should also include detailed notes on how the evidence was handled. Although the chain of custody could be kept on a piece of paper there are tools that help organize the events in a better way. Some of these tools are
* Microsoft Office (<https://products.office.com/es-mx/home>)
* Google Documents (<https://www.google.com/docs/about/>)
* Apple Pages (<https://www.apple.com/lae/pages/>)
* Paper and Pen (the traditional way)
* TCMax (<https://www.ekprotrack.com/evidence-chain-of-custody-inventory-software.html>)

Some of these software tools are highly recognized and highly used for document creation in a daily base, while other may not be so common. _TCMax_ is an example of a not so common tool that provides full chain of custody features and also provides inventory and evidence tracking. For preservation and chain of custody purposes, any software tool that let the user type notes and store them somewhere will work, but it is important to have backups of the chain of custody in case of the destruction of the original.

## Analysis
Analysis is the process of finding the evidentiary items from the digital evidence acquired. The analysis of every case will be different and will involve the usage of different tools. When a digital forensics expert performs an examination he/she should document step by step their analysis. This documentation, that is part of the chain of custody, must be able to lead any other forensic expert to the same result. There are many good tools that won't be discussed in this article, but two of the most popular are EnCase and Forensic Toolkit (FTK).

EnCase and FTK are very similar in functionality. They are both multipurpose tools that provide functionality to make acquisition, analysis, keyword searches, imaging capabilities, and many more. When it comes to the comparison of both users usually go with what they are more comfortable with. As in performance they both have some advantages and disadvantages. FTK creates a keyword index of the entire image at the start of the process, this makes it more slow to start, but way more efficient when searching for keywords after the initial setup of the image has been completed. Although FTK is better when performing keyword searches, EnCase excels at examining complex structures since it breaks a file structures for examination. This can be very helpful when performing analysis. Both tools are great and comparing them to determine which one is better is very difficult. I wouldn't say one is better than the other. They both have outstanding functionality and the best way to determine which one to use is to try them both and find out by yourself.

To give a little more information about the functionalities of both tools I'll use as reference the information provided by _Forensic Labs_ on Medium (<https://medium.com/@cloudyforensics/encase-vs-ftk-vs-x-ways-review-2b7b075333ef>).

**Forensic ToolKit**
* Apple DMG and DD_DMG disk image support
* JSON file support
* Support for 700 image, archive and file types
* Notes NSF, Outlook PST/OST, Exchange EDB, Outlook Express DBX, Eudora, EML (Microsoft Internet Mail, Earthlink, Thunderbird, Quickmail, etc.), Netscape, AOL and RFC 833
* Process and analyze DMG (compressed and uncompressed), Ext4, exFAT, VxFS (Veritas File System), Microsoft VHD (Microsoft Virtual Hard Disk), Blackberry IPD backup files, Android YAFFS / YAFFS 2
* Derypt Credant, SafeBoot, Utimaco, SafeGuard Enterprise and Easy, EFS, PGP, GuardianEdge, Pointsec and S/MIME.
* View E-Mail Details Graphically
* Explicit Image detection
* Generate Reports in CSV, HTML, PDF, XML, RTF

**EnCase**
* Acquisition Restart
* Logical Evidence Files
* Acquire Evidence via Bootdisk
* Acquire volatile memory
* EnScript Scripting
* Filters and Conditions
* Active Directory Information Extractor
* Hardware Analysis
* Recover partitions
* Recover deleted files/folders
* Windows event log parser
* Link file parser
* File Signature analysis
* Hash analysis
* File finder
* Built-in Registry Viewer
* External File Viewers
* Gallery View
* Calendar viewer
* Unicode index search
* Binary search
* Proximity Search
* Internet and email search
* Case Sensitive
* Listing of all files and folders
* List all URLs
* Acquisition and Hard Drive details

## Presentation
The last step in the forensic analysis of electronic evidence is the presentation. In this step the examiner reports their background and experience, the tools used for the examination, the methods used to verify the data and statement of what he/she found. Actual data recovered that supports the statement of the findings should be presented as well. There are various ways of presenting all of this information, but some of the most commons are:
* Microsoft Powerpoint 
* Apple keynote (<https://www.apple.com/lae/keynote/>)
* EnCase
* Forensic Toolkit

There are more tools out there that can work just as well as the ones mentioned here, but these are the most common. There are also tools that are specific to one sub-discipline of digital evidence, like mobile acquisition software. The  type of digital evidence involved in a cas will determine the type of tools needed to acquire, preserve, analyze and present the evidence. 
