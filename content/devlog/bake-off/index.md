+++
title = "Bake off - second attempt in the kitchen!"
date = 2024-10-03T10:00:00+10:00
draft = false
+++

Two weeks ago I gave a first demonstration of Siplicity for the [iPRES conference](https://ipres2024.pubpub.org/) (the "bake off" stream). Many thanks to Micky, Dries, and the rest of the conference team for including me in the program.

My presentation was unfortunately a little undercooked. Many of the ingredients were there, but without enough time in the coding oven, and so I focused the presentation on Siplicity's backend application (the GRPC server), which didn't make for an appetizing meal.  

OK, enough with the cooking puns! Here's the demo of Siplicity I would have liked to have given:

{{< image siplicity_2024-10-20.gif >}}Screencast of Siplicity application{{< /image >}}

In this screencast you can see that much of Siplicity's basic functionality is now implemented in the frontend.

The screencast demonstrates:

- adding files and folders to an input graph
- manipulating the input graph (select, delete and move nodes to the output graph)
- running processes like file format identification and checksum calculation to enrich record metadata
- viewing record details and metadata
- manipulating the output graph and defining an output destination
- formatting the output graph as a bagit package
- committing the output graph to disk.