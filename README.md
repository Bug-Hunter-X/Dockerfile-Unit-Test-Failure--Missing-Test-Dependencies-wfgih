# Dockerfile Unit Test Failure: Missing Test Dependencies

This repository demonstrates a common error in Dockerfiles: forgetting to install necessary dependencies for running unit tests. The provided `Dockerfile` attempts to run unit tests using `unittest`, but fails because the required testing libraries are not installed. The solution demonstrates how to correctly install these dependencies within the Dockerfile.