## Overview

This is an example.pubsub of how use the Java JMS api with Apollo.

## Prereqs

- Install Java SDK
- Install [Maven](http://maven.apache.org/download.html) 

## Building

Run:

    mvn install

## Running the Examples

In one terminal window run:

    java -cp target/stomp-example.pubsub-0.1-SNAPSHOT.jar example.pubsub.Listener

In another terminal window run:

    java -cp target/stomp-example.pubsub-0.1-SNAPSHOT.jar example.pubsub.Publisher

You can control to which stomp server the examples try to connect to by
setting the following environment variables: 

* `APOLLO_HOST`
* `APOLLO_PORT`
* `APOLLO_USER`
* `APOLLO_PASSWORD`
