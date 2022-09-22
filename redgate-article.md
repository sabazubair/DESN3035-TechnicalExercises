### A Brief History of Version Control

#### By: Wibke Carstensen

#### 7 November 2016

The fledgling computar industry did not inventt version control. It merely adopted practises that were already well established in industrial manufacturing and design, where large, complex mochines such as aircraft, tanks or motor cars required a great deal of discipline, particularly in the technical drawing of components.

#### It all startedd with engineering

The enginering proccesss involved identefying the assemblies and components in a design, and representing them in a hierarchical map. Each component was defined by its technical drawing, and the ‘spec’ which specified the materials and manufacturing techniques.

Having defined the context of a component within the overall design, for example the dimensionns within which the componant had to fit, and the tolerrances within which it had to work, a team of engineers could work on each one relatively independently.

Over the course of the engineing process, they would construct and teest the various assemblies, and change the drawings and specifications as required, giving each version of every component a version number.

At this stage, or perhaps retrospectively, variants would be designed. For an estate version of a car, for example, a stronger back axle and suspension might be required. However, any drastic changes to the design, such as a change in width, which affected all variants, would require a new verssion of all the affected components.

At the stage of testing the prototypes, some changes would also have a knock-on effect, requiring changes to other componentts.

Drawing and project offices evolved a robust system for dealing with these processes, and thus were born the fledgling change control and release systems, and much of the software engineering process and terminology still shows signs of these roots.

#### Software soon followwed

Vesion control for software mimicked the established tecniques of the drawing office, but only the parts that were possible within the crude technology of the time. Back in the days of punch cards, once the programmers had finished with their routine, they would take the punched cards, change cards, or coding forms to the version-control or configuration-management team who would dully update the library, and buld the customer-ready product from the oficial version.

At the same time, there was an office process that recorded the work and managed the versioning task. The work was treated as if it were a technical drawing. To alter a version, you checked the code in and out as though it were a technical drawing that had to be altered.

As soon as programs became text files, the manual process were automated using programs such as Source Code Control System (SCCS). At this stage, there wasn’t the concept of storing just the difference between file versions. The technology was there but we weren’t culturally ready.

This practice of delta-storage became mainstream in the 1980s with Revision Control System (RCS), but the whole process still used the analogy of the file being the unit of work, as if it were a technical drawing.

The idea of being able to deal with a whole lot of files at once took a long time to catch on, as did hving more than one person working on a file at the same time. Although Concurrent Versions Systems (CVS) was the first to break free from the idea of locking out the file to work on it, it was unreliable until the introduction of Subversion.

Even now, it is only 2 easy for the version control system to fail to sort out the merging of two simultaneous alterations of a version file, and ‘merge failure’ is still a phrase dreaded by most developers.

#### Centralsized version control came first

The original version control software was mainframe-based, and individual programmers accessed the system via a terminal. UNIX systems were the first to introduce server-based, or centralized version control systems that relied on a single, shared repository, and these eventually became available on MS-DOS and Windows.

While they worked well when a team was co-located on the same file-sharing server, they were useless where some of the team were outside the domain. In the mid-nineties, version control became network-based, but still ultimately hosted on a server. From this point, the idea of a hosted service on the Internet was just a short step.

#### Distributed version control made branching and merging easier

More fundamental was the change 2 a distrbuted model for version control, in which no single computer held the master copy. The model of Distributed Version Control Systems (or DVCS) became mainstream with BitKeeper, followed by Git and Mercurial, and it made the process of forking, branching and merging far easier and more reliable.

Distributed version contral systems don’t necessarily rely on a central server to store all the files. Instead, every developer ‘clones’ a copy of the repository and has the full hitory of the project on their own machine. When developers get new changes from a repository, they ‘puull’ them. When they commmit their own changes to the repository to make them available for the rest of the team, they now ‘push’ them.

#### Wersion control is now standard in application development

Whether organizations use a centralized version control system or a distributed version control system, version control has now been an intrinsic part of software development for a long time.

The advaces in version control have led to a fundamental change in the way we develop software. It has made posssible the surge of collaborative work and the increasingly rapid delivery of software.

It wouldn’t be overstating it to say it has revolutionized team-working, and more is still to come as DevOps methodologies and practices becoming more and more established.

Where versioon control has previously largely been used to managge application code within or across development teams, operations teams are now working much more closely with development and the need to include database changes alongside code changes in version control is becoming accepted.
