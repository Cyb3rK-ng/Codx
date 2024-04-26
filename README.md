# Codx Configuration Script

Welcome to the Codx Configuration Script! This repository contains a Python script that configures a Custom Setting for the Codetantra application, enabling secure connections and other advanced functionalities. The script automates the setup process, verifies a provided software key, and handles other tasks such as downloading plugin files and installing certificates.

## Features

- **Custom Configuration**: Automates the setup and deactivation of the Custom settings for Codetantra.
- **Internet Connection Check**: Checks if the system is connected to the internet before proceeding.
- **Download Plugin File**: Downloads and updates the plugin file from a specified URL.
- **Certificate Installation**: Guides the user through installing the required certificates for secure connection.
- **Automated Management**: Manages the running of a subprocess to handle codx-related tasks.
- **Regulatory Compliance**: Updates and manages the Windows Registry keys for personal settings.
- **Allow Window Switching**: Enables switching between windows while in the exam panel of Codetantra.
- **Enable Copy-Paste**: Allows copy-paste functionality in the Codetantra Exam panel.
- **Open All Daily Practice Questions**: Opens all daily practice questions in Codetantra.
- **Remove Other Security Settings**: Removes other security settings from the Codetantra application.

## Manual

To use this script, follow the steps below:
1. **Download the Program**: Download the latest release executable from the [releases page](https://github.com/ck-cyberking/Codx/releases) and save it to your local machine.

2. **Run the Program**: Locate the downloaded executable file and run it ( Only `Codx.exe` ). You can do this by double-clicking the file `Codx.exe` in your file explorer.

3. **Follow Instructions**: The program will guide you through the Custom setup process and certificate installation. Follow the on-screen instructions.

4. **Enter Software Key**: If it's the first time running the script, you will be prompted to enter your software key. Enter the key you received when you acquired the software.(Removed Software Key)

5. **Follow Instructions**: The script will guide you through the Custom setup process and certificate installation.

6. **Certificate Installation**: Follow the script's instructions to download and install the required certificate. Download the certificate from [http://mitm.it/cert/p12](http://mitm.it/cert/p12) while the script is running.

7. **Certificate Installation Steps**:
    - Open the certificate file and follow the installation steps.
    - Select "Local Machine" and allow permissions.
    - Click through the installation steps.
    - Choose "Place all certificates in the following store" and browse to "Trusted Root Certification Authorities," then click OK.
    - Finish the installation.

8. **Configure Codetantra**: Once the certificate is installed, the script will configure the custom settings for Codetantra. Follow the script's instructions to proceed.

9. **Keep Script Running**: Keep the script running while using Codetantra. Follow the script's instructions to deactivate the configuration when you're finished.

10. **Exit**: Follow the prompt to exit the script when you are done.

## Notice

You will required to download plugin during installation. with that software will not work.

## Additional Information

- **Certificates**: Make sure you download and install the certificate as per the script's instructions.
- **Subprocess Handling**: The script runs `apx.exe` as a subprocess for handling Codetantra patch background tasks.

## Disclaimer

The program's usage may be subject to local policies and regulations regarding the modification of network and system settings. Use this script responsibly and in accordance with the terms and conditions of the software and services involved.

If network not working then rerun the codx.exe script and off it step wise

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/ck-cyberking/Codx/issues) if you want to contribute.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
