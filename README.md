# Node-RED Installation and Usage Guide for Windows

This guide provides step-by-step instructions for installing and using Node-RED on a Windows operating system.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Starting Node-RED](#starting-node-red)
- [Accessing the Node-RED Dashboard](#accessing-the-node-red-dashboard)
- [Using Node-RED](#using-node-red)
- [Stopping Node-RED](#stopping-node-red)
- [Troubleshooting](#troubleshooting)

## Prerequisites

Before installing Node-RED, ensure that you have the following software installed:

- **Node.js**: Node-RED requires Node.js to run. Download and install the latest LTS version of Node.js from [nodejs.org](https://nodejs.org/).
- **npm**: Node.js comes with npm, the Node Package Manager, which will be used to install Node-RED.

## Installation

1. Open a Command Prompt window (you can do this by pressing `Win + R`, typing `cmd`, and hitting `Enter`).

2. Verify that Node.js and npm are installed correctly by running:
   You should see version numbers for both commands.
   ```bash
   node -v
   npm -v
3. Install Node-RED globally using npm:
    ```bash
    npm install -g --unsafe-perm node-red
    
4. After installation, verify Node-RED is installed by checking the version:
   ```bash
   node-red -v

## Starting Node-RED
To start Node-RED, run the following command in your Command Prompt:
   ```bash
   node-red
