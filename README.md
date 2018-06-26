# Zoom API using JWT

> This is a sample app that uses JWT to call Zoom's API. It also uses the request-promise node module to make http calls with Promises. 

## Getting Started

### Install

You can install using git clone

` git clone https://github.com/zoom/zoom-api-jwt.git`

### Quick Start

> Install the dependent node modules
``` npm install ```

> In the config.js file, input your client API Key & Secret credentials.
``` const config = {
	production:{	
		APIKey : 'Your environment API Key',
		APISecret : 'Your environment API Secret'
	}
    };
```
> Set your environment varaibles
``` export NODE_NEV=[environment name] (e.g. export NODE_NEV=production) ```

> Start the node app using the below command.
``` node.index.js ```
