# Fujitsu Enterprise Postgres with Cryptographic Operator Helm Chart description

This Helm Chart makes it easy to deploy Fujitsu Enterprise Postgres with Cryptographic Module Operators in a Kubernetes environment.

# How to deploy the FEP Operator

```
    # helm repo add fep-repo https://fujitsu.github.io/fep-operator-helm-with-cryptographic-module/v1 
    # kubectl create namespace fep-operator
    # helm install fep-operator-release fep-repo/fujitsu-enterprise-postgres-operator --namespace fep-operator
```

# About clients

Fujitsu Enterprise Postgres clients can be downloaded from the [Fujitsu Enterprise Postgres with Cryptographic Module client - download](https://www.postgresql.fastware.com/fujitsu-enterprise-postgres-cg-client-download) page.

For details on how to install the client, refer to the [Installation and Setup Guide for Client](https://www.postgresql.fastware.com/hubfs/_Global/Manuals/FEP-v15SP2forx86-InstallationAndSetupGuideForClient.pdf) manual.

# License information

Please note that the Fujitsu Enterprise Postgres with Cryptographic Module Operator installed with this Helm Chart must be purchased and use a product license.
