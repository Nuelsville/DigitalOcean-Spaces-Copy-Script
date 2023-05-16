# DigitalOcean Spaces Copy Script

This PHP script allows you to copy the contents of a specific folder within a DigitalOcean Space or your entire DigitalOcean Space to your local storage. It utilizes the AWS SDK for PHP to interact with DigitalOcean Spaces and simplifies the retrieval of files from a specific folder of your Space or entire Space.

## Prerequisites

Before using this script, ensure that you have the following:

- PHP (with the AWS SDK for PHP) installed on your machine.
- DigitalOcean Spaces credentials (Access Key and Secret Key) for the Space you want to access.
- Proper permissions to access the specified Space.

## Usage

1. Clone or download this repository to your local machine.

2. Update the script with your own DigitalOcean Spaces details and desired configuration. Open the script file `copy_script.php` and modify the following variables:

   - `$space_name`: Replace with the name of your DigitalOcean Space.
   - `$access_key`: Replace with your DigitalOcean Spaces Access Key.
   - `$secret_key`: Replace with your DigitalOcean Spaces Secret Key.
   - `$local_directory`: Replace with the local directory where you want to save the copied files.

3. Run the script by executing the following command in your terminal or command prompt:

   ```shell
   php copy_script.php

The script will connect to your DigitalOcean Space, list the contents of the 'public' folder, and copy the files to your specified local directory.

4. Check your local directory to verify that the files from the specific folder or entire space have been successfully copied.

## License
This project is licensed under the MIT License.

Feel free to customize and enhance the script according to your specific needs.

## Disclaimer
Please note that this script is provided as-is and without warranty. Use it at your own risk. Ensure that you have proper backups and take necessary precautions while copying files from your DigitalOcean Space to your local storage.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.
