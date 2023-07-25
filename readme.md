**larawsl - Development Environment Setup Script for Ubuntu 22.04 (WSL)**

![larawsl Logo](https://raw.githubusercontent.com/realanmup/larawsl/main/larawsl.png) 

**Overview**

larawsl is a convenient shell script designed to simplify the setup of development environments on Ubuntu 22.04 running in Windows Subsystem for Linux (WSL). This script automates the installation of essential tools and services commonly used in web development, making it easier for developers to kickstart their projects without spending time on manual configurations.

**Features**

- Installs PHP 8.1 with commonly used extensions (bcmath, mbstring, curl, xml, zip, mysql, pgsql, imagick, redis, gd, gmp, mongodb, and sqlite3).
- Sets up Nginx, Redis, and MySQL as well as PHP-FPM to enable smooth web development workflows.
- Includes Composer, Node.js 16, npm, and n (Node.js version manager) for efficient package management.
- Sets up phpMyAdmin for easy database management and interaction.
- Provides a simple and intuitive command-line interface to start, stop, and check the status of installed services.
- Comes with detailed installation logs for better visibility into the setup process.

**Usage**

Using larawsl is straightforward. Simply download the `larawsl.sh` script and run it in your Ubuntu 22.04 WSL environment. The script will handle the installation of all the required components, and you'll have a fully functional development environment in no time.

**Installation**

To install larawsl, open a terminal in your Ubuntu 22.04 WSL and run the following command:

```
curl -sSfL https://raw.githubusercontent.com/realanmup/larawsl/main/larawsl | bash
```

For more detailed instructions, refer to the [Installation Guide](https://github.com/realanmup/larawsl/blob/main/Installation.md).

**Contribution**

We welcome contributions from the community! If you encounter any issues or have ideas to improve larawsl, feel free to submit a pull request or open an issue on our [GitHub repository](https://github.com/realanmup/larawsl). Please read our [Contribution Guidelines](https://github.com/realanmup/larawsl/blob/main/CONTRIBUTING.md) and [Code of Conduct](https://github.com/realanmup/larawsl/blob/main/CODE_OF_CONDUCT.md) before getting involved.

**License**

larawsl is open-source software distributed under the [MIT License](https://github.com/realanmup/larawsl/blob/main/LICENSE.md). By using, modifying, or contributing to this project, you agree to be bound by the terms of the license.

**Support**

If you have any questions or need assistance with larawsl, you can reach out to us on [GitHub Discussions](https://github.com/realanmup/larawsl/discussions) or contact the project maintainers at [email address].

Let larawsl streamline your development environment setup and empower you to focus on building amazing projects with ease! Happy coding!
