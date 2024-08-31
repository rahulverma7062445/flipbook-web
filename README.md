# How to use sopraflipbook in local environment

### Prerequisites

Apache server.

* To install `Apache server` in your local environment follow below steps:

1. Go to this [link](https://www.apachelounge.com/download/#google_vignette) and download `Apache`.
2. Unzipp the downloaded zip file in `c drive`.
3. After unzipping go to `Apache24/conf` and find a file called `httpd.conf`.
4. open file `httpd.conf` and uncomment line 162(LoadModule rewrite_module modules/mod_rewrite.so), on line 227 change `ServerName` to `localhost:80`
and on line 272 set AllowOverride to All.
5. Open command prompt in administrator mode and run `httpd.exe -k install` command.
6. Apache server has been installed in your local environmentto, to run the server use `httpd.exe -k start` command.

* To run `flipbook-web` in your local environment follow below steps:

1. Go to this [link](https://innersource.soprasteria.com/di-codebase/sopraflipbook/flipbook-web) and download
or clone `sopraflipbook` project in your local directory. 
2. Start the server using `httpd.exe -k start` command.