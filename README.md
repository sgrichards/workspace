# Workspace [![Build Status](https://travis-ci.org/my127/workspace.svg?branch=0.1.x)](https://travis-ci.org/my127/workspace)

Workspace is a tool to orchestrate and bring consistency to your project environments. 

## Documentation

### Getting Started
#### Requirements
 - `PHP-7.2+`
 - `sodium` php extension installed and activated in php.ini if it's not enabled by default 
 - `docker 17.04.0+`
 - `docker-compose (compose file version 3.1+)`
#### Installation
Download the `ws` file from the [Latest Release](https://github.com/my127/workspace/releases/latest) make executable and move to a location in your PATH, eg.
```
chmod +x ws && sudo mv ws /usr/local/bin/ws
```
#### Creating a workspace
```
# TODO
```
### Anatomy of a workspace

#### Key Concepts
 - [Workspace](docs/concepts/workspace.md)
 - [Harness](docs/concepts/harness.md)
 
#### Types

 - [Attribute](docs/types/attribute.md)
 - [Command](docs/types/command.md)
 - [Confd](docs/types/confd.md)
 - [Crypt](docs/types/crypt.md)
 - [Function](docs/types/function.md)
 - [Harness](docs/types/harness.md)
   - [Repository](docs/types/harness-repository.md)
 - [Subscriber](docs/types/subscriber.md)
 - [Workspace](docs/types/workspace.md)

#### Interpreters

 - [Bash](docs/interpreters/bash.md)
 - [PHP](docs/interpreters/php.md)
 
### Tutorials

 - [Creating a simple harness](docs/tutorials/create-harness.md)
