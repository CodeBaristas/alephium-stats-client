# alephium-stats-client

## Overview

The alephium-stats-client repository serves as a Proof of Concept demonstrating the basic functionalities and structure of the backend system, which is responsible for serving data and handling requests from the client application.

This repository showcases how to interact with the backend system and provides examples of how to utilize the endpoints exposed by the backend.

## Getting Started

To generate the client, follow these steps:

1. Navigate to the root backend directory.
2. Ensure all necessary dependencies are installed (poetry, lets, openapi-generator-cli)
3. Use the command `lets client` to generate the client.

## Open Endpoints

All open endpoints and their functionalities can be found in the [documentation](https://alephiumstatsapi.alph.land/docs). These endpoints are accessible without authentication and serve as the entry points for interacting with the backend. Since this is only a proof of concept, the system is designed to be easily extensible. You can add new endpoints to fulfill additional functionalities as needed.

Open endpoints are accessible without authentication and serve as the entry points for interacting with the backend. You can find detailed information about these endpoints and their functionalities in the documentation.
These endpoints are designed to be easily extensible, allowing for the addition of new endpoints to fulfill additional functionalities as needed.

## Additional Resources

- [Backend](https://github.com/CodeBaristas/alephium-stats-backend) Repository: Link to the backend repository for further reference.
- [documentation](https://alephiumstatsapi.alph.land/docs): Detailed documentation of the backend API endpoints.
