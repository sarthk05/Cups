# ADDING COMMENTS AND PRINTING THEM
I modified the cupsFilePrintf() function in the scheduler's log.c file. I made a mental note to remember the function. Following the alteration of the file. Retype the commands build and make install.

## Here is modified accesslog
```
localhost - - [21/Dec/2022:16:35:41 +0530] "POST / HTTP/1.1" 200 349 Create-Printer-Subscriptions successful-ok
localhost - - [21/Dec/2022:16:35:41 +0530] "POST / HTTP/1.1" 200 176 Create-Printer-Subscriptions successful-ok
localhost - - [21/Dec/2022:16:35:43 +0530] "POST / HTTP/1.1" 200 359 Create-Printer-Subscriptions successful-ok
localhost - - [21/Dec/2022:16:35:56 +0530] "POST / HTTP/1.1" 200 363 Create-Printer-Subscriptions successful-ok
localhost - - [21/Dec/2022:16:35:56 +0530] "POST / HTTP/1.1" 200 151 Cancel-Subscription successful-ok
localhost - - [21/Dec/2022:16:35:56 +0530] "POST / HTTP/1.1" 200 151 Cancel-Subscription client-error-not-found
localhost - - [21/Dec/2022:22:44:37 +0530] "POST / HTTP/1.1" 200 349 Create-Printer-Subscriptions successful-ok
localhost - - [21/Dec/2022:22:44:37 +0530] "POST / HTTP/1.1" 200 176 Create-Printer-Subscriptions successful-ok
localhost - - [21/Dec/2022:22:44:41 +0530] "POST / HTTP/1.1" 200 359 Create-Printer-Subscriptions successful-ok
localhost - - [21/Dec/2022:22:44:49 +0530] "POST / HTTP/1.1" 200 363 Create-Printer-Subscriptions successful-ok
localhost - - [21/Dec/2022:22:44:51 +0530] "POST / HTTP/1.1" 200 151 Cancel-Subscription successful-ok
localhost - - [21/Dec/2022:22:44:51 +0530] "POST / HTTP/1.1" 200 151 Cancel-Subscription client-error-not-found
localhost - - [26/Dec/2022:22:17:56 +0530] "POST / HTTP/1.1" 200 349 Create-Printer-Subscriptions successful-ok
localhost - - [26/Dec/2022:22:17:56 +0530] "POST / HTTP/1.1" 200 176 Create-Printer-Subscriptions successful-ok
localhost - - [26/Dec/2022:22:18:00 +0530] "POST / HTTP/1.1" 200 359 Create-Printer-Subscriptions successful-ok
localhost - - [26/Dec/2022:22:18:10 +0530] "POST / HTTP/1.1" 200 363 Create-Printer-Subscriptions successful-ok
localhost - - [26/Dec/2022:22:18:12 +0530] "POST / HTTP/1.1" 200 151 Cancel-Subscription successful-ok
localhost - - [26/Dec/2022:22:29:08 +0530] "POST /admin/ HTTP/1.1" 401 239 CUPS-Add-Modify-Printer successful-ok
localhost - root [26/Dec/2022:22:29:08 +0530] "POST /admin/ HTTP/1.1" 200 239 CUPS-Add-Modify-Printer successful-ok
localhost - - [26/Dec/2022:22:29:35 +0530] "POST / HTTP/1.1" 200 347 Create-Printer-Subscriptions successful-ok
localhost - - [26/Dec/2022:22:29:35 +0530] "POST / HTTP/1.1" 200 5293864 CUPS-Get-PPDs -
localhost - - [26/Dec/2022:22:30:40 +0530] "POST /admin/ HTTP/1.1" 401 242 CUPS-Add-Modify-Printer successful-ok
localhost - root [26/Dec/2022:22:30:40 +0530] "POST /admin/ HTTP/1.1" 200 242 CUPS-Add-Modify-Printer successful-ok
localhost - - [26/Dec/2022:22:37:56 +0530] "POST / HTTP/1.1" 200 186 Renew-Subscription successful-ok
localhost - - [26/Dec/2022:22:46:16 +0530] "POST / HTTP/1.1" 200 186 Renew-Subscription successful-ok
localhost - - [26/Dec/2022:22:48:34 +0530] "POST /printers/DummyPrint HTTP/1.1" 200 365 Create-Job successful-ok
localhost - - [26/Dec/2022:22:48:34 +0530] "POST /printers/DummyPrint HTTP/1.1" 200 3296 Send-Document successful-ok
localhost - - [26/Dec/2022:22:52:48 +0530] "POST /printers/DummyPrint HTTP/1.1" 200 365 Create-Job successful-ok
localhost - - [26/Dec/2022:22:52:48 +0530] "POST /printers/DummyPrint HTTP/1.1" 200 3296 Send-Document successful-ok
localhost - - [26/Dec/2022:22:54:36 +0530] "POST / HTTP/1.1" 200 186 Renew-Subscription successful-ok
Sarthak Singh commented here
 localhost - - [26/Dec/2022:23:02:56 +0530] "POST / HTTP/1.1" 200 186 Renew-Subscription successful-ok
```
