+++
title = "Tech stack overview"
date = 2024-09-15T12:00:00+10:00
draft = false
+++

Siplicity has a backend written in [Go](https://golang.org). I chose Go mainly because I am familiar with it but can justify the choice on the basis that it is cross-platform, reasonably performant, and enables native integration with [Siegfried](https://www.itforarchivists.com/siegfried).

The frontend is [Flutter](https://flutter.dev). This framework is best known for mobile UIs but it now has good desktop and web support too. It is modern, performant, and native-feeling.

The backend and frontend communicate via [gRPC](https://grpc.io). I've been using the [Buf](https://buf.build/) tooling for this.

I am focused on creating a local, client application but a benefit of this mix of go/flutter/grpc is that it opens the door to other potential deployment scenarios, including local client (native or browser) with a cloud backend (e.g. an AWS machine in the same region as your cloud storage). 