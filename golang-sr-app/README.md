# Demo SR-App - Golang

This is a small demo SR-App to demonstrate the usage of the Jalapeño API Gateway (JAGW).

## Prerquisites

To run this application your setup must meet the following conditions:

- You have setup a running instance of both **Jalapeño** as well as the **Jalapeño API Gateway** and your local machine can reach the request service of the JAGW.
- You have installed [Golang](https://golang.org/doc/install) version 1.16 or higher on your local machine.

## Usage

1. Clone this repository

```bash
$ git clone git@github.com:jalapeno-api-gateway/sample-sr-apps.git
```

2. Change to this directory and start the application (providing the server address and port of your JAGW instance)

```bash
$ cd sample-sr-apps/golang-sr-app
$ go run main.go <server-address> <request-service-port>
```

## Output

This demo app will request all nodes from the Jalapeño framework and print them to the console.
