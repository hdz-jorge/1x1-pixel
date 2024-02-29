# 1x1 Pixel Tracker

1x1 Pixel Tracker is a simple tool used for tracking email opens by embedding a small transparent image (pixel) in the email content. When the recipient opens the email, their email client fetches the pixel image from a remote server, allowing the sender to track when the email was opened.

## Table of Contents

1. [Introduction](#introduction)
2. [Usage](#usage)
3. [Setup](#setup)
4. [Hosting Pixel Image](#hosting-pixel-image)
5. [Security Considerations](#security-considerations)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)

## Introduction

Email Pixel Tracker provides a lightweight method for tracking email opens without compromising user privacy. By embedding a 1x1 transparent pixel image in the email content, senders can monitor email engagement and effectiveness.

## Usage

To use the Email Pixel Tracker:

1. Generate a 1x1 transparent pixel image.
2. Host the pixel image on a remote server.
3. Embed the pixel image URL in the HTML content of your email.
4. Send the email to recipients.
5. Monitor pixel requests on the server to track email opens.

## Setup

1. Clone or download the Email Pixel Tracker repository.
2. Generate a 1x1 transparent pixel image (e.g., using image editing software).
3. Host the pixel image on a web server or an image hosting service.
4. Replace the placeholder pixel image URL in the HTML template with the hosted pixel image URL.
5. Customize the HTML template as needed.
6. Send the email to recipients.

## Hosting Pixel Image

There are several options for hosting the pixel image:

- Use a web server to host the pixel image.
- Upload the pixel image to an image hosting service (e.g., GitHub Pages, Imgur).
- Embed the pixel image directly in the HTML content using base64 encoding.

## Security Considerations

When using Email Pixel Tracker, consider the following security considerations:

- Ensure that the pixel image URL is accessible only to authorized users.
- Avoid embedding sensitive information or personally identifiable information in the pixel image URL.
- Use HTTPS to encrypt pixel image requests and prevent eavesdropping.

## Contributing

Contributions to Email Pixel Tracker are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive messages.
4. Submit a pull request detailing your changes.

## License

This project is licensed under the MIT License.

## Contact

For questions or support, contact Jorge Hernandez at jorge.hernandez@taskmate.agency.
