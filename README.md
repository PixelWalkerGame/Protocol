# PixelWalker Protocol

## Introduction
PixelWalker uses [Protocol Buffers v3](https://protobuf.dev/programming-guides/proto3/) for communication between the client and game server. You can use the `.proto` file in this repository to generate classes for your programming language of choice.

In addition, we have volunteer community members who maintain unofficial SDKs in a variety of programming languages that can also interface with the game. Using an existing SDK is typically easier for those who are learning how to program, as the foundation is built for you, such as built-in user and block management, and other features. Please join our [Discord server](https://discord.com/invite/rDgtbbzDqX) to learn more about what the community has to offer! Please keep in mind that these third party SDKs are not vetted by the PixelWalker team, and that they should be used at your own risk. (Always check the source code of any application before providing your credentials or authentication tokens!)

## Useful Resources
### Blocks
If you're looking for all the block palette mappings, please see the [mappings endpoint](https://server.pixelwalker.net/listblocks) from the game server. This can be referenced in your program so you always have the most up-to-date mappings, as numerical block ids are subject to change and should not be used in persistent storage. In addition, palette ids are subject to change as well, but those changes are posted in our [Discord server](https://discord.com/invite/rDgtbbzDqX) for the developer community.
### Help
If you'd like help with your program and to connect with the community, please join our [Discord server](https://discord.com/invite/rDgtbbzDqX).
### Community Resources
The majority of community resources are in the pinned #programming channel on the Discord server, but a notable resource to utilize API endpoints is the [PixelWalker Swagger API](https://piratux.github.io/PixelWalker-Api/) maintained by Piratux, a community member.
