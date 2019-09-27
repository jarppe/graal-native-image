# Docker image based on oracle/graalvm-ce:latest with native-image installed

Dockerfile is:

```dockerfile
FROM oracle/graalvm-ce:latest
RUN gu install native-image
```

You get the idea.

# License

Copyright © 2019 Jarppe Länsiö

Distributed under the Eclipse Public License either version 1.0 or (at your option) any later version.
