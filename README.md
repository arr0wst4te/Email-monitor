# Email Monitor

The Email Monitor is a tool for monitoring email infrastructure, allowing users to send emails via SMTP and retrieve emails via POP3. It provides metrics and logs for tracking the email sending and receiving process.

## Features

- Send emails via SMTP.
- Retrieve emails via POP3.
- Track metrics such as the number of emails sent, received, and failed transmissions.
- Monitor cycle time for each email between send and receive.
- Supports SMTP and POP3 with SSL/TLS.
- Configuration via YAML file.

## Requirements

- Go programming language.
- `gopkg.in/yaml.v2` for YAML parsing.
- `github.com/knadh/go-pop3` for POP3 functionality.
- Internet connection for sending and receiving emails.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/arr0wst4te/Email-monitor.git

2. Install dependencies;

   ```bash
   go mod tidy

3. Create a config.yaml file with your SMTP and POP3 server configurations.


4. Run the application:

    ```bash
    go run email_monitor.go config.yaml


 The application will send an email and retrieve emails at regular intervals (default is every 5 minutes). Check the console output for logs and status messages.



## Configuration Options

`smtp_server`: SMTP server address.
`smtp_port`: SMTP port number.
`pop3_server`: POP3 server address.
`pop3_port`: POP3 port number.
`username`: Your email username.
`password`: Your email password.
`use_ssl`: Set to true if SSL/TLS is enabled.
`subject`: Email subject.
`recipient`: Recipient email address.


## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.


Feel free to modify the content as needed before copying it to your `README.md` file.


***Contact Details:***

Email: jameskal924@gmail.com

Skype: [Join Me on Skype](https://join.skype.com/invite/xqvUSh5ugdbJ)

Telegram: [Contact me on Telegram](https://t.me/luckycstar55)