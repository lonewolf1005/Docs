# Project Lifeline

### What is project lifeline?
The aim of this project is to build a distributed CoWIN polling system so that we can expand slot opening notifications to the entire country at once with extremely high update frequencies. The main issue most developers like us are having with expanding to the whole country is scalability due to costs, therefore by developing a distributed system, so that public can help poll data, it will help us expand easily and achieve extremely high polling frequencies.

### Community 
You can join the discord server [here](https://discord.gg/HuFApqaz5F) and join the conversation.

## How do I contribute?

### Fork the project. 

### How do you get your environment setup?

#### Install

- [Go>=1.16](https://golang.org/doc/install)
- [Protobuf](https://developers.google.com/protocol-buffers/)
  - Follow instruction the gRPC guide [here](https://grpc.io/docs/languages/go/quickstart/) to install

#### 

#### Install dependencies
- `go mod download`

### Run
- `go run Main/main.go`

#### Connecting and testing locally
I would recommend using tools such as [evans](https://github.com/ktr0731/evans) to connect to the server and test it out as it is a gRPC project and so tools such as `Postman` will not work.

### About
This project uses the [gRPC](https://grpc.io) framework on [Go](http://golang.org) to communicate between the servers.

#### Architecture
![img.png](ReadmeImages/systems_architecture.png)

---

