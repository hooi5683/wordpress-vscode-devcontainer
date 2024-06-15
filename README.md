# wordpress-vscode-docker
This is a VSCode devcontainer boilerplate that enables developers to run and develop WordPress projects in a Docker container.

## Why Use This?
To resolve performance issues in WordPress when setting up by simply binding the \wp-content directory to a physical folder.

## How It Works
[Volume]
* The folder `/var/www/html` is bound to a Docker volume.
* This folder is accessible from Windows Explorer at the path: `\\wsl.localhost\docker-desktop-data\data\docker\volumes\wordpress-docker-template_wordpress-data\_data`
 
[Use Cases]
* You can set up a git repository in the folder `\\wsl.localhost\docker-desktop-data\data\docker\volumes\wordpress-docker-template_wordpress-data\_data\wp-content\plugins` to develop your plugin and more.
