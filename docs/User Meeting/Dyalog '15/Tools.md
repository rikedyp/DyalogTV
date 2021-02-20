# Tools

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/l16INr6itqM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Mining the Depths of Excel – a Case Study in Objects and Arrays
Richard Procter, APL Borealis

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/NAEhbmpWMj4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

For those who need to move data back and forth between APL and Microsoft Excel, the options are growing. With Microsoft Office 2007, Excel and other Office documents adopted an open, XML-based file format. From an APL perspective, XML is nothing more than a delimited string of text – and we know how to handle such things in APL (in addition to which we have ⎕XML). Several object-oriented, .NET-driven class libraries exist for manipulating \*.xlsx files without the need for Excel itself. These include Syncfusion's XLsIO, which is now provided by, and integrates easily with, Dyalog. Office Automation, using COM techniques, still works but has its limitations (and, of course, still requires Excel to be installed). The newer XML-based tools also have limitations, some of which can be overcome with familiar APL array-oriented magic.

## RIDE: a New Way to Interact with the Interpreter
Nick Nickolov

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/OPR6elGIYq0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The RIDE (Remote Integrated Development Environment) is a graphical front end that can be used to develop and maintain Dyalog applications, irrespective of the computer that the Dyalog engine is running on. Nick explains how you can make the most of RIDE's latest features and enhance your coding comfort and efficiency by customising the default keystrokes, characters, and colours.

## External Workspaces
Morten Kromberg, Technical Director (CTO) & Stig Nielsen, SimCorp (Denmark)

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/aInyvTdMHMo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

An External Workspace is a workspace saved in a new format that allows an application to page code and data into the active workspace on demand, rather than loading the entire workspace when the application starts. The files are memory mapped, which means that processes running on the same machine can share the memory used by the parts of the workspace which have been paged in, and the file is only read by the first process that uses any particular function or variable.

SimCorp Dimension is a rapidly growing application. At run time, code is usually loaded from a network drive. The time required to load the workspace and subsequently to page code in from component files is also steadily growing. Details of the implementation of External Workspaces at SimCorp will be discussed – including some timings.

## Sharpleaf: Flowing Automated Reports to Paper
Nicolas Delcros

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/22-6wOdoiu4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

SharpLeaf is a typesetting and tabulation engine that allows automated production of high-quality reports using a simple yet powerful API. It is the replacement for NewLeaf, and will be bundled within the SharpPlot package. Nic takes us through why and how to use it.

## User Command Update
Adám Brudzewsky & Dan Baronet

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/ktsFyXnEspo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

This presentation concentrates on the latest changes to user commands. Particular emphasis is given to the new ]CopyReg command (introduced at version 2.01 with Dyalog version 14.1), which enables a Microsoft Windows user to copy configurations from one version of Dyalog to another.

## DP2 - The Dyalog Project Project
Morten Kromberg, Technical Director (CTO)

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/76_wqInqkXw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Dyalog intends to develop new tools for application development. A central idea is the notion of a shared definition of a "Dyalog Project": a mechanism for declaring the source code components that an application is built from and build directives to build and deploy different variants or sub-sets of the application, for different uses or target platforms. Future tools are likely to revolve around such "project definitions", which need to be sufficiently flexible to allow new users to ask for "A New Dyalog Web Application" and have it up and running in minutes, and still describe legacy applications well enough to allow selected tools to be brought to bear on them.

Keywords: Source Code Management, Dependency Management, Building and Deploying applications.