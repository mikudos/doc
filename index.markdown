---
subtitle: Mikudos
sections:
    - section_id: hero
      component: hero_block.html
      type: heroblock
      image: assets/images/hero.png
      title: Micro service framework
      content: >-
          Mikudos is build on top of micro-service + grpc + kubernetes(istio + helm deploy) + docker.
      actions:
          - label: Learn More
            url: /about
    - section_id: build_blocks
      component: building_block.html
      type: reviewsblock
      bg: white
      title: Building Blocks
      subtitle: >-
          Mikudos has several different part provided for user to build their micro services server: Client Gate Grpc-Server Plugin(Grpc-Service) Generator
      reviews:
          - author: JS / TS
            title: >-
                Gate
            mark: https://img.shields.io/badge/MIKUDOS-Gate-blue?style=for-the-badge&logo=appveyor
            link: /gate/
            content: >-
                Gate works as front-end service. Gate handle normal client side connections and requests, and handle these request or transit them to the back end service. We want to provide Gate template, which can work as general server for both normal Business or Game server.
          - author: JS / TS / PYTHON / GOLANG / RUBY / C++ / C#
            title: >-
                Grpc-server
            mark: https://img.shields.io/badge/MIKUDOS-GRPC--server-lightgrey?style=for-the-badge&logo=appveyor
            link: /grpc-server/
            content: >-
                Grpc server sind templates for easy implemention of the Grpc methods. The Grpc server take the .proto file as service description, and make a docker container starter with implementation of all the service methods. Different grpc services communicate with other services or containers with grpc-call and kafka as event broker.
          - author: RBAC & Schedule & EventAggregate
            title: >-
                Plugin
            mark: https://img.shields.io/badge/MIKUDOS-Plugin-orange?style=for-the-badge&logo=appveyor
            link: /plugins/
            content: >-
                Plugins work as single independent docker container. The Plugins can be used neben by the other Mikudos service. We want to provide a lot of different Plugins to auto finish your Jobs. We just want to help these independent Developers to use their spare time to make their Gaint Ideas come true.
          - author: \@mikudos/cli
            title: >-
                Generator
            mark: https://img.shields.io/badge/MIKUDOS-Generator-brightgreen?style=for-the-badge&logo=appveyor
            link: /genrator/
            content: >-
                Mikudos generator is write in node.js.
          - author: Richard Roe
            title: >-
                Deployment
            mark: https://img.shields.io/badge/MIKUDOS-Deployment-ff69b4?style=for-the-badge&logo=appveyor
            link: /deployment/
            content: >-
                Integer consectetur purus neque, ac porttitor enim convallis vitae.
                Interdum et malesuada fames ac ante ipsum primis in faucibus.
layout: home
---

Mikudos is a micro service Framework with a set of micro services in structure of micro-service + grpc + kubernetes(istio + helm deploy) + docker.

Mikudos just want to do all the dirty things, which waste your time and block your way.
