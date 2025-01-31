# PHP File Manager with Password Protection

## Description
This is a simple yet secure PHP-based File Manager that allows users to upload files with a password. When downloading a file, users must enter the same password used during the upload process to access the file. This ensures an additional layer of security for file sharing.

## Features
- **Upload files with a password**
- **Secure file download requiring password verification**
- **Simple and user-friendly interface**
- **Supports multiple file types**
- **Prevents unauthorized access to uploaded files**

## Requirements
- PHP 7.3 or higher
- Apache/Nginx Server
- Enabled file uploads in `php.ini`

## Usage
1. **Upload Files**: Select a file, enter a password, and upload.
2. **Download Files**: Enter the correct password to retrieve the file.

## Security Measures
- **Password Hashing**: Prevents unauthorized access by securely storing passwords.
- **Restricted Direct Access**: Uploaded files are stored securely and cannot be accessed directly.
- **Input Validation and Sanitization**: Prevents malicious file uploads and XSS attacks.

## Screenshots
Screenshots of the application are available in the [GitHub repository](https://github.com/your-username/php-file-manager).

## Contributing
If you'd like to contribute, please fork the repository and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For any issues or feature requests, please create an issue on GitHub or contact me at [gsehjowalia@gmail.com](mailto:gsehjowalia@gmail.com).
