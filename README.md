# laminas-mail

[![Build Status](https://github.com/laminas/laminas-mail/workflows/Continuous%20Integration/badge.svg)](https://github.com/laminas/laminas-mail/actions?query=workflow%3A"Continuous+Integration")

> ## Abandoned
>
> This package is **abandoned** and will receive no further development!
>
> It is suggested to use
>
> - [ddeboer/imap](https://github.com/ddeboer/imap) for interacting with IMAP
> - [zbateson/mail-mime-parser](https://github.com/zbateson/mail-mime-parser) for parsing MIME messages
> - [symfony/mailer](https://github.com/symfony/mailer) for sending mail
>
> See the Technical Steering Committee [meeting minutes](https://github.com/laminas/technical-steering-committee/blob/main/meetings/minutes/2023-12-04-TSC-Minutes.md).

`Laminas\Mail` provides generalized functionality to compose and send both text and
MIME-compliant multipart email messages. Mail can be sent with `Laminas\Mail` via
the `Mail\Transport\Sendmail`, `Mail\Transport\Smtp` or the `Mail\Transport\File`
transport. Of course, you can also implement your own transport by implementing
the `Mail\Transport\TransportInterface`.

- File issues at https://github.com/laminas/laminas-mail/issues
- Documentation is at https://docs.laminas.dev/laminas-mail/
