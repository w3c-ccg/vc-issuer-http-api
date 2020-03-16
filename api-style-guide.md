# VC Issuer HTTP API Style Guide

This document is used to track design choices made in the development of [api.yml](./api.yml).

To the best of our ability we are attempting to follow [restfulapi.net](https://restfulapi.net/).

In cases where excessive optionality is allowed, or where consensus must needed to be reached are recorded, we will document our decisions here.

## API Versioning

We have decided to use HTTP Headers to version the API.

## Regarding Collections and Controllers

We are debating the appropriatness of both. See: [resource-naming](https://restfulapi.net/resource-naming/)