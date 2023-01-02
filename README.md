# Learning Management System - AWS
<table>
<tr>
<td>
  In this work we will build an Infrastructure based on AWS technologies. The following will be used as a service for displaying videos inside a learning management system. But It could also be used for creating a simple distribution service of videos like Netflix or Prime Video.
</td>
</tr>
</table>


## Introduction
The rise in demand for learning management systems and other HR and learning technologies reflects a working world – and a society – that is in the midst of enormous change. Today, as organizations scramble to find and retain good talent, employees find themselves negotiating from a position of unprecedented strength. Workforces that were once localized in central offices are now distributed far and wide. Skill sets that used to be held in high demand, are gradually becoming obsolete as digital transformation begins to forever change traditional roles, integrating data-driven automation and cyber-physical processes into everyday business operations. And as it has always been, the resilient and the agile will be the ones who leverage change rather than run from it.

Most often referred to as an LMS, a learning management system is a software application that provides organizations with a framework for all aspects of the learning process. The best LMS systems are powered by AI and smart technologies and allow for cloud integration with other crucial HR and enterprise management system. The LMS houses, delivers, and tracks all learning and training content. 

## Building process
In the first part of this work we build the architecture and Back End infrastructure using aws, so it is mandatory to have an aws account available to continue. In particular we design an architecture resilient and able to scale the number of users. The architecture takes an .mp4 file and through the aws services converts the .mp4 in a stream of .m3u8 and .ts files. The format used is the http live streaming (hls). Then the files produced are signed so that no one is able to enter the stream without a valid account on the platform. We proceed also with the automatization of the whole building, deploying and versioning process with terraform.
[click here for the architecture](/doc-lms/architecture.md)

In the second part of the project we create an instance on a server of a java spring application as a backend for a website for distributing the videos. Finally we create the frontend, composed by videojs. [click here for the server app](/doc-lms/architecture.md)


## Team
<img src="images/me.jpg" width="182" height="200" />

Morgan Malavasi

---|---


## [License](link)



