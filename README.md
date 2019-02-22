# dockerfiles

This repository contains dockerfiles used in BeSpunky projects and are shared with the community.

Every file here represents a docker image on [Docker Hub](https://hub.docker.com/u/bespunky).
Dockerfiles have the same name as the docker image and do not include the `dockerfile` word in order to easily match the image names.

## Usage

Find the name of the image you are interested in and use it in your `FROM` statement.
```dockerfile
FROM bespunky/<dockerfile name>[:tag]
```

## Example

```dockerfile
FROM bespunky/microsoft-dotnet-sdk-angular-ready
```
