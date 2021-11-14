# docker_example1

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

# Containerizing Flutter-web App with Docker
Run the following commands to build and run the image.
```
docker build . -t flutter_docker
```
```
sudo docker run -i -p 8080:5000 -td flutter_docker
```
Dockerfile and server\.sh was taken from [this link](https://blog.logrocket.com/containerizing-flutter-web-apps-with-docker/)