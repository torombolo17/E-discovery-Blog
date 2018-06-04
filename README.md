# Quick Resources Guide for Legal Professionals in E-Discovery and Digital Evidence
### Author: José R. de la Vega
---
There are hundreds of tools available for legal professionals in digital evidence. Some of these tools are forensically sound, while others arn't, which makes those in that category not the best options for digital forensics examiners. The first thing to know as a digital forensics examiner is that the whole process of digital forensics is divided in foru major steps: _Acquisition_, _Preservation_, _Analisys_ and _Presentation_.

## Acquisition
Acquisition is the process of collecting and creating a forensically sound copy of the electronic evidence collected. This is the first step on the digital forensics process since this is when the digital forensics expert first comes in contact with the evidence itself. This step is crucial because if the data is acquired incorrectly (_e.g._ if the data is not copied with a forensically sound tool) then it's autentacity will be questioned. To perform a proper acquisition the forensic copies must be done with a forensically sound tool. Some of the tools that can be used are:
* Forensic Toolkit (FTK) (<https://accessdata.com/products-services/forensic-toolkit-ftk>)
* EnCase (<https://www.guidancesoftware.com/encase-forensic>)
* Logicube (<https://www.logicube.com/?v=0fe75a5189c2>)
* Wibetech (<https://www.cru-inc.com/cru-wiebetech/>)

Acquisition tools need to be able to create a forensically sound copy of the original evidence, and they usually give the user a way to verify that the forensic copy is the same as the original by comparing the hash of the copy to the hash of the original. The hash of a file or hard drive image is a mathematically function that given an file or image as an input it gives you a unique _"hash"_ that identifies that given input. if both the original and the copy have the same _hash_ value then they have the same content. Bear in mind that when we are working with acquisition on digital evidence we may use software tools or hardware tools. The hardware tools used are usually write blockers. Write blockers prevent that when the expert is making a copy of the device with the evidence wrirtes on it by accident. _Logicube_ and _Wibetech_ are hardware tools that provide a write block function. _FTK_, and _EnCase_ are tools that have multiple uses. Tools like these will be mentioned later on, since thet not only serve as acquisition tools, but they also have functions like verification, search, reporting, etc.

## Preservation
Preservation is the process of creating a chain of custody for every piece of digital evidence. The chain of custody is a document stating when, who, and how data was handled since before the evidence is collected until the evidence is returned to the owner or destroyed.If the chain of custody is broken, the validity of the evidence can be questioned. The chain of custody should also include detailed notes on how the evidence was handled. Although the chain of custody could be kept on a piece of paper there are tools that help organize the events in a better way. Some of these tools are
* Microsoft Office (<https://products.office.com/es-mx/home>)
* Google Documents (<https://www.google.com/docs/about/>)
* Apple Pages (<https://www.apple.com/lae/pages/>)
* Paper and Pen (the traditional way)
* TCMax (<https://www.ekprotrack.com/evidence-chain-of-custody-inventory-software.html>)

Some of these software tools are highly recognized and highly used for document creation in a daily base, while other may not be so common. _TCMax_ is an example of a not so common tool that provides full chain of custody features and also provides inventory and evidence tracking. It is important to have backups of the chain of custody in case of the destruction of the original.

## Analysis
Analysis is the process of finding the evidentiary items from the digital evidence acquired. The analysis of every case will be different and will involve the usage of different tools. When a digital forensics expert performs an examination he/she should document step by step their analysis. This documentation, that is part of the chain of custody, must be able to lead any other forensic expert to the same result. There are many good tools that won't be discussed in this article, but two of the most popular are EnCase and Forensic Toolkit (FTK).

## Presentation
The last step in the forensic analysis of electronic evidence is the presentation. In this step the examiner reports their background and experience, the tools used for the examination, the methods used to verify the data and statement of what he/she found. Actual data recovered that supports the statement of the findings should be presented as well. There are varios ways of presenting all of this information, but some of the most commons are:
* Microsoft Power Point 
* Apple keynote (<https://www.apple.com/lae/keynote/>)
* EnCase
* Forensic Toolkit

There are more tools out there that can work just as well as the ones mentioned here, but these are the most common. There are also tools that are specific to one sub-discipline of digital evidence, like mobile acquisition software. The  type of digital evidence involved in a cas will determine the type of tools needed to acquire, preserve, analyze and present the evidence. 
