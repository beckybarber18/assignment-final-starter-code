# COS316, Final Project: System Analysis

## Due: January 14, 2020 at 17:00


## Overview

One of the objectives of COS 316 is to understand the general principles underlying the  design, 
implementation, and evaluation of computer systems.  In this final project, you must select an open source system 
(or a  significant component of an open source system) and 
perform an analysis of the system.  Your analysis may use the various tools/frameworks we have covered this semester 
for describing system features and capabilities, including:

* Naming
* Caching
* Resource Management
* Virtualization
* Access Control

Of course, some of these  may not be applicable.  Moreover you are encouraged to define additional 
tools/frameworks to help with your analysis.

This is a *group project* - two students per group.  

## How to select a system:

You should select a system that is reasonable in size and capability.   
For example, the Android Open Source Platform (https://source.android.com/) is not a good candidate since it is
quite large and requires substantial (time and computing) resources to download and build.  

Here are some possible systems to consider; feel free to research and select your own!

* Ruby on Rails 
* Django 
* Spring 
* NGINX
* FUSE (File System in User Space)
* Nix Package Panager
* Rocket Chat
* Kubernetes
* MapReduce
* The Linux device driver API
* ActiveRecord from Ruby on Rails

There are many repositories of open source systems.   Here are a few examples; this list is not exhaustive:
* Linux Foundation - https://www.linuxfoundation.org/
* Apache - https://www.apache.org/
* GNU - https://www.gnu.org/


## Suggested approach:  

This is relatively open-ended project.  Here are some high-level guidelines:

* Identify an open source system that you and your partner can subdivide the work appropriately.
* You will definitely need to download the source system and read source code, including documentation. 
* You should be able to successfully build the system.  This is not always a trivial task. Dependencies,  outdated packages, etc. can be a challenge.
* To help understand the system, you should probably implement a few prototype applications.
* As you investigate the source code and documentation, you may find that sketching a software architecture will help you understand the various modules and their relationships (data flow and control flow). This diagram might also be useful for your report (see below). 
* Use the tools/frameworks we outlined in class to explain the major components that make the system.  However, you need not be limited to these tools. Depending on the system you selected, you may use a subset of these tools/frameworks, or you might define your own.
* Although we did not directly discuss performance and scale, you may want to consider these to help describe any limitations. You may want to design and implement some benchmarks as well.

## Deliverables
Your report be well-written and well-organized. It should clearly explain the system you have selected. Deliverables include:
* Final Report: 
    * Use your favorite document processor, e.g., LaTeX, Google Doc, Word, etc.
    * However, upload the PDF only.
    * 12pt, 1 inch margins.
    * Approximately ten (10) pages  although there is no strict limit or minimum.
    * You must cite all sources (e.g., repositories, blogs, articles, etc.) in a bibliography.
* Software: you may also include source code and documentation. 
* Any other materials that you feel are relevant to your analysis.  

Use the GitHub classroom invite to form your team and submit your report and other materials.



