<p align="center"><a href="https://giveth.io"><img alt="Giveth.io" src="https://github.com/Giveth/giveth-design-assets/blob/master/02-logos/Giveth%20logo/giveth-symbol-logo-purple.png" width="80"/></a></p><h1 align="center">
  Giveth v2
</h1>

## 🚀 Quick start
Giveth-2 is a reimagined version of the ["Giveth donation application"](https://github.com/Giveth/giveth-dapp). Users leverage the Ethereum blockchain to distribute and track their donations or enable unstoppable funding for their campaign.

1.  **Create a Gatsby site.**
The projects aims to simplify the application's options to enable new users without blockchain experience a frictionless experience.

The project is currently in heavy development and does not offer all functionality that is needed for an MVP state (first release goal).

If you want to contribute, pls say hello to us in chat -  [https://giveth.io/join](https://giveth.io/join)

###### Uses
- Gatsby
- Apollo GraphQL
- Tor.us
- Theme UI

## Contributor's guide

1.  **Clone and install the backend server**

    In order to develop locally you need to clone the backend server as well. We are using https://github.com/topiahq/impact-graph for this. Please follow the readme of `impact-graph` to install it. For more detailed instructions specific to giveth2 please refer to this [gist](https://gist.github.com/geleeroyale/6283549c469f2fa89fc059f936c59002).

1.  **Clone and install the frontend (this repo)**
	First, please star and follow this repository.
	```bash
	git clone git@github.com:Giveth/giveth-2.git
	cd giveth-2
	npm i
	```
    
1.  **Set up the development environment**
	
	```bash
	cp .env.example .env.development
	```
	To get the necessary information for local development, please [ask in giveth-2 developer chat](https://riot.im/app/#/room/!zFyfjCfKHawjZJcueK:matrix.org?via=matrix.org)

1.  **Start developing.**
	Make sure that the backend server is running (Step1)
    Navigate into the giveth-2 directory and start up the local development server.

    ```shell
    gatsby develop
    ```

1.  **Open the source code and start editing!**

    Your site is now running at `http://localhost:8000`!

    _Note: You'll also see a second link: _`http://localhost:8000/___graphql`_. This is a tool you can use to experiment with querying your data. Learn more about using this tool in the [Gatsby tutorial](https://www.gatsbyjs.org/tutorial/part-five/#introducing-graphiql)._
    
    Save your changes and the browser will update in real time!

1. **TODO Gitflow and contributor guidelines**
