---
layout: page
title: About
hideLogo: true
permalink: /about/
---

Mikudos is a micro service Framework with a set of micro services in structure of micro-service + grpc + kubernetes(istio + helm deploy) + docker.

#### The Name MiKudos means Micro service + Kubernetes + Docker.

The name shows the base archtechture of this framework. The Core Idea of us is build several micro services Templates as start point for you to easy getting start with the Micro services infrastracture. The Internal communication use [Grpc standart](https://grpc.io), designed by [Google](https://google.com), as a powerful method to dist the Send package and easy to use Remote Procedure Call for Unify or Duplex stream message. You could use Mikudos to generate a start Point for Grpc server with Several programming Language. With the power of Grpc and kubernetes, we want provide defferent templates to satisfy all different business type, such as: e-commerce, online-game.

#### Command Line Tools

The command line tools lived with [node.js](http://nodejs.org/) and [npm](https://www.npmjs.com/)/[Yarn](https://yarnpkg.com). You need to install them first.

#### [Grpc service]({{ site.baseurl }}/grpc-server/)

Grpc service template are build in many defferent language, they have different dependencies the detail can be finded with these Links:

[Grpc server in Javascript]({{ site.baseurl }}/grpc-server/javascript/)

[Grpc server in Typescript]({{ site.baseurl }}/grpc-server/typescript/)

[Grpc server in Python]({{ site.baseurl }}/grpc-server/python/)

[Grpc server in Java]({{ site.baseurl }}/grpc-server/java/)

[Grpc server in C#]({{ site.baseurl }}/grpc-server/c#/)

[Grpc server in c++]({{ site.baseurl }}/grpc-server/c++/)

[Grpc server in ruby]({{ site.baseurl }}/grpc-server/ruby/)
