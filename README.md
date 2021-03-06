# Product-Details_proxy
MountainCrow is a full stack application that displays various products with their details, descriptions, and reviews. The goal of the application was to focus on deployment and scalability. Each component of the application was separately scaled and load-balanced using AWS EC2 instances and NGINX.

This repository particularly focuses on the proxy server that connected all three horizontally scaled components of the application. The proxy server is the culmination of the single page application.

## Related Projects

  - https://github.com/MountainCrow/product_details
  - https://github.com/MountainCrow/Product-description-service
  - https://github.com/MountainCrow/reviews

## Table of Contents

1. [Requirements](#requirements)
1. [Development](#development)


## Requirements

An `nvmrc` file is included if using [nvm](https://github.com/creationix/nvm).

- Node 6.13.0
- npm 
- AWS

### Installing Dependencies

From within the root directory:

```sh
npm install 
```
## Development

To Run Server

```sh
npm start
```
