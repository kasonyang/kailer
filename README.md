# Overview

Kailer is a mailer writing in kalang.

# Build

    $ gradlew clean build

# Usage

1. create configuration file `~/.kailer/main.properties` and configure your email account:

        mail.smtp.host=Your smtp server's host
        mail.smtp.port=Your smtp server's port
        mail.smtp.ssl.enable=true
        mail.smtp.auth=true
        user=Your account 
        password=Your email password


2. send email from command line:

        $ kailer -s 'email from kailer' -b 'This is a email from kailer' admin@example.com



# License

MIT