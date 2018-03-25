# sonic-telemetry

**Note:** Official development for SONiC-telemetry has moved to [sonic-telemetry](https://github.com/Azure/sonic-telemetry)

## Description
This repository contains implementation for the sonic system telemetry services:
- dial-in mode system telemetry server: `telemetry`
- dial-out mode system telemetry client `dialout_client_cli`

## Getting Started

### Prerequisites

Install __go__ in your system https://golang.org/doc/install. Requires golang1.8+.

## Installing

To install dial-in mode system telemetry server, run

    go get -u github.com/jipanyang/sonic-telemetry/telemetry

To install dial-out mode system telemetry client, run

    go get -u github.com/jipanyang/sonic-telemetry/dialout/dialout_client_cli

There is also a test program dialout_server_cli for basic testing of collecting data from dial-out mode system telemetry client.

    go get -u github.com/jipanyang/sonic-telemetry/dialout/dialout_server_cli

## Running
* See [SONiC gRPC telemetry](./doc/grpc_telemetry.md) for how to run dial-in mode system telemetry server
* See [SONiC telemetry in dial-out mode](./doc/dialout.md) for how to run dial-out mode system telemetry client