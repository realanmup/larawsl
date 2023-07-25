**Installation Guide for larawsl**

To install `larawsl` on your Ubuntu 22.04 running in Windows Subsystem for Linux (WSL), follow these steps:

1. Open a terminal in your Ubuntu 22.04 WSL.

2. Run the following command to download and execute the installer script from the public GitHub repository:

   ```bash
   curl -sSfL https://raw.githubusercontent.com/realanmup/larawsl/main/larawsl | bash
   ```

   The `curl` command will fetch the `larawsl` script from the public GitHub repository and pipe it to `bash` to execute it directly.

3. The installer script will prompt you for your password (if required for administrative privileges) and proceed to install `larawsl` along with the required components, including PHP 8.1, extensions, additional apt services, and Node.js 16.

4. Once the installation is complete, you can start using `larawsl` to manage your development environment on Ubuntu 22.04.

Please note that running scripts directly from the internet may have security implications. Always review the script source before executing it. The `larawsl` script in the GitHub repository is an open-source script provided under the MIT License.

If you encounter any issues or have questions regarding the installation, feel free to report them on the [GitHub repository](https://github.com/realanmup/larawsl). Additionally, please adhere to the project's Code of Conduct when interacting with the community.

Enjoy using `larawsl` for your development environment setup! Happy coding!