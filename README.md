# Project Lifeline

### What is Project Lifeline?
The aim of this project is to build a distributed CoWIN polling system so that we can expand slot opening notifications to the entire country at once with extremely high update frequencies. The main issue most developers like us are having with expanding to the whole country is scalability due to costs, therefore by developing a distributed system, so that public can help poll data, it will help us expand easily and achieve extremely high polling frequencies.

### Community 
You can join the discord server [here](https://discord.gg/HuFApqaz5F) and join the conversation.

## How do I contribute?

## Let's set your environment up first?

#### Installing the requirments
- [Go>=1.16](https://golang.org/doc/install)
  - Folow the instructions given in the link to install Go.
- [Protobuf](https://developers.google.com/protocol-buffers/)
  - Follow instruction the gRPC guide [here](https://grpc.io/docs/languages/go/quickstart/) to install 

#### Fork the project
- Click on the `Fork` button on the top right of the repository that you want to contribtue to, and select your organization(or your account). This will create a copy of the repository under your account. 
- Clone the project to your local machine 
  - Using CLI 
    `git clone https://github.com/github-username/repository-name.git`
  - Using an IDE (My preffered IDE for GoLang development is GoLand and the instructions given below are for GoLand, but the steps should be similar to all other IDEs out there) (
    - Click on `Get from VCS`
    - Select version control as `Git`
    - Enter the URL of the repo that you forked 
      - For example: `https://github.com/github-username/repository-name.git`
    - Click `Clone`

#### Install dependencies
Once you have clone the repository locally, naviate to that folder and run `go mod download` to downlaod the required dependencies for the repository

### Run
You can run the repos in this project with the `go run main.go`

#### Connecting and testing locally
I would recommend using tools such as [evans](https://github.com/ktr0731/evans) to connect to the server and test it out as it is a gRPC project and so tools such as `Postman` will not work. 
- Install evans by following the instructions on their GitHub repo. 
- You can connect to the server using the following command `evans foo.pb`.
- Call an RPC endpoint using the following command `call EndpointName`,
- For more information on how to use evans, please read the README on their GitHub.

Lastly there are no unit tests at the moment and as we add them, I will update the instructions for the same.

## What do I contribute to?
There 
