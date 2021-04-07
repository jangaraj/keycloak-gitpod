# Keycloak in the Gitpod

Click on this badge [![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/jangaraj/keycloak-gitpod) and your own Keycloak server will be running within 1-2 minute.

Keycloak server in Gitpod - setup for developers, who want to have quick base setup of the Keycloak. Default admin credentials `admin/password`.

Gitpod env variables and their default values (can be modified in the Gitpod URL - [example Gitpod URL](https://gitpod.io/#IMAGE=jboss/keycloak:12.0.4,KEYCLOAK_USER=admin,KEYCLOAK_PASSWORD=password,KEYCLOAK_STATISTICS=all/https://github.com/jangaraj/keycloak-gitpod)):

```
IMAGE=quay.io/keycloak/keycloak:12.0.4
KEYCLOAK_USER=admin
KEYCLOAK_PASSWORD=password
KEYCLOAK_STATISTICS=all
KEYCLOAK_LOGLEVEL=INFO
JAVA_OPTS_APPEND="-Dkeycloak.profile.feature.upload_script=enabled -Dkeycloak.profile.feature.scripts=enabled -Dkeycloak.profile.feature.account2=enabled -Dkeycloak.profile.feature.account_api=enabled"
```

Description of some env variables is available on https://hub.docker.com/r/jboss/keycloak/
