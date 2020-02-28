#  Verifiable Credential Issuer HTTP API Architecture Model
This document describes the architecture model and context for the Verifiable
Credential Issuer HTTP API.

## Overview
The Verifiable Credential Issuer HTTP API is designed to be a consistent API for
Issuer Services to call in order to generate Verifiable Credentials. This API is
intended for Issuer Services who are able to manage and secure external
connections to Holders. This API encapsulates and abstracts the Verifiable
Credential data model, format, and proof methods from Issuer Services. This API
also abstracts any underlying DID methods, resolver capabilities, and
cryptographic algorithms from the Issuer Services.

## Objectives
The following capture the objectives of this API.
1. Provide an open and consistent HTTP based API for Issuer Services to leverage   
