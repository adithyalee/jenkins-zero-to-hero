# Jenkins Zero to Hero

My notes and setup from learning Jenkins.

- `Dockerfile` builds a Jenkins LTS (JDK 17) image with the Docker CLI and the Blue Ocean and Docker Pipeline plugins.
- `helloworld.py` is the script my first pipeline job runs.

```bash
docker build -t my-jenkins .
docker run -p 8080:8080 -v /var/run/docker.sock:/var/run/docker.sock my-jenkins
```
