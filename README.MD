PHP File Manager with Password Protection

Description

This is a simple yet secure PHP-based File Manager that allows users to upload files with a password. When downloading a file, users must enter the same password used during the upload process to access the file. This ensures an additional layer of security for file sharing.

Features

Upload files with a password

Secure file download requiring password verification

Simple and user-friendly interface

Supports multiple file types

Prevents unauthorized access to uploaded files

Installation

Extract the files into your web server directory (e.g., htdocs for XAMPP, www for WAMP).

Ensure the uploads directory has write permissions.

chmod 777 uploads

Start your local server (Apache with PHP support).

Open the project in a web browser.

Usage

Uploading a File

Navigate to the upload page.

Select a file to upload.

Enter a password to secure the file.

Click the "Upload" button.

The system generates a unique file link.

Downloading a File

Open the file download page.

Enter the correct password used during upload.

If the password matches, the file will be available for download.

Requirements

PHP 7.4 or higher

Apache/Nginx Server

Enabled file uploads in php.ini

Security Measures

Password hashing to prevent unauthorized access

Restricted direct access to uploaded files

Input validation and sanitization

Screenshots

Screenshots of the application are available in the GitHub repository.

Contributing

If you'd like to contribute, please fork the repository and submit a pull request.

License

This project is licensed under the MIT License.

Contact

For any issues or feature requests, please create an issue on GitHub or contact me at gsehjowalia@gmail.com.
