# Optimal Load Shape (OLS) data model and API

This repo includes machine readable files that define the OLS data model and API.

# YANG
The OLS YANG model describes entities and relationships that represent OLS data that may be provided
by an energy service provider and consumed by any energy load consumer. A YANG model does not define
a data interchange format, but tools exist to derive concrete NETCONF, REST, and gRPC bindings.

YANG models my be generated from sources such as UML or even SNMP MIB, In our case this simple model was
authored by hand.

To validate syntax of a yang model see: https://yangvalidator.org/yangvalidator/validator


# OpenAPI
Included here is a JSON file that is an OpenAPI definition of a REST API derived from the OLS YAMG model.

To convert yang to OpenAPI see: https://dave.dev/blog/2018/10/yang-openapi-swagger-code-generation/
