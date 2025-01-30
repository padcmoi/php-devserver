# Node Development Server

## Short Description
This is an environment for developing any PHP application.


## Why?
This container allows you to have a version of PHP without installing PHP locally. Any PHP application can run on it, including frameworks like Symfony, Laravel, Slim, etc.


## Installation
1. Copy the `docker/.env.example` file to `.env` and modify it as needed, such as setting the desired Node.js version.
2. In the `app` folder, the content is an example. Place your project inside.
3. Use the following Docker commands:
    - `docker/create_env.sh`: To configure your environment and remove unnecessary files including folder .git
    - `docker/version`: To select a PHP version, for example, `7.2`, `5.4`, or `8.2`
    - `docker/exec`: To execute a command in the container
    - `docker/log`: To get real-time logs
    - `docker/restart`: To rebuild and restart the container
    - `docker/start`: To build and start the container
    - `docker/stop`: To stop and remove the unused container

**NOTE:** It is possible to add a PHP version to the commands `docker/restart 7.2` and `docker/start 7.2`, this is optional.

And that's it, very simple.


## Contact me

- Julien Jean
- France
- [By discord](https://discord.gg/257rUb9)