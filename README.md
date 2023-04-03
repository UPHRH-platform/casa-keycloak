Note
-----
Providers are picked from `providers` folder which is built using this repo -> https://github.com/UPHRH-platform/casa-keycloak-storage-provider

Keycloak
========

To get help configuring Keycloak via the CLI, run:

on Linux/Unix:

    $ bin/kc.sh

on Windows:

    $ bin\kc.bat

To try Keycloak out in development mode, run: 

on Linux/Unix:

    $ bin/kc.sh start-dev

on Windows:

    $ bin\kc.bat start-dev

After the server boots, open http://localhost:8080 in your web browser. The welcome page will indicate that the server is running.

To get started, check out the [configuration guides](https://www.keycloak.org/guides#server).
