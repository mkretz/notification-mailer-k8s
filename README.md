# notification-mailer-k8s
Docker / kubernetes version of notification-mailer

## Requirements to run
1. Assumes that there exists a RabbitMQ service named `notification-mq`
2. Assumes that the environment variable `MAIL_URL` is containing a valid SMTP URI
3. Assumes that the environment variable `TO_ADDRESS` is containing the email address to which all notification mails are sent

## Deployment
Use [this Helm chart](https://github.com/mkretz/notification-k8s).
