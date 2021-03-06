A [Giter8][g8] template for Akka HTTP in Scala

Prerequisites:
- JDK 8
- sbt 0.13.13 or higher

Open a console and run the following command to apply this template:
 ```
sbt -Dsbt.version=0.13.15 new https://github.com/akka/akka-http-scala-seed.g8
 ```

This template will prompt for the following parameters. Press `Enter` if the default values suit you:
- `name`: Becomes the name of the project.
- `scala_version`: Specifies the Scala version for this project.
- `akka_http_version`: Specifies which version of Akka HTTP should be used for this project.
- `akka_version`: Specifies which version of Akka should be used for this project.
- `organization`: Specifies the organization for this project.

The template comes with the following sources:

* `UserRegistryActor.scala` -- the actor which handles the registration requests.
* `UserRoutes.scala` -- Akka HTTP `routes` defining exposed endpoints.
* `QuickstartServer.scala` -- the main class which combines Akka HTTP `routes` with the actor to run HTTP server.
* `JsonSupport.scala` -- converts the JSON data from requests into Scala types and from Scala types into JSON responses.

Once inside the project folder use the following command to run the code:
```
sbt run
```

Template license
----------------
Written in 2017 by Lightbend, Inc.

To the extent possible under law, the author(s) have dedicated all copyright and related
and neighboring rights to this template to the public domain worldwide.
This template is distributed without any warranty. See <http://creativecommons.org/publicdomain/zero/1.0/>.

[g8]: http://www.foundweekends.org/giter8/
