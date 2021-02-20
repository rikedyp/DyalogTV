# Application Development

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/Xvf7q9OA4Sg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Cor(e) Blimey! What's He Up To Now?
John Daintree

?v=hgfz4c5iclw

.NET is Dead. Long live .NET!
The .NET Framework ends its life at version 4.x. In 2020, .NET 5 (based on .NET Core) will be released. We'd better get started…

## Cross-Platform Configuration Files
Richard Smith

v=Dnn2y3WutF4

Configuring the interpreter currently requires a mix of registry entries,
environment variables and command-line options. We are at the early
stages of designing a portable, human-readable and editable text file format
that will greatly simplify the tasks of configuring the interpreter, setting
different configurations for different applications, and moving the
configurations between platforms. Richard will present an overview of what
you might expect in next year's release of Dyalog.

## Web Enabling SimCorp Dimension
Stig Nielsen, SimCorp (Denmark))

v=ZSOjTNp8eYQ

As our customers are demanding services rather than software installed on premise, SimCorp has started the journey to transform SimCorp Dimension into a 3-tier solution, preparing for launching a full web-frontend version of the system. SimCorp Dimension consists of both APL and C# code, where APL is the "driver" for the entire system. Stig will take you through one of the major architectural changes that will take advantage of the "multi-concurrency" features of Microsoft.NET while at the same time
continuing to use APL where much of the business logic resides.

## What's new with HTMLRenderer?
Brian Becker

?v=C66wAhafG0Q

Some applications need only a simple user interface, popping up a window for the user to enter a bit of data or displaying messages back to the user. Others applications may need a fully interactive, rich, graphical user interface. HTMLRenderer can address both needs, across every platform where Dyalog runs.

Introduced with Dyalog version 16.0, HTMLRenderer offers the Dyalog user the ability to develop graphical user interfaces on Microsoft Windows, Apple macOS, Linux and even the Raspberry Pi. Dyalog version 17.1 adds many new features and updates to HTMLRenderer based on user feedback and our own experiences.

In this session Brian will provide a review of HTMLRenderer, demonstrate many of its new features, and present some of the tools and frameworks that are available or in development for use with HTMLRenderer.

## Easy Cross-Platform GUI Creation
Josh David

?v=G6p6G1ewokg

Wouldn't it be nice to have a single function to generate an operational GUI? Josh introduces a utility library that enables the cross-platform creation of simple recurrent GUIs.

## ]Link
Morten Kromberg and Adám Brudzewsky

?v=4cEqsBRMdW0

The Link system, prototyped by Morten for version 17.0 in 2018 and then substantially rewritten by Adám in 2019, creates an invisible bond between the active workspace and one or more folders in a file system. Each function, operator, namespace or class is linked to a source file. Selected
arrays, which are considered to be part of the source code of the application, can also be included in the link. Changes on either side of the link are immediately copied to the other side. The result is that – without changes to how APL prototyping, development and maintenance is done –
APL source code can be brought under the control of mainstream editors, source code management systems, and other development tools.

## A Git Workflow For Dyalog APL
Paul Mansour, The Carlisle Group (U.S.A.)

/?v=VuAYeDYmh6g

Git is great, but the newcomer can easily drown in a sea of commands and options. Git doesn't tell you when or why to branch, when or why to merge or rebase, how to version your project or prepare a release. AcreFlow is a radically simplified Git workflow that answers these questions. It is
implemented in Dyalog APL so you can branch, commit, and put out new versions directly from the APL session.

## Shared Code Files
Geoff Streeter

?v=o6ophqBdB5Q

> Maybe an "implementation" category/page?

Shared Code Files (.dwx files) allow code to be called without fully loading the workspace that contains it; code and data is only loaded on demand. This improves the performance of large applications while reducing their memory consumption and initialisation time. Geoff will explore the gestation, development and usefulness of Shared Code Files.

## TamStat 2019 - Technical Update
Michael Baas

> Maybe under "use cases"?

/?v=zpDRV0Rl9q4

Michael presents a more technical view of TamStat's implementation and
demonstrates a few interesting details behind recent features