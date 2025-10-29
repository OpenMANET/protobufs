# OpenMANET Protobuf Definitions

## Overview

The [Protobuf](https://developers.google.com/protocol-buffers) message definitions for the OpenMANET project.

The protobuf messages are used with [Alfred](https://www.open-mesh.org/projects/alfred/wiki) to publish low level information within the batman-adv network used by OpenMANET.

>alfred is a user space daemon for distributing arbitrary local information over
the mesh/network in a decentralized fashion. This data can be anything which
appears to be useful - originally designed to replace the batman-adv
visualization (vis), you may distribute hostnames, phone books, administration
information, DNS information, the local weather forecast...

## Use Case
Protobufs are a language neutral way of defining an API specification used to perform low level data syncronization across the OpenMANET mesh.

>It’s like JSON, except it’s smaller and faster, and it generates native language bindings. You define how you want your data to be structured once, then you can use special generated source code to easily write and read your structured data to and from a variety of data streams and using a variety of languages.