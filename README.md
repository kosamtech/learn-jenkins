## Learn Jenkins Pipeline as Code

### Using Git, Github, Docker and Deploying to AWS

- DevOps is a set of practices, tools and cultural philosophies designed to improve collaboration and effeciency between software development (Dev) and IT operations (Ops) team
- Jenkins is an automation server

### Gain the following
* Foundational Knowledge
* Hands on Experience
* Continous Integration Mastery
* Deployment to AWS

### Getting Started
To build the jenkins image run the following command

```bash
docker build -t my-jenkins .
```

To start the jenkns server in a container environment run the following command

```bash
docker compose up -d
```

To tear down or shutdown the jenkins server, run the following command

```bash
docker compose down
```

Optionally to get rid of the volume associated with the jenkins container, run the following command

```bash
docker compose down -v
```