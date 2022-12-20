# Twelve-Factor App Checklist

A checklist for the [Twelve-Factor App](http://12factor.net/) methodology.

## I. Codebase

### One codebase tracked in revision control, many deploys

- [ ] There is one repository for the codebase.
- [ ] The codebase is tracked in revision control, such as Git.
- [ ] There is one codebase for the production deploy and for any other deploys of the app.

## II. Dependencies

### Explicitly declare and isolate dependencies

- [ ] Dependencies are declared, such as with a requirements.txt file for Python.
- [ ] Dependencies are isolated, such as with pip, virtualenv, or Docker.

## III. Config

### Store config in the environment

- [ ] Configuration that varies between deploys, such as API keys, are stored in the environment.

## IV. Backing services

### Treat backing services as attached resources

- [ ] Backing services, such as databases and queues, are treated as attached resources.

## V. Build, release, run

### Strictly separate build and run stages

- [ ] Build, release, and run stages are clearly separated.
- [ ] Build and run stages are repeatable, such as with script or Dockerfile.

## VI. Processes

### Execute the app as one or more stateless processes

- [ ] The app is executed as one or more stateless processes.
- [ ] The app is executed as one or more stateless processes.
- [ ] The app's state is stored in a stateful backing service, such as a database.

## VII. Port binding

### Export services via port binding

- [ ] The app is executed by a web server, such as Nginx, and the web server is bound to a port.

## VIII. Concurrency

### Scale out via the process model

- [ ] Concurrency is achieved by scaling out via the process model.
- [ ] Each process is completely disposable, such as with Docker.

## IX. Disposability

### Maximize robustness with fast startup and graceful shutdown

- [ ] Processes shut down gracefully, such as with a SIGTERM signal in Linux.
- [ ] Processes start up quickly.

## X. Dev/prod parity

### Keep development, staging, and production as similar as possible

- [ ] Development, staging, and production environments are as similar as possible.
- [ ] Development, staging, and production environments are as similar as possible.
- [ ] Development, staging, and production environments are as similar as possible.

## XI. Logs

### Treat logs as event streams

- [ ] Logs are treated as event streams.

## XII. Admin processes

### Run admin/management tasks as one-off processes

- [ ] Admin/management tasks are executed as one-off processes, such as with `docker-compose run`.
