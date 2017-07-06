<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### Table of Contents

-   [Discovery](#discovery)
    -   [constructor](#constructor)
    -   [getAll](#getall)
    -   [get](#get)
-   [services](#services)
    -   [handler](#handler)
    -   [router](#router)
    -   [broker](#broker)

## Discovery

Discovery is a client for The Things Network discovery API

**Parameters**

-   `opts` **Options**  (optional, default `{}`)

### constructor

Create a new Discovery client.

**Parameters**

-   `opts` **Options**  (optional, default `{}`)

### getAll

getAll returns announcements for all services known to
the discovery server that match the service name.

**Parameters**

-   `serviceName` **service** The name of the services to look for, eg. "handler"

### get

get returns the announcement for the service with the
specified service name and id.

**Parameters**

-   `serviceName` **service** The name of the services to look for, eg. "handler"
-   `id` **[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)** The id of the service to look for, eg. "ttn-handler-eu"

## services

services is a map with the known service names for the discovery server.

### handler

handler is a Handler service

### router

router is a Router service

### broker

broker is a Broker service