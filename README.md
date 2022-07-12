# Proto

This document describes tools and workflows necessary to get started working on the Polar Signals' protobuf definitons.

## Prerequisites

We'll need a couple of tools to spin up the dev environment. Make sure they are installed by running the `env-proto.sh` script.

Use `make proto-install` to install necessary 3rd party proto dependecies to generate necessary server and client code.

## Generate

Use `make proto` to generate server-side Go code.