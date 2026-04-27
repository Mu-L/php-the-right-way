---
isChild: true
anchor:  windows_setup
---

## Windows Setup {#windows_setup_title}

You can download the binaries from [the php.net download page][php-downloads]. After the extraction of PHP, it is 
recommended to set the [PATH][windows-path] to the root of your PHP folder (where php.exe is located) so you can execute
PHP from anywhere.

For learning and local development, you can use the [built-in webserver](/#builtin_web_server_title) with PHP 5.4+ so
you don't need to worry about configuring it. If you would like an "all-in-one" which includes a full-blown webserver
and MySQL too, then tools such as the [EasyPHP][easyphp], [OpenServer][openserver] or [WampServer][wamp] will help get a 
Windows development environment up and running fast. That said, these tools will be a little different from 
production so be careful of environment differences if you are working on Windows and deploying to Linux.

Generally running your application on different environment in development and production can lead to strange bugs 
popping up when you go live. If you are developing on Windows and deploying to Linux (or anything non-Windows) then you
should consider using a [Virtual Machine](/#virtualization_title) or [Windows Subsystem for Linux (WSL)][wsl].

Chris Tankersley has a very helpful blog post on what tools he uses to do [PHP development using Windows][windows-tools].

[easyphp]: https://www.easyphp.org/
[openserver]: https://ospanel.io/en/
[php-downloads]: https://www.php.net/downloads.php?os=windows
[wamp]: https://wampserver.aviatechno.net/?lang=en
[windows-path]: https://www.windows-commandline.com/set-path-command-line/
[windows-tools]: https://ctankersley.com/2016/11/13/developing-on-windows-2016/
[wsl]: https://learn.microsoft.com/en-us/windows/wsl/
