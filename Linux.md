
Welcome to Ubuntu 22.04.4 LTS (GNU/Linux 5.15.153.1-microsoft-standard-WSL2 x86_64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/pro


This message is shown once a day. To disable it please create the
/home/anchisa/.hushlogin file.
anchisa@IE3311-27:~$
anchisa@IE3311-27:~$
anchisa@IE3311-27:~$
anchisa@IE3311-27:~$
anchisa@IE3311-27:~$
anchisa@IE3311-27:~$
anchisa@IE3311-27:~$
anchisa@IE3311-27:~$
anchisa@IE3311-27:~$ docker run -it -name test-node --rm ubuntu /bin/bash
unknown shorthand flag: 'n' in -name
See 'docker run --help'.
anchisa@IE3311-27:~$ docker run -it -name test-node --rm ubuntu /bin/bash
unknown shorthand flag: 'n' in -name
See 'docker run --help'.
anchisa@IE3311-27:~$ docker run -it --name test-node --rm ubuntu /bin/bash
Unable to find image 'ubuntu:latest' locally
latest: Pulling from library/ubuntu
9c704ecd0c69: Pull complete
Digest: sha256:2e863c44b718727c860746568e1d54afd13b2fa71b160f5cd9058fc436217b30
Status: Downloaded newer image for ubuntu:latest
^@rg: 80) ^C
root@e0b474ad133b:/# ^C
root@e0b474ad133b:/# ^C
root@e0b474ad133b:/# ^C
(arg: 80) ^C
root@e0b474ad133b:/# apt
apt 2.7.14 (amd64)
Usage: apt [options] command

apt is a commandline package manager and provides commands for
searching and managing as well as querying information about packages.
It provides the same functionality as the specialized APT tools,
like apt-get and apt-cache, but enables options more suitable for
interactive use by default.

Most used commands:
  list - list packages based on package names
  search - search in package descriptions
  show - show package details
  install - install packages
  reinstall - reinstall packages
  remove - remove packages
  autoremove - automatically remove all unused packages
  update - update list of available packages
  upgrade - upgrade the system by installing/upgrading packages
  full-upgrade - upgrade the system by removing/installing/upgrading packages
  edit-sources - edit the source information file
  satisfy - satisfy dependency strings

See apt(8) for more information about the available commands.
Configuration options and syntax is detailed in apt.conf(5).
Information about how to configure sources can be found in sources.list(5).
Package and version choices can be expressed via apt_preferences(5).
Security details are available in apt-secure(8).
                                        This APT has Super Cow Powers.
root@e0b474ad133b:/# apt updat
E: Invalid operation updat
root@e0b474ad133b:/# apt update
Get:1 http://security.ubuntu.com/ubuntu noble-security InRelease [126 kB]
Get:2 http://archive.ubuntu.com/ubuntu noble InRelease [256 kB]
Get:3 http://security.ubuntu.com/ubuntu noble-security/restricted amd64 Packages [299 kB]
Get:4 http://archive.ubuntu.com/ubuntu noble-updates InRelease [126 kB]
Get:5 http://security.ubuntu.com/ubuntu noble-security/main amd64 Packages [360 kB]
Get:6 http://security.ubuntu.com/ubuntu noble-security/universe amd64 Packages [333 kB]
Get:7 http://archive.ubuntu.com/ubuntu noble-backports InRelease [126 kB]
Get:8 http://security.ubuntu.com/ubuntu noble-security/multiverse amd64 Packages [12.7 kB]
Get:9 http://archive.ubuntu.com/ubuntu noble/universe amd64 Packages [19.3 MB]
Get:10 http://archive.ubuntu.com/ubuntu noble/main amd64 Packages [1808 kB]
Get:11 http://archive.ubuntu.com/ubuntu noble/multiverse amd64 Packages [331 kB]
Get:12 http://archive.ubuntu.com/ubuntu noble/restricted amd64 Packages [117 kB]
Get:13 http://archive.ubuntu.com/ubuntu noble-updates/restricted amd64 Packages [299 kB]
Get:14 http://archive.ubuntu.com/ubuntu noble-updates/multiverse amd64 Packages [16.9 kB]
Get:15 http://archive.ubuntu.com/ubuntu noble-updates/universe amd64 Packages [428 kB]
Get:16 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 Packages [429 kB]
Get:17 http://archive.ubuntu.com/ubuntu noble-backports/universe amd64 Packages [11.5 kB]
Fetched 24.4 MB in 8s (2984 kB/s)
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
3 packages can be upgraded. Run 'apt list --upgradable' to see them.
root@e0b474ad133b:/# apt upgrade
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
Calculating upgrade... Done
The following packages will be upgraded:
  libssl3t64 libsystemd0 libudev1
3 upgraded, 0 newly installed, 0 to remove and 0 not upgraded.
Need to get 2548 kB of archives.
After this operation, 1024 B of additional disk space will be used.
Do you want to continue? [Y/n] Y
Abort.
root@e0b474ad133b:/# curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.20.0/install.sh | bash
bash: curl: command not found
root@e0b474ad133b:/# sudo apt update
bash: sudo: command not found
root@e0b474ad133b:/# sudo apt install nodejs
bash: sudo: command not found
root@e0b474ad133b:/# node -v
bash: node: command not found
root@e0b474ad133b:/# curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
bash: curl: command not found
root@e0b474ad133b:/# curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
bash: curl: command not found
root@e0b474ad133b:/# sudo apt update
bash: sudo: command not found
root@e0b474ad133b:/# sudo apt install curl
bash: sudo: command not found
root@e0b474ad133b:/# sudo yum install curl
bash: sudo: command not found
root@e0b474ad133b:/# sudo apt update
bash: sudo: command not found
root@e0b474ad133b:/# sudo apt upgrade
bash: sudo: command not found
root@e0b474ad133b:/# sudo apt install docker.io
bash: sudo: command not found
root@e0b474ad133b:/# sudo usermod -aG docker $USER
bash: sudo: command not found
root@e0b474ad133b:/# apt-get update
Hit:1 http://archive.ubuntu.com/ubuntu noble InRelease
Hit:2 http://security.ubuntu.com/ubuntu noble-security InRelease
Hit:3 http://archive.ubuntu.com/ubuntu noble-updates InRelease
Hit:4 http://archive.ubuntu.com/ubuntu noble-backports InRelease
Reading package lists... Done
root@e0b474ad133b:/# apt-get install -y curl
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
  ca-certificates krb5-locales libbrotli1 libcurl4t64 libgssapi-krb5-2 libk5crypto3 libkeyutils1 libkrb5-3 libkrb5support0 libldap-common libldap2 libnghttp2-14
  libpsl5t64 librtmp1 libsasl2-2 libsasl2-modules libsasl2-modules-db libssh-4 libssl3t64 openssl publicsuffix
Suggested packages:
  krb5-doc krb5-user libsasl2-modules-gssapi-mit | libsasl2-modules-gssapi-heimdal libsasl2-modules-ldap libsasl2-modules-otp libsasl2-modules-sql
The following NEW packages will be installed:
  ca-certificates curl krb5-locales libbrotli1 libcurl4t64 libgssapi-krb5-2 libk5crypto3 libkeyutils1 libkrb5-3 libkrb5support0 libldap-common libldap2 libnghttp2-14
  libpsl5t64 librtmp1 libsasl2-2 libsasl2-modules libsasl2-modules-db libssh-4 openssl publicsuffix
The following packages will be upgraded:
  libssl3t64
1 upgraded, 21 newly installed, 0 to remove and 2 not upgraded.
Need to get 5503 kB of archives.
After this operation, 9198 kB of additional disk space will be used.
Get:1 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libssl3t64 amd64 3.0.13-0ubuntu3.2 [1940 kB]
Get:2 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 openssl amd64 3.0.13-0ubuntu3.2 [1002 kB]
Get:3 http://archive.ubuntu.com/ubuntu noble/main amd64 ca-certificates all 20240203 [159 kB]
Get:4 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 krb5-locales all 1.20.1-6ubuntu2.1 [14.0 kB]
Get:5 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libkrb5support0 amd64 1.20.1-6ubuntu2.1 [33.6 kB]
Get:6 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libk5crypto3 amd64 1.20.1-6ubuntu2.1 [81.7 kB]
Get:7 http://archive.ubuntu.com/ubuntu noble/main amd64 libkeyutils1 amd64 1.6.3-3build1 [9490 B]
Get:8 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libkrb5-3 amd64 1.20.1-6ubuntu2.1 [347 kB]
Get:9 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libgssapi-krb5-2 amd64 1.20.1-6ubuntu2.1 [143 kB]
Get:10 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libnghttp2-14 amd64 1.59.0-1ubuntu0.1 [74.3 kB]
Get:11 http://archive.ubuntu.com/ubuntu noble/main amd64 libpsl5t64 amd64 0.21.2-1.1build1 [57.1 kB]
Get:12 http://archive.ubuntu.com/ubuntu noble/main amd64 publicsuffix all 20231001.0357-0.1 [129 kB]
Get:13 http://archive.ubuntu.com/ubuntu noble/main amd64 libbrotli1 amd64 1.1.0-2build2 [331 kB]
Get:14 http://archive.ubuntu.com/ubuntu noble/main amd64 libsasl2-modules-db amd64 2.1.28+dfsg1-5ubuntu3 [20.3 kB]
Get:15 http://archive.ubuntu.com/ubuntu noble/main amd64 libsasl2-2 amd64 2.1.28+dfsg1-5ubuntu3 [53.2 kB]
Get:16 http://archive.ubuntu.com/ubuntu noble/main amd64 libldap2 amd64 2.6.7+dfsg-1~exp1ubuntu8 [195 kB]
Get:17 http://archive.ubuntu.com/ubuntu noble/main amd64 librtmp1 amd64 2.4+20151223.gitfa8646d.1-2build7 [56.3 kB]
Get:18 http://archive.ubuntu.com/ubuntu noble/main amd64 libssh-4 amd64 0.10.6-2build2 [188 kB]
Get:19 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libcurl4t64 amd64 8.5.0-2ubuntu10.2 [341 kB]
Get:20 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 curl amd64 8.5.0-2ubuntu10.2 [227 kB]
Get:21 http://archive.ubuntu.com/ubuntu noble/main amd64 libldap-common all 2.6.7+dfsg-1~exp1ubuntu8 [31.4 kB]
Get:22 http://archive.ubuntu.com/ubuntu noble/main amd64 libsasl2-modules amd64 2.1.28+dfsg1-5ubuntu3 [69.7 kB]
Fetched 5503 kB in 4s (1448 kB/s)
debconf: delaying package configuration, since apt-utils is not installed
(Reading database ... 4376 files and directories currently installed.)
Preparing to unpack .../libssl3t64_3.0.13-0ubuntu3.2_amd64.deb ...
Unpacking libssl3t64:amd64 (3.0.13-0ubuntu3.2) over (3.0.13-0ubuntu3.1) ...
Setting up libssl3t64:amd64 (3.0.13-0ubuntu3.2) ...
Selecting previously unselected package openssl.
(Reading database ... 4376 files and directories currently installed.)
Preparing to unpack .../00-openssl_3.0.13-0ubuntu3.2_amd64.deb ...
Unpacking openssl (3.0.13-0ubuntu3.2) ...
Selecting previously unselected package ca-certificates.
Preparing to unpack .../01-ca-certificates_20240203_all.deb ...
Unpacking ca-certificates (20240203) ...
Selecting previously unselected package krb5-locales.
Preparing to unpack .../02-krb5-locales_1.20.1-6ubuntu2.1_all.deb ...
Unpacking krb5-locales (1.20.1-6ubuntu2.1) ...
Selecting previously unselected package libkrb5support0:amd64.
Preparing to unpack .../03-libkrb5support0_1.20.1-6ubuntu2.1_amd64.deb ...
Unpacking libkrb5support0:amd64 (1.20.1-6ubuntu2.1) ...
Selecting previously unselected package libk5crypto3:amd64.
Preparing to unpack .../04-libk5crypto3_1.20.1-6ubuntu2.1_amd64.deb ...
Unpacking libk5crypto3:amd64 (1.20.1-6ubuntu2.1) ...
Selecting previously unselected package libkeyutils1:amd64.
Preparing to unpack .../05-libkeyutils1_1.6.3-3build1_amd64.deb ...
Unpacking libkeyutils1:amd64 (1.6.3-3build1) ...
Selecting previously unselected package libkrb5-3:amd64.
Preparing to unpack .../06-libkrb5-3_1.20.1-6ubuntu2.1_amd64.deb ...
Unpacking libkrb5-3:amd64 (1.20.1-6ubuntu2.1) ...
Selecting previously unselected package libgssapi-krb5-2:amd64.
Preparing to unpack .../07-libgssapi-krb5-2_1.20.1-6ubuntu2.1_amd64.deb ...
Unpacking libgssapi-krb5-2:amd64 (1.20.1-6ubuntu2.1) ...
Selecting previously unselected package libnghttp2-14:amd64.
Preparing to unpack .../08-libnghttp2-14_1.59.0-1ubuntu0.1_amd64.deb ...
Unpacking libnghttp2-14:amd64 (1.59.0-1ubuntu0.1) ...
Selecting previously unselected package libpsl5t64:amd64.
Preparing to unpack .../09-libpsl5t64_0.21.2-1.1build1_amd64.deb ...
Unpacking libpsl5t64:amd64 (0.21.2-1.1build1) ...
Selecting previously unselected package publicsuffix.
Preparing to unpack .../10-publicsuffix_20231001.0357-0.1_all.deb ...
Unpacking publicsuffix (20231001.0357-0.1) ...
Selecting previously unselected package libbrotli1:amd64.
Preparing to unpack .../11-libbrotli1_1.1.0-2build2_amd64.deb ...
Unpacking libbrotli1:amd64 (1.1.0-2build2) ...
Selecting previously unselected package libsasl2-modules-db:amd64.
Preparing to unpack .../12-libsasl2-modules-db_2.1.28+dfsg1-5ubuntu3_amd64.deb ...
Unpacking libsasl2-modules-db:amd64 (2.1.28+dfsg1-5ubuntu3) ...
Selecting previously unselected package libsasl2-2:amd64.
Preparing to unpack .../13-libsasl2-2_2.1.28+dfsg1-5ubuntu3_amd64.deb ...
Unpacking libsasl2-2:amd64 (2.1.28+dfsg1-5ubuntu3) ...
Selecting previously unselected package libldap2:amd64.
Preparing to unpack .../14-libldap2_2.6.7+dfsg-1~exp1ubuntu8_amd64.deb ...
Unpacking libldap2:amd64 (2.6.7+dfsg-1~exp1ubuntu8) ...
Selecting previously unselected package librtmp1:amd64.
Preparing to unpack .../15-librtmp1_2.4+20151223.gitfa8646d.1-2build7_amd64.deb ...
Unpacking librtmp1:amd64 (2.4+20151223.gitfa8646d.1-2build7) ...
Selecting previously unselected package libssh-4:amd64.
Preparing to unpack .../16-libssh-4_0.10.6-2build2_amd64.deb ...
Unpacking libssh-4:amd64 (0.10.6-2build2) ...
Selecting previously unselected package libcurl4t64:amd64.
Preparing to unpack .../17-libcurl4t64_8.5.0-2ubuntu10.2_amd64.deb ...
Unpacking libcurl4t64:amd64 (8.5.0-2ubuntu10.2) ...
Selecting previously unselected package curl.
Preparing to unpack .../18-curl_8.5.0-2ubuntu10.2_amd64.deb ...
Unpacking curl (8.5.0-2ubuntu10.2) ...
Selecting previously unselected package libldap-common.
Preparing to unpack .../19-libldap-common_2.6.7+dfsg-1~exp1ubuntu8_all.deb ...
Unpacking libldap-common (2.6.7+dfsg-1~exp1ubuntu8) ...
Selecting previously unselected package libsasl2-modules:amd64.
Preparing to unpack .../20-libsasl2-modules_2.1.28+dfsg1-5ubuntu3_amd64.deb ...
Unpacking libsasl2-modules:amd64 (2.1.28+dfsg1-5ubuntu3) ...
Setting up libkeyutils1:amd64 (1.6.3-3build1) ...
Setting up libbrotli1:amd64 (1.1.0-2build2) ...
Setting up libsasl2-modules:amd64 (2.1.28+dfsg1-5ubuntu3) ...
Setting up libpsl5t64:amd64 (0.21.2-1.1build1) ...
Setting up libnghttp2-14:amd64 (1.59.0-1ubuntu0.1) ...
Setting up krb5-locales (1.20.1-6ubuntu2.1) ...
Setting up libldap-common (2.6.7+dfsg-1~exp1ubuntu8) ...
Setting up libkrb5support0:amd64 (1.20.1-6ubuntu2.1) ...
Setting up libsasl2-modules-db:amd64 (2.1.28+dfsg1-5ubuntu3) ...
Setting up librtmp1:amd64 (2.4+20151223.gitfa8646d.1-2build7) ...
Setting up libk5crypto3:amd64 (1.20.1-6ubuntu2.1) ...
Setting up libsasl2-2:amd64 (2.1.28+dfsg1-5ubuntu3) ...
Setting up libkrb5-3:amd64 (1.20.1-6ubuntu2.1) ...
Setting up openssl (3.0.13-0ubuntu3.2) ...
Setting up publicsuffix (20231001.0357-0.1) ...
Setting up libldap2:amd64 (2.6.7+dfsg-1~exp1ubuntu8) ...
Setting up ca-certificates (20240203) ...
debconf: unable to initialize frontend: Dialog
debconf: (No usable dialog-like program is installed, so the dialog based frontend cannot be used. at /usr/share/perl5/Debconf/FrontEnd/Dialog.pm line 79.)
debconf: falling back to frontend: Readline
debconf: unable to initialize frontend: Readline
debconf: (Can't locate Term/ReadLine.pm in @INC (you may need to install the Term::ReadLine module) (@INC entries checked: /etc/perl /usr/local/lib/x86_64-linux-gnu/perl/5.38.2 /usr/local/share/perl/5.38.2 /usr/lib/x86_64-linux-gnu/perl5/5.38 /usr/share/perl5 /usr/lib/x86_64-linux-gnu/perl-base /usr/lib/x86_64-linux-gnu/perl/5.38 /usr/share/perl/5.38 /usr/local/lib/site_perl) at /usr/share/perl5/Debconf/FrontEnd/Readline.pm line 8.)
debconf: falling back to frontend: Teletype
Updating certificates in /etc/ssl/certs...
146 added, 0 removed; done.
Setting up libgssapi-krb5-2:amd64 (1.20.1-6ubuntu2.1) ...
Setting up libssh-4:amd64 (0.10.6-2build2) ...
Setting up libcurl4t64:amd64 (8.5.0-2ubuntu10.2) ...
Setting up curl (8.5.0-2ubuntu10.2) ...
Processing triggers for libc-bin (2.39-0ubuntu8.2) ...
Processing triggers for ca-certificates (20240203) ...
Updating certificates in /etc/ssl/certs...
0 added, 0 removed; done.
Running hooks in /etc/ca-certificates/update.d...
done.
root@e0b474ad133b:/# curl --version
curl 8.5.0 (x86_64-pc-linux-gnu) libcurl/8.5.0 OpenSSL/3.0.13 zlib/1.3 brotli/1.1.0 zstd/1.5.5 libidn2/2.3.7 libpsl/0.21.2 (+libidn2/2.3.7) libssh/0.10.6/openssl/zlib nghttp2/1.59.0 librtmp/2.3 OpenLDAP/2.6.7
Release-Date: 2023-12-06, security patched: 8.5.0-2ubuntu10.2
Protocols: dict file ftp ftps gopher gophers http https imap imaps ldap ldaps mqtt pop3 pop3s rtmp rtsp scp sftp smb smbs smtp smtps telnet tftp
Features: alt-svc AsynchDNS brotli GSS-API HSTS HTTP2 HTTPS-proxy IDN IPv6 Kerberos Largefile libz NTLM PSL SPNEGO SSL threadsafe TLS-SRP UnixSockets zstd
root@e0b474ad133b:/# curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100 15916  100 15916    0     0  51410      0 --:--:-- --:--:-- --:--:-- 52013
=> Downloading nvm as script to '/root/.nvm'

=> Appending nvm source string to /root/.bashrc
=> Appending bash_completion source string to /root/.bashrc
=> Close and reopen your terminal to start using nvm or run the following to use it now:

export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion
root@e0b474ad133b:/# source ~/.bashrc
root@e0b474ad133b:/# nvm list-remote
        v0.1.14
        v0.1.15
        v0.1.16
        v0.1.17
        v0.1.18
        v0.1.19
        v0.1.20
        v0.1.21
        v0.1.22
        v0.1.23
        v0.1.24
        v0.1.25
        v0.1.26
        v0.1.27
        v0.1.28
        v0.1.29
        v0.1.30
        v0.1.31
        v0.1.32
        v0.1.33
        v0.1.90
        v0.1.91
        v0.1.92
        v0.1.93
        v0.1.94
        v0.1.95
        v0.1.96
        v0.1.97
        v0.1.98
        v0.1.99
       v0.1.100
       v0.1.101
       v0.1.102
       v0.1.103
       v0.1.104
         v0.2.0
         v0.2.1
         v0.2.2
         v0.2.3
         v0.2.4
         v0.2.5
         v0.2.6
         v0.3.0
         v0.3.1
         v0.3.2
         v0.3.3
         v0.3.4
         v0.3.5
         v0.3.6
         v0.3.7
         v0.3.8
         v0.4.0
         v0.4.1
         v0.4.2
         v0.4.3
         v0.4.4
         v0.4.5
         v0.4.6
         v0.4.7
         v0.4.8
         v0.4.9
        v0.4.10
        v0.4.11
        v0.4.12
         v0.5.0
         v0.5.1
         v0.5.2
         v0.5.3
         v0.5.4
         v0.5.5
         v0.5.6
         v0.5.7
         v0.5.8
         v0.5.9
        v0.5.10
         v0.6.0
         v0.6.1
         v0.6.2
         v0.6.3
         v0.6.4
         v0.6.5
         v0.6.6
         v0.6.7
         v0.6.8
         v0.6.9
        v0.6.10
        v0.6.11
        v0.6.12
        v0.6.13
        v0.6.14
        v0.6.15
        v0.6.16
        v0.6.17
        v0.6.18
        v0.6.19
        v0.6.20
        v0.6.21
         v0.7.0
         v0.7.1
         v0.7.2
         v0.7.3
         v0.7.4
         v0.7.5
         v0.7.6
         v0.7.7
         v0.7.8
         v0.7.9
        v0.7.10
        v0.7.11
        v0.7.12
         v0.8.0
         v0.8.1
         v0.8.2
         v0.8.3
         v0.8.4
         v0.8.5
         v0.8.6
         v0.8.7
         v0.8.8
         v0.8.9
        v0.8.10
        v0.8.11
        v0.8.12
        v0.8.13
        v0.8.14
        v0.8.15
        v0.8.16
        v0.8.17
        v0.8.18
        v0.8.19
        v0.8.20
        v0.8.21
        v0.8.22
        v0.8.23
        v0.8.24
        v0.8.25
        v0.8.26
        v0.8.27
        v0.8.28
         v0.9.0
         v0.9.1
         v0.9.2
         v0.9.3
         v0.9.4
         v0.9.5
         v0.9.6
         v0.9.7
         v0.9.8
         v0.9.9
        v0.9.10
        v0.9.11
        v0.9.12
        v0.10.0
        v0.10.1
        v0.10.2
        v0.10.3
        v0.10.4
        v0.10.5
        v0.10.6
        v0.10.7
        v0.10.8
        v0.10.9
       v0.10.10
       v0.10.11
       v0.10.12
       v0.10.13
       v0.10.14
       v0.10.15
       v0.10.16
       v0.10.17
       v0.10.18
       v0.10.19
       v0.10.20
       v0.10.21
       v0.10.22
       v0.10.23
       v0.10.24
       v0.10.25
       v0.10.26
       v0.10.27
       v0.10.28
       v0.10.29
       v0.10.30
       v0.10.31
       v0.10.32
       v0.10.33
       v0.10.34
       v0.10.35
       v0.10.36
       v0.10.37
       v0.10.38
       v0.10.39
       v0.10.40
       v0.10.41
       v0.10.42
       v0.10.43
       v0.10.44
       v0.10.45
       v0.10.46
       v0.10.47
       v0.10.48
        v0.11.0
        v0.11.1
        v0.11.2
        v0.11.3
        v0.11.4
        v0.11.5
        v0.11.6
        v0.11.7
        v0.11.8
        v0.11.9
       v0.11.10
       v0.11.11
       v0.11.12
       v0.11.13
       v0.11.14
       v0.11.15
       v0.11.16
        v0.12.0
        v0.12.1
        v0.12.2
        v0.12.3
        v0.12.4
        v0.12.5
        v0.12.6
        v0.12.7
        v0.12.8
        v0.12.9
       v0.12.10
       v0.12.11
       v0.12.12
       v0.12.13
       v0.12.14
       v0.12.15
       v0.12.16
       v0.12.17
       v0.12.18
    iojs-v1.0.0
    iojs-v1.0.1
    iojs-v1.0.2
    iojs-v1.0.3
    iojs-v1.0.4
    iojs-v1.1.0
    iojs-v1.2.0
    iojs-v1.3.0
    iojs-v1.4.1
    iojs-v1.4.2
    iojs-v1.4.3
    iojs-v1.5.0
    iojs-v1.5.1
    iojs-v1.6.0
    iojs-v1.6.1
    iojs-v1.6.2
    iojs-v1.6.3
    iojs-v1.6.4
    iojs-v1.7.1
    iojs-v1.8.1
    iojs-v1.8.2
    iojs-v1.8.3
    iojs-v1.8.4
    iojs-v2.0.0
    iojs-v2.0.1
    iojs-v2.0.2
    iojs-v2.1.0
    iojs-v2.2.0
    iojs-v2.2.1
    iojs-v2.3.0
    iojs-v2.3.1
    iojs-v2.3.2
    iojs-v2.3.3
    iojs-v2.3.4
    iojs-v2.4.0
    iojs-v2.5.0
    iojs-v3.0.0
    iojs-v3.1.0
    iojs-v3.2.0
    iojs-v3.3.0
    iojs-v3.3.1
         v4.0.0
         v4.1.0
         v4.1.1
         v4.1.2
         v4.2.0   (LTS: Argon)
         v4.2.1   (LTS: Argon)
         v4.2.2   (LTS: Argon)
         v4.2.3   (LTS: Argon)
         v4.2.4   (LTS: Argon)
         v4.2.5   (LTS: Argon)
         v4.2.6   (LTS: Argon)
         v4.3.0   (LTS: Argon)
         v4.3.1   (LTS: Argon)
         v4.3.2   (LTS: Argon)
         v4.4.0   (LTS: Argon)
         v4.4.1   (LTS: Argon)
         v4.4.2   (LTS: Argon)
         v4.4.3   (LTS: Argon)
         v4.4.4   (LTS: Argon)
         v4.4.5   (LTS: Argon)
         v4.4.6   (LTS: Argon)
         v4.4.7   (LTS: Argon)
         v4.5.0   (LTS: Argon)
         v4.6.0   (LTS: Argon)
         v4.6.1   (LTS: Argon)
         v4.6.2   (LTS: Argon)
         v4.7.0   (LTS: Argon)
         v4.7.1   (LTS: Argon)
         v4.7.2   (LTS: Argon)
         v4.7.3   (LTS: Argon)
         v4.8.0   (LTS: Argon)
         v4.8.1   (LTS: Argon)
         v4.8.2   (LTS: Argon)
         v4.8.3   (LTS: Argon)
         v4.8.4   (LTS: Argon)
         v4.8.5   (LTS: Argon)
         v4.8.6   (LTS: Argon)
         v4.8.7   (LTS: Argon)
         v4.9.0   (LTS: Argon)
         v4.9.1   (Latest LTS: Argon)
         v5.0.0
         v5.1.0
         v5.1.1
         v5.2.0
         v5.3.0
         v5.4.0
         v5.4.1
         v5.5.0
         v5.6.0
         v5.7.0
         v5.7.1
         v5.8.0
         v5.9.0
         v5.9.1
        v5.10.0
        v5.10.1
        v5.11.0
        v5.11.1
        v5.12.0
         v6.0.0
         v6.1.0
         v6.2.0
         v6.2.1
         v6.2.2
         v6.3.0
         v6.3.1
         v6.4.0
         v6.5.0
         v6.6.0
         v6.7.0
         v6.8.0
         v6.8.1
         v6.9.0   (LTS: Boron)
         v6.9.1   (LTS: Boron)
         v6.9.2   (LTS: Boron)
         v6.9.3   (LTS: Boron)
         v6.9.4   (LTS: Boron)
         v6.9.5   (LTS: Boron)
        v6.10.0   (LTS: Boron)
        v6.10.1   (LTS: Boron)
        v6.10.2   (LTS: Boron)
        v6.10.3   (LTS: Boron)
        v6.11.0   (LTS: Boron)
        v6.11.1   (LTS: Boron)
        v6.11.2   (LTS: Boron)
        v6.11.3   (LTS: Boron)
        v6.11.4   (LTS: Boron)
        v6.11.5   (LTS: Boron)
        v6.12.0   (LTS: Boron)
        v6.12.1   (LTS: Boron)
        v6.12.2   (LTS: Boron)
        v6.12.3   (LTS: Boron)
        v6.13.0   (LTS: Boron)
        v6.13.1   (LTS: Boron)
        v6.14.0   (LTS: Boron)
        v6.14.1   (LTS: Boron)
        v6.14.2   (LTS: Boron)
        v6.14.3   (LTS: Boron)
        v6.14.4   (LTS: Boron)
        v6.15.0   (LTS: Boron)
        v6.15.1   (LTS: Boron)
        v6.16.0   (LTS: Boron)
        v6.17.0   (LTS: Boron)
        v6.17.1   (Latest LTS: Boron)
         v7.0.0
         v7.1.0
         v7.2.0
         v7.2.1
         v7.3.0
         v7.4.0
         v7.5.0
         v7.6.0
         v7.7.0
         v7.7.1
         v7.7.2
         v7.7.3
         v7.7.4
         v7.8.0
         v7.9.0
        v7.10.0
        v7.10.1
         v8.0.0
         v8.1.0
         v8.1.1
         v8.1.2
         v8.1.3
         v8.1.4
         v8.2.0
         v8.2.1
         v8.3.0
         v8.4.0
         v8.5.0
         v8.6.0
         v8.7.0
         v8.8.0
         v8.8.1
         v8.9.0   (LTS: Carbon)
         v8.9.1   (LTS: Carbon)
         v8.9.2   (LTS: Carbon)
         v8.9.3   (LTS: Carbon)
         v8.9.4   (LTS: Carbon)
        v8.10.0   (LTS: Carbon)
        v8.11.0   (LTS: Carbon)
        v8.11.1   (LTS: Carbon)
        v8.11.2   (LTS: Carbon)
        v8.11.3   (LTS: Carbon)
        v8.11.4   (LTS: Carbon)
        v8.12.0   (LTS: Carbon)
        v8.13.0   (LTS: Carbon)
        v8.14.0   (LTS: Carbon)
        v8.14.1   (LTS: Carbon)
        v8.15.0   (LTS: Carbon)
        v8.15.1   (LTS: Carbon)
        v8.16.0   (LTS: Carbon)
        v8.16.1   (LTS: Carbon)
        v8.16.2   (LTS: Carbon)
        v8.17.0   (Latest LTS: Carbon)
         v9.0.0
         v9.1.0
         v9.2.0
         v9.2.1
         v9.3.0
         v9.4.0
         v9.5.0
         v9.6.0
         v9.6.1
         v9.7.0
         v9.7.1
         v9.8.0
         v9.9.0
        v9.10.0
        v9.10.1
        v9.11.0
        v9.11.1
        v9.11.2
        v10.0.0
        v10.1.0
        v10.2.0
        v10.2.1
        v10.3.0
        v10.4.0
        v10.4.1
        v10.5.0
        v10.6.0
        v10.7.0
        v10.8.0
        v10.9.0
       v10.10.0
       v10.11.0
       v10.12.0
       v10.13.0   (LTS: Dubnium)
       v10.14.0   (LTS: Dubnium)
       v10.14.1   (LTS: Dubnium)
       v10.14.2   (LTS: Dubnium)
       v10.15.0   (LTS: Dubnium)
       v10.15.1   (LTS: Dubnium)
       v10.15.2   (LTS: Dubnium)
       v10.15.3   (LTS: Dubnium)
       v10.16.0   (LTS: Dubnium)
       v10.16.1   (LTS: Dubnium)
       v10.16.2   (LTS: Dubnium)
       v10.16.3   (LTS: Dubnium)
       v10.17.0   (LTS: Dubnium)
       v10.18.0   (LTS: Dubnium)
       v10.18.1   (LTS: Dubnium)
       v10.19.0   (LTS: Dubnium)
       v10.20.0   (LTS: Dubnium)
       v10.20.1   (LTS: Dubnium)
       v10.21.0   (LTS: Dubnium)
       v10.22.0   (LTS: Dubnium)
       v10.22.1   (LTS: Dubnium)
       v10.23.0   (LTS: Dubnium)
       v10.23.1   (LTS: Dubnium)
       v10.23.2   (LTS: Dubnium)
       v10.23.3   (LTS: Dubnium)
       v10.24.0   (LTS: Dubnium)
       v10.24.1   (Latest LTS: Dubnium)
        v11.0.0
        v11.1.0
        v11.2.0
        v11.3.0
        v11.4.0
        v11.5.0
        v11.6.0
        v11.7.0
        v11.8.0
        v11.9.0
       v11.10.0
       v11.10.1
       v11.11.0
       v11.12.0
       v11.13.0
       v11.14.0
       v11.15.0
        v12.0.0
        v12.1.0
        v12.2.0
        v12.3.0
        v12.3.1
        v12.4.0
        v12.5.0
        v12.6.0
        v12.7.0
        v12.8.0
        v12.8.1
        v12.9.0
        v12.9.1
       v12.10.0
       v12.11.0
       v12.11.1
       v12.12.0
       v12.13.0   (LTS: Erbium)
       v12.13.1   (LTS: Erbium)
       v12.14.0   (LTS: Erbium)
       v12.14.1   (LTS: Erbium)
       v12.15.0   (LTS: Erbium)
       v12.16.0   (LTS: Erbium)
       v12.16.1   (LTS: Erbium)
       v12.16.2   (LTS: Erbium)
       v12.16.3   (LTS: Erbium)
       v12.17.0   (LTS: Erbium)
       v12.18.0   (LTS: Erbium)
       v12.18.1   (LTS: Erbium)
       v12.18.2   (LTS: Erbium)
       v12.18.3   (LTS: Erbium)
       v12.18.4   (LTS: Erbium)
       v12.19.0   (LTS: Erbium)
       v12.19.1   (LTS: Erbium)
       v12.20.0   (LTS: Erbium)
       v12.20.1   (LTS: Erbium)
       v12.20.2   (LTS: Erbium)
       v12.21.0   (LTS: Erbium)
       v12.22.0   (LTS: Erbium)
       v12.22.1   (LTS: Erbium)
       v12.22.2   (LTS: Erbium)
       v12.22.3   (LTS: Erbium)
       v12.22.4   (LTS: Erbium)
       v12.22.5   (LTS: Erbium)
       v12.22.6   (LTS: Erbium)
       v12.22.7   (LTS: Erbium)
       v12.22.8   (LTS: Erbium)
       v12.22.9   (LTS: Erbium)
      v12.22.10   (LTS: Erbium)
      v12.22.11   (LTS: Erbium)
      v12.22.12   (Latest LTS: Erbium)
        v13.0.0
        v13.0.1
        v13.1.0
        v13.2.0
        v13.3.0
        v13.4.0
        v13.5.0
        v13.6.0
        v13.7.0
        v13.8.0
        v13.9.0
       v13.10.0
       v13.10.1
       v13.11.0
       v13.12.0
       v13.13.0
       v13.14.0
        v14.0.0
        v14.1.0
        v14.2.0
        v14.3.0
        v14.4.0
        v14.5.0
        v14.6.0
        v14.7.0
        v14.8.0
        v14.9.0
       v14.10.0
       v14.10.1
       v14.11.0
       v14.12.0
       v14.13.0
       v14.13.1
       v14.14.0
       v14.15.0   (LTS: Fermium)
       v14.15.1   (LTS: Fermium)
       v14.15.2   (LTS: Fermium)
       v14.15.3   (LTS: Fermium)
       v14.15.4   (LTS: Fermium)
       v14.15.5   (LTS: Fermium)
       v14.16.0   (LTS: Fermium)
       v14.16.1   (LTS: Fermium)
       v14.17.0   (LTS: Fermium)
       v14.17.1   (LTS: Fermium)
       v14.17.2   (LTS: Fermium)
       v14.17.3   (LTS: Fermium)
       v14.17.4   (LTS: Fermium)
       v14.17.5   (LTS: Fermium)
       v14.17.6   (LTS: Fermium)
       v14.18.0   (LTS: Fermium)
       v14.18.1   (LTS: Fermium)
       v14.18.2   (LTS: Fermium)
       v14.18.3   (LTS: Fermium)
       v14.19.0   (LTS: Fermium)
       v14.19.1   (LTS: Fermium)
       v14.19.2   (LTS: Fermium)
       v14.19.3   (LTS: Fermium)
       v14.20.0   (LTS: Fermium)
       v14.20.1   (LTS: Fermium)
       v14.21.0   (LTS: Fermium)
       v14.21.1   (LTS: Fermium)
       v14.21.2   (LTS: Fermium)
       v14.21.3   (Latest LTS: Fermium)
        v15.0.0
        v15.0.1
        v15.1.0
        v15.2.0
        v15.2.1
        v15.3.0
        v15.4.0
        v15.5.0
        v15.5.1
        v15.6.0
        v15.7.0
        v15.8.0
        v15.9.0
       v15.10.0
       v15.11.0
       v15.12.0
       v15.13.0
       v15.14.0
        v16.0.0
        v16.1.0
        v16.2.0
        v16.3.0
        v16.4.0
        v16.4.1
        v16.4.2
        v16.5.0
        v16.6.0
        v16.6.1
        v16.6.2
        v16.7.0
        v16.8.0
        v16.9.0
        v16.9.1
       v16.10.0
       v16.11.0
       v16.11.1
       v16.12.0
       v16.13.0   (LTS: Gallium)
       v16.13.1   (LTS: Gallium)
       v16.13.2   (LTS: Gallium)
       v16.14.0   (LTS: Gallium)
       v16.14.1   (LTS: Gallium)
       v16.14.2   (LTS: Gallium)
       v16.15.0   (LTS: Gallium)
       v16.15.1   (LTS: Gallium)
       v16.16.0   (LTS: Gallium)
       v16.17.0   (LTS: Gallium)
       v16.17.1   (LTS: Gallium)
       v16.18.0   (LTS: Gallium)
       v16.18.1   (LTS: Gallium)
       v16.19.0   (LTS: Gallium)
       v16.19.1   (LTS: Gallium)
       v16.20.0   (LTS: Gallium)
       v16.20.1   (LTS: Gallium)
       v16.20.2   (Latest LTS: Gallium)
        v17.0.0
        v17.0.1
        v17.1.0
        v17.2.0
        v17.3.0
        v17.3.1
        v17.4.0
        v17.5.0
        v17.6.0
        v17.7.0
        v17.7.1
        v17.7.2
        v17.8.0
        v17.9.0
        v17.9.1
        v18.0.0
        v18.1.0
        v18.2.0
        v18.3.0
        v18.4.0
        v18.5.0
        v18.6.0
        v18.7.0
        v18.8.0
        v18.9.0
        v18.9.1
       v18.10.0
       v18.11.0
       v18.12.0   (LTS: Hydrogen)
       v18.12.1   (LTS: Hydrogen)
       v18.13.0   (LTS: Hydrogen)
       v18.14.0   (LTS: Hydrogen)
       v18.14.1   (LTS: Hydrogen)
       v18.14.2   (LTS: Hydrogen)
       v18.15.0   (LTS: Hydrogen)
       v18.16.0   (LTS: Hydrogen)
       v18.16.1   (LTS: Hydrogen)
       v18.17.0   (LTS: Hydrogen)
       v18.17.1   (LTS: Hydrogen)
       v18.18.0   (LTS: Hydrogen)
       v18.18.1   (LTS: Hydrogen)
       v18.18.2   (LTS: Hydrogen)
       v18.19.0   (LTS: Hydrogen)
       v18.19.1   (LTS: Hydrogen)
       v18.20.0   (LTS: Hydrogen)
       v18.20.1   (LTS: Hydrogen)
       v18.20.2   (LTS: Hydrogen)
       v18.20.3   (LTS: Hydrogen)
       v18.20.4   (Latest LTS: Hydrogen)
        v19.0.0
        v19.0.1
        v19.1.0
        v19.2.0
        v19.3.0
        v19.4.0
        v19.5.0
        v19.6.0
        v19.6.1
        v19.7.0
        v19.8.0
        v19.8.1
        v19.9.0
        v20.0.0
        v20.1.0
        v20.2.0
        v20.3.0
        v20.3.1
        v20.4.0
        v20.5.0
        v20.5.1
        v20.6.0
        v20.6.1
        v20.7.0
        v20.8.0
        v20.8.1
        v20.9.0   (LTS: Iron)
       v20.10.0   (LTS: Iron)
       v20.11.0   (LTS: Iron)
       v20.11.1   (LTS: Iron)
       v20.12.0   (LTS: Iron)
       v20.12.1   (LTS: Iron)
       v20.12.2   (LTS: Iron)
       v20.13.0   (LTS: Iron)
       v20.13.1   (LTS: Iron)
       v20.14.0   (LTS: Iron)
       v20.15.0   (LTS: Iron)
       v20.15.1   (LTS: Iron)
       v20.16.0   (Latest LTS: Iron)
        v21.0.0
        v21.1.0
        v21.2.0
        v21.3.0
        v21.4.0
        v21.5.0
        v21.6.0
        v21.6.1
        v21.6.2
        v21.7.0
        v21.7.1
        v21.7.2
        v21.7.3
        v22.0.0
        v22.1.0
        v22.2.0
        v22.3.0
        v22.4.0
        v22.4.1
        v22.5.0
        v22.5.1
        v22.6.0
root@e0b474ad133b:/# nvm install v14.10.0
Downloading and installing node v14.10.0...
Downloading https://nodejs.org/dist/v14.10.0/node-v14.10.0-linux-x64.tar.gz...
################################################################################################################################################################# 100.0%
Computing checksum with sha256sum
Checksums matched!
Now using node v14.10.0 (npm v6.14.8)
Creating default alias: default -> v14.10.0
root@e0b474ad133b:/# nvm install lts/hydrogen
Downloading and installing node v18.20.4...
Downloading https://nodejs.org/dist/v18.20.4/node-v18.20.4-linux-x64.tar.gz...
################################################################################################################################################################# 100.0%
Computing checksum with sha256sum
Checksums matched!
Now using node v18.20.4 (npm v10.7.0)
root@e0b474ad133b:/# nvm use v14.10.0
Now using node v14.10.0 (npm v6.14.8)
root@e0b474ad133b:/# sudo apt remove nodejs
bash: sudo: command not found
root@e0b474ad133b:/# sudo apt purge nodejs
bash: sudo: command not found
root@e0b474ad133b:/# apt-get update
Hit:1 http://archive.ubuntu.com/ubuntu noble InRelease
Hit:2 http://security.ubuntu.com/ubuntu noble-security InRelease
Hit:3 http://archive.ubuntu.com/ubuntu noble-updates InRelease
Hit:4 http://archive.ubuntu.com/ubuntu noble-backports InRelease
Reading package lists... Done
root@e0b474ad133b:/# apt-get install -y curl
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
curl is already the newest version (8.5.0-2ubuntu10.2).
0 upgraded, 0 newly installed, 0 to remove and 2 not upgraded.
root@e0b474ad133b:/# yum install -y curl
bash: yum: command not found
root@e0b474ad133b:/# dnf install -y curl
bash: dnf: command not found
root@e0b474ad133b:/# apk add --no-cache curl
bash: apk: command not found
root@e0b474ad133b:/# export NVM_DIR="$HOME/.nvm"
root@e0b474ad133b:/# [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
root@e0b474ad133b:/# nvm --version
0.39.3
root@e0b474ad133b:/# docker container ls
bash: docker: command not found
root@e0b474ad133b:/# docker container ls
bash: docker: command not found
root@e0b474ad133b:/# docker run -it --name test-node --rm ubuntu /bin/bash
bash: docker: command not found
root@e0b474ad133b:/# docker container ls
bash: docker: command not found
root@e0b474ad133b:/# docker ps
bash: docker: command not found
root@e0b474ad133b:/# docker container ls -a
bash: docker: command not found
root@e0b474ad133b:/# docker container ls --filter "status=exited"
bash: docker: command not found
root@e0b474ad133b:/# docker container ls -q
bash: docker: command not found
root@e0b474ad133b:/# docker container run
bash: docker: command not found
root@e0b474ad133b:/# docker --version
bash: docker: command not found
root@e0b474ad133b:/# sudo apt-get install docker
bash: sudo: command not found
root@e0b474ad133b:/# sudo apt-get update
bash: sudo: command not found
root@e0b474ad133b:/# docker container run -it -d --name test ubuntu
bash: docker: command not found
root@e0b474ad133b:/# docker exec -it test /bin/bash
bash: docker: command not found
root@e0b474ad133b:/# exit
exit
anchisa@IE3311-27:~$
anchisa@IE3311-27:~$ docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES
anchisa@IE3311-27:~$ docker run -it --name test-node -d ubuntu
8b3416ca70885a7342109a0845cb39c5f8d34b68aa87810518e45afe5f7e4ba1
anchisa@IE3311-27:~$ docker ps
CONTAINER ID   IMAGE     COMMAND       CREATED         STATUS         PORTS     NAMES
8b3416ca7088   ubuntu    "/bin/bash"   9 seconds ago   Up 8 seconds             test-node
anchisa@IE3311-27:~$ docker exec -it test-node /bin/bash
root@8b3416ca7088:/# sudo apt-get update && sudo apt-get upgrade -y
bash: sudo: command not found
root@8b3416ca7088:/# sudo apt-get update
bash: sudo: command not found
root@8b3416ca7088:/# sudo apt-get update
bash: sudo: command not found
root@8b3416ca7088:/# update
bash: update: command not found
root@8b3416ca7088:/# upgrade
bash: upgrade: command not found
root@8b3416ca7088:/# sudo apt-get update
bash: sudo: command not found
root@8b3416ca7088:/# sudo apk update
bash: sudo: command not found
root@8b3416ca7088:/# sudo apk upgrade
bash: sudo: command not found
root@8b3416ca7088:/# apt-get update
Get:1 http://archive.ubuntu.com/ubuntu noble InRelease [256 kB]
Get:2 http://security.ubuntu.com/ubuntu noble-security InRelease [126 kB]
Get:3 http://security.ubuntu.com/ubuntu noble-security/multiverse amd64 Packages [12.7 kB]
Get:4 http://archive.ubuntu.com/ubuntu noble-updates InRelease [126 kB]
Get:5 http://security.ubuntu.com/ubuntu noble-security/restricted amd64 Packages [299 kB]
Get:6 http://archive.ubuntu.com/ubuntu noble-backports InRelease [126 kB]
Get:7 http://security.ubuntu.com/ubuntu noble-security/universe amd64 Packages [333 kB]
Get:8 http://archive.ubuntu.com/ubuntu noble/universe amd64 Packages [19.3 MB]
Get:9 http://security.ubuntu.com/ubuntu noble-security/main amd64 Packages [360 kB]
Get:10 http://archive.ubuntu.com/ubuntu noble/multiverse amd64 Packages [331 kB]
Get:11 http://archive.ubuntu.com/ubuntu noble/restricted amd64 Packages [117 kB]
Get:12 http://archive.ubuntu.com/ubuntu noble/main amd64 Packages [1808 kB]
Get:13 http://archive.ubuntu.com/ubuntu noble-updates/universe amd64 Packages [428 kB]
Get:14 http://archive.ubuntu.com/ubuntu noble-updates/multiverse amd64 Packages [16.9 kB]
Get:15 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 Packages [429 kB]
Get:16 http://archive.ubuntu.com/ubuntu noble-updates/restricted amd64 Packages [299 kB]
Get:17 http://archive.ubuntu.com/ubuntu noble-backports/universe amd64 Packages [11.5 kB]
Fetched 24.4 MB in 8s (3097 kB/s)
Reading package lists... Done
root@8b3416ca7088:/# apt-get install -y curl
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
  ca-certificates krb5-locales libbrotli1 libcurl4t64 libgssapi-krb5-2 libk5crypto3 libkeyutils1 libkrb5-3 libkrb5support0 libldap-common libldap2 libnghttp2-14
  libpsl5t64 librtmp1 libsasl2-2 libsasl2-modules libsasl2-modules-db libssh-4 libssl3t64 openssl publicsuffix
Suggested packages:
  krb5-doc krb5-user libsasl2-modules-gssapi-mit | libsasl2-modules-gssapi-heimdal libsasl2-modules-ldap libsasl2-modules-otp libsasl2-modules-sql
The following NEW packages will be installed:
  ca-certificates curl krb5-locales libbrotli1 libcurl4t64 libgssapi-krb5-2 libk5crypto3 libkeyutils1 libkrb5-3 libkrb5support0 libldap-common libldap2 libnghttp2-14
  libpsl5t64 librtmp1 libsasl2-2 libsasl2-modules libsasl2-modules-db libssh-4 openssl publicsuffix
The following packages will be upgraded:
  libssl3t64
1 upgraded, 21 newly installed, 0 to remove and 2 not upgraded.
Need to get 5503 kB of archives.
After this operation, 9198 kB of additional disk space will be used.
Get:1 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libssl3t64 amd64 3.0.13-0ubuntu3.2 [1940 kB]
Get:2 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 openssl amd64 3.0.13-0ubuntu3.2 [1002 kB]
Get:3 http://archive.ubuntu.com/ubuntu noble/main amd64 ca-certificates all 20240203 [159 kB]
Get:4 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 krb5-locales all 1.20.1-6ubuntu2.1 [14.0 kB]
Get:5 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libkrb5support0 amd64 1.20.1-6ubuntu2.1 [33.6 kB]
Get:6 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libk5crypto3 amd64 1.20.1-6ubuntu2.1 [81.7 kB]
Get:7 http://archive.ubuntu.com/ubuntu noble/main amd64 libkeyutils1 amd64 1.6.3-3build1 [9490 B]
Get:8 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libkrb5-3 amd64 1.20.1-6ubuntu2.1 [347 kB]
Get:9 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libgssapi-krb5-2 amd64 1.20.1-6ubuntu2.1 [143 kB]
Get:10 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libnghttp2-14 amd64 1.59.0-1ubuntu0.1 [74.3 kB]
Get:11 http://archive.ubuntu.com/ubuntu noble/main amd64 libpsl5t64 amd64 0.21.2-1.1build1 [57.1 kB]
Get:12 http://archive.ubuntu.com/ubuntu noble/main amd64 publicsuffix all 20231001.0357-0.1 [129 kB]
Get:13 http://archive.ubuntu.com/ubuntu noble/main amd64 libbrotli1 amd64 1.1.0-2build2 [331 kB]
Get:14 http://archive.ubuntu.com/ubuntu noble/main amd64 libsasl2-modules-db amd64 2.1.28+dfsg1-5ubuntu3 [20.3 kB]
Get:15 http://archive.ubuntu.com/ubuntu noble/main amd64 libsasl2-2 amd64 2.1.28+dfsg1-5ubuntu3 [53.2 kB]
Get:16 http://archive.ubuntu.com/ubuntu noble/main amd64 libldap2 amd64 2.6.7+dfsg-1~exp1ubuntu8 [195 kB]
Get:17 http://archive.ubuntu.com/ubuntu noble/main amd64 librtmp1 amd64 2.4+20151223.gitfa8646d.1-2build7 [56.3 kB]
Get:18 http://archive.ubuntu.com/ubuntu noble/main amd64 libssh-4 amd64 0.10.6-2build2 [188 kB]
Get:19 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libcurl4t64 amd64 8.5.0-2ubuntu10.2 [341 kB]
Get:20 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 curl amd64 8.5.0-2ubuntu10.2 [227 kB]
Get:21 http://archive.ubuntu.com/ubuntu noble/main amd64 libldap-common all 2.6.7+dfsg-1~exp1ubuntu8 [31.4 kB]
Get:22 http://archive.ubuntu.com/ubuntu noble/main amd64 libsasl2-modules amd64 2.1.28+dfsg1-5ubuntu3 [69.7 kB]
Fetched 5503 kB in 4s (1477 kB/s)
debconf: delaying package configuration, since apt-utils is not installed
(Reading database ... 4376 files and directories currently installed.)
Preparing to unpack .../libssl3t64_3.0.13-0ubuntu3.2_amd64.deb ...
Unpacking libssl3t64:amd64 (3.0.13-0ubuntu3.2) over (3.0.13-0ubuntu3.1) ...
Setting up libssl3t64:amd64 (3.0.13-0ubuntu3.2) ...
Selecting previously unselected package openssl.
(Reading database ... 4376 files and directories currently installed.)
Preparing to unpack .../00-openssl_3.0.13-0ubuntu3.2_amd64.deb ...
Unpacking openssl (3.0.13-0ubuntu3.2) ...
Selecting previously unselected package ca-certificates.
Preparing to unpack .../01-ca-certificates_20240203_all.deb ...
Unpacking ca-certificates (20240203) ...
Selecting previously unselected package krb5-locales.
Preparing to unpack .../02-krb5-locales_1.20.1-6ubuntu2.1_all.deb ...
Unpacking krb5-locales (1.20.1-6ubuntu2.1) ...
Selecting previously unselected package libkrb5support0:amd64.
Preparing to unpack .../03-libkrb5support0_1.20.1-6ubuntu2.1_amd64.deb ...
Unpacking libkrb5support0:amd64 (1.20.1-6ubuntu2.1) ...
Selecting previously unselected package libk5crypto3:amd64.
Preparing to unpack .../04-libk5crypto3_1.20.1-6ubuntu2.1_amd64.deb ...
Unpacking libk5crypto3:amd64 (1.20.1-6ubuntu2.1) ...
Selecting previously unselected package libkeyutils1:amd64.
Preparing to unpack .../05-libkeyutils1_1.6.3-3build1_amd64.deb ...
Unpacking libkeyutils1:amd64 (1.6.3-3build1) ...
Selecting previously unselected package libkrb5-3:amd64.
Preparing to unpack .../06-libkrb5-3_1.20.1-6ubuntu2.1_amd64.deb ...
Unpacking libkrb5-3:amd64 (1.20.1-6ubuntu2.1) ...
Selecting previously unselected package libgssapi-krb5-2:amd64.
Preparing to unpack .../07-libgssapi-krb5-2_1.20.1-6ubuntu2.1_amd64.deb ...
Unpacking libgssapi-krb5-2:amd64 (1.20.1-6ubuntu2.1) ...
Selecting previously unselected package libnghttp2-14:amd64.
Preparing to unpack .../08-libnghttp2-14_1.59.0-1ubuntu0.1_amd64.deb ...
Unpacking libnghttp2-14:amd64 (1.59.0-1ubuntu0.1) ...
Selecting previously unselected package libpsl5t64:amd64.
Preparing to unpack .../09-libpsl5t64_0.21.2-1.1build1_amd64.deb ...
Unpacking libpsl5t64:amd64 (0.21.2-1.1build1) ...
Selecting previously unselected package publicsuffix.
Preparing to unpack .../10-publicsuffix_20231001.0357-0.1_all.deb ...
Unpacking publicsuffix (20231001.0357-0.1) ...
Selecting previously unselected package libbrotli1:amd64.
Preparing to unpack .../11-libbrotli1_1.1.0-2build2_amd64.deb ...
Unpacking libbrotli1:amd64 (1.1.0-2build2) ...
Selecting previously unselected package libsasl2-modules-db:amd64.
Preparing to unpack .../12-libsasl2-modules-db_2.1.28+dfsg1-5ubuntu3_amd64.deb ...
Unpacking libsasl2-modules-db:amd64 (2.1.28+dfsg1-5ubuntu3) ...
Selecting previously unselected package libsasl2-2:amd64.
Preparing to unpack .../13-libsasl2-2_2.1.28+dfsg1-5ubuntu3_amd64.deb ...
Unpacking libsasl2-2:amd64 (2.1.28+dfsg1-5ubuntu3) ...
Selecting previously unselected package libldap2:amd64.
Preparing to unpack .../14-libldap2_2.6.7+dfsg-1~exp1ubuntu8_amd64.deb ...
Unpacking libldap2:amd64 (2.6.7+dfsg-1~exp1ubuntu8) ...
Selecting previously unselected package librtmp1:amd64.
Preparing to unpack .../15-librtmp1_2.4+20151223.gitfa8646d.1-2build7_amd64.deb ...
Unpacking librtmp1:amd64 (2.4+20151223.gitfa8646d.1-2build7) ...
Selecting previously unselected package libssh-4:amd64.
Preparing to unpack .../16-libssh-4_0.10.6-2build2_amd64.deb ...
Unpacking libssh-4:amd64 (0.10.6-2build2) ...
Selecting previously unselected package libcurl4t64:amd64.
Preparing to unpack .../17-libcurl4t64_8.5.0-2ubuntu10.2_amd64.deb ...
Unpacking libcurl4t64:amd64 (8.5.0-2ubuntu10.2) ...
Selecting previously unselected package curl.
Preparing to unpack .../18-curl_8.5.0-2ubuntu10.2_amd64.deb ...
Unpacking curl (8.5.0-2ubuntu10.2) ...
Selecting previously unselected package libldap-common.
Preparing to unpack .../19-libldap-common_2.6.7+dfsg-1~exp1ubuntu8_all.deb ...
Unpacking libldap-common (2.6.7+dfsg-1~exp1ubuntu8) ...
Selecting previously unselected package libsasl2-modules:amd64.
Preparing to unpack .../20-libsasl2-modules_2.1.28+dfsg1-5ubuntu3_amd64.deb ...
Unpacking libsasl2-modules:amd64 (2.1.28+dfsg1-5ubuntu3) ...
Setting up libkeyutils1:amd64 (1.6.3-3build1) ...
Setting up libbrotli1:amd64 (1.1.0-2build2) ...
Setting up libsasl2-modules:amd64 (2.1.28+dfsg1-5ubuntu3) ...
Setting up libpsl5t64:amd64 (0.21.2-1.1build1) ...
Setting up libnghttp2-14:amd64 (1.59.0-1ubuntu0.1) ...
Setting up krb5-locales (1.20.1-6ubuntu2.1) ...
Setting up libldap-common (2.6.7+dfsg-1~exp1ubuntu8) ...
Setting up libkrb5support0:amd64 (1.20.1-6ubuntu2.1) ...
Setting up libsasl2-modules-db:amd64 (2.1.28+dfsg1-5ubuntu3) ...
Setting up librtmp1:amd64 (2.4+20151223.gitfa8646d.1-2build7) ...
Setting up libk5crypto3:amd64 (1.20.1-6ubuntu2.1) ...
Setting up libsasl2-2:amd64 (2.1.28+dfsg1-5ubuntu3) ...
Setting up libkrb5-3:amd64 (1.20.1-6ubuntu2.1) ...
Setting up openssl (3.0.13-0ubuntu3.2) ...
Setting up publicsuffix (20231001.0357-0.1) ...
Setting up libldap2:amd64 (2.6.7+dfsg-1~exp1ubuntu8) ...
Setting up ca-certificates (20240203) ...
debconf: unable to initialize frontend: Dialog
debconf: (No usable dialog-like program is installed, so the dialog based frontend cannot be used. at /usr/share/perl5/Debconf/FrontEnd/Dialog.pm line 79.)
debconf: falling back to frontend: Readline
debconf: unable to initialize frontend: Readline
debconf: (Can't locate Term/ReadLine.pm in @INC (you may need to install the Term::ReadLine module) (@INC entries checked: /etc/perl /usr/local/lib/x86_64-linux-gnu/perl/5.38.2 /usr/local/share/perl/5.38.2 /usr/lib/x86_64-linux-gnu/perl5/5.38 /usr/share/perl5 /usr/lib/x86_64-linux-gnu/perl-base /usr/lib/x86_64-linux-gnu/perl/5.38 /usr/share/perl/5.38 /usr/local/lib/site_perl) at /usr/share/perl5/Debconf/FrontEnd/Readline.pm line 8.)
debconf: falling back to frontend: Teletype
Updating certificates in /etc/ssl/certs...
146 added, 0 removed; done.
Setting up libgssapi-krb5-2:amd64 (1.20.1-6ubuntu2.1) ...
Setting up libssh-4:amd64 (0.10.6-2build2) ...
Setting up libcurl4t64:amd64 (8.5.0-2ubuntu10.2) ...
Setting up curl (8.5.0-2ubuntu10.2) ...
Processing triggers for libc-bin (2.39-0ubuntu8.2) ...
Processing triggers for ca-certificates (20240203) ...
Updating certificates in /etc/ssl/certs...
0 added, 0 removed; done.
Running hooks in /etc/ca-certificates/update.d...
done.
root@8b3416ca7088:/# docker exec -it test /bin/bash
bash: docker: command not found
root@8b3416ca7088:/# docker images
bash: docker: command not found
root@8b3416ca7088:/# apt install  curl
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
curl is already the newest version (8.5.0-2ubuntu10.2).
0 upgraded, 0 newly installed, 0 to remove and 2 not upgraded.
root@8b3416ca7088:/# apt install  nano
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
Suggested packages:
  hunspell
The following NEW packages will be installed:
  nano
0 upgraded, 1 newly installed, 0 to remove and 2 not upgraded.
Need to get 281 kB of archives.
After this operation, 856 kB of additional disk space will be used.
Get:1 http://archive.ubuntu.com/ubuntu noble/main amd64 nano amd64 7.2-2build1 [281 kB]
Fetched 281 kB in 1s (247 kB/s)
debconf: delaying package configuration, since apt-utils is not installed
Selecting previously unselected package nano.
(Reading database ... 5009 files and directories currently installed.)
Preparing to unpack .../nano_7.2-2build1_amd64.deb ...
Unpacking nano (7.2-2build1) ...
Setting up nano (7.2-2build1) ...
update-alternatives: using /bin/nano to provide /usr/bin/editor (editor) in auto mode
update-alternatives: warning: skip creation of /usr/share/man/man1/editor.1.gz because associated file /usr/share/man/man1/nano.1.gz (of link group editor) doesn't exist
update-alternatives: using /bin/nano to provide /usr/bin/pico (pico) in auto mode
update-alternatives: warning: skip creation of /usr/share/man/man1/pico.1.gz because associated file /usr/share/man/man1/nano.1.gz (of link group pico) doesn't exist
root@8b3416ca7088:/# curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100 15916  100 15916    0     0  36560      0 --:--:-- --:--:-- --:--:-- 36672
=> Downloading nvm as script to '/root/.nvm'

=> Appending nvm source string to /root/.bashrc
=> Appending bash_completion source string to /root/.bashrc
=> Close and reopen your terminal to start using nvm or run the following to use it now:

export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion
root@8b3416ca7088:/# source ~/.bashrc
root@8b3416ca7088:/# nvm list-remote
        v0.1.14
        v0.1.15
        v0.1.16
        v0.1.17
        v0.1.18
        v0.1.19
        v0.1.20
        v0.1.21
        v0.1.22
        v0.1.23
        v0.1.24
        v0.1.25
        v0.1.26
        v0.1.27
        v0.1.28
        v0.1.29
        v0.1.30
        v0.1.31
        v0.1.32
        v0.1.33
        v0.1.90
        v0.1.91
        v0.1.92
        v0.1.93
        v0.1.94
        v0.1.95
        v0.1.96
        v0.1.97
        v0.1.98
        v0.1.99
       v0.1.100
       v0.1.101
       v0.1.102
       v0.1.103
       v0.1.104
         v0.2.0
         v0.2.1
         v0.2.2
         v0.2.3
         v0.2.4
         v0.2.5
         v0.2.6
         v0.3.0
         v0.3.1
         v0.3.2
         v0.3.3
         v0.3.4
         v0.3.5
         v0.3.6
         v0.3.7
         v0.3.8
         v0.4.0
         v0.4.1
         v0.4.2
         v0.4.3
         v0.4.4
         v0.4.5
         v0.4.6
         v0.4.7
         v0.4.8
         v0.4.9
        v0.4.10
        v0.4.11
        v0.4.12
         v0.5.0
         v0.5.1
         v0.5.2
         v0.5.3
         v0.5.4
         v0.5.5
         v0.5.6
         v0.5.7
         v0.5.8
         v0.5.9
        v0.5.10
         v0.6.0
         v0.6.1
         v0.6.2
         v0.6.3
         v0.6.4
         v0.6.5
         v0.6.6
         v0.6.7
         v0.6.8
         v0.6.9
        v0.6.10
        v0.6.11
        v0.6.12
        v0.6.13
        v0.6.14
        v0.6.15
        v0.6.16
        v0.6.17
        v0.6.18
        v0.6.19
        v0.6.20
        v0.6.21
         v0.7.0
         v0.7.1
         v0.7.2
         v0.7.3
         v0.7.4
         v0.7.5
         v0.7.6
         v0.7.7
         v0.7.8
         v0.7.9
        v0.7.10
        v0.7.11
        v0.7.12
         v0.8.0
         v0.8.1
         v0.8.2
         v0.8.3
         v0.8.4
         v0.8.5
         v0.8.6
         v0.8.7
         v0.8.8
         v0.8.9
        v0.8.10
        v0.8.11
        v0.8.12
        v0.8.13
        v0.8.14
        v0.8.15
        v0.8.16
        v0.8.17
        v0.8.18
        v0.8.19
        v0.8.20
        v0.8.21
        v0.8.22
        v0.8.23
        v0.8.24
        v0.8.25
        v0.8.26
        v0.8.27
        v0.8.28
         v0.9.0
         v0.9.1
         v0.9.2
         v0.9.3
         v0.9.4
         v0.9.5
         v0.9.6
         v0.9.7
         v0.9.8
         v0.9.9
        v0.9.10
        v0.9.11
        v0.9.12
        v0.10.0
        v0.10.1
        v0.10.2
        v0.10.3
        v0.10.4
        v0.10.5
        v0.10.6
        v0.10.7
        v0.10.8
        v0.10.9
       v0.10.10
       v0.10.11
       v0.10.12
       v0.10.13
       v0.10.14
       v0.10.15
       v0.10.16
       v0.10.17
       v0.10.18
       v0.10.19
       v0.10.20
       v0.10.21
       v0.10.22
       v0.10.23
       v0.10.24
       v0.10.25
       v0.10.26
       v0.10.27
       v0.10.28
       v0.10.29
       v0.10.30
       v0.10.31
       v0.10.32
       v0.10.33
       v0.10.34
       v0.10.35
       v0.10.36
       v0.10.37
       v0.10.38
       v0.10.39
       v0.10.40
       v0.10.41
       v0.10.42
       v0.10.43
       v0.10.44
       v0.10.45
       v0.10.46
       v0.10.47
       v0.10.48
        v0.11.0
        v0.11.1
        v0.11.2
        v0.11.3
        v0.11.4
        v0.11.5
        v0.11.6
        v0.11.7
        v0.11.8
        v0.11.9
       v0.11.10
       v0.11.11
       v0.11.12
       v0.11.13
       v0.11.14
       v0.11.15
       v0.11.16
        v0.12.0
        v0.12.1
        v0.12.2
        v0.12.3
        v0.12.4
        v0.12.5
        v0.12.6
        v0.12.7
        v0.12.8
        v0.12.9
       v0.12.10
       v0.12.11
       v0.12.12
       v0.12.13
       v0.12.14
       v0.12.15
       v0.12.16
       v0.12.17
       v0.12.18
    iojs-v1.0.0
    iojs-v1.0.1
    iojs-v1.0.2
    iojs-v1.0.3
    iojs-v1.0.4
    iojs-v1.1.0
    iojs-v1.2.0
    iojs-v1.3.0
    iojs-v1.4.1
    iojs-v1.4.2
    iojs-v1.4.3
    iojs-v1.5.0
    iojs-v1.5.1
    iojs-v1.6.0
    iojs-v1.6.1
    iojs-v1.6.2
    iojs-v1.6.3
    iojs-v1.6.4
    iojs-v1.7.1
    iojs-v1.8.1
    iojs-v1.8.2
    iojs-v1.8.3
    iojs-v1.8.4
    iojs-v2.0.0
    iojs-v2.0.1
    iojs-v2.0.2
    iojs-v2.1.0
    iojs-v2.2.0
    iojs-v2.2.1
    iojs-v2.3.0
    iojs-v2.3.1
    iojs-v2.3.2
    iojs-v2.3.3
    iojs-v2.3.4
    iojs-v2.4.0
    iojs-v2.5.0
    iojs-v3.0.0
    iojs-v3.1.0
    iojs-v3.2.0
    iojs-v3.3.0
    iojs-v3.3.1
         v4.0.0
         v4.1.0
         v4.1.1
         v4.1.2
         v4.2.0   (LTS: Argon)
         v4.2.1   (LTS: Argon)
         v4.2.2   (LTS: Argon)
         v4.2.3   (LTS: Argon)
         v4.2.4   (LTS: Argon)
         v4.2.5   (LTS: Argon)
         v4.2.6   (LTS: Argon)
         v4.3.0   (LTS: Argon)
         v4.3.1   (LTS: Argon)
         v4.3.2   (LTS: Argon)
         v4.4.0   (LTS: Argon)
         v4.4.1   (LTS: Argon)
         v4.4.2   (LTS: Argon)
         v4.4.3   (LTS: Argon)
         v4.4.4   (LTS: Argon)
         v4.4.5   (LTS: Argon)
         v4.4.6   (LTS: Argon)
         v4.4.7   (LTS: Argon)
         v4.5.0   (LTS: Argon)
         v4.6.0   (LTS: Argon)
         v4.6.1   (LTS: Argon)
         v4.6.2   (LTS: Argon)
         v4.7.0   (LTS: Argon)
         v4.7.1   (LTS: Argon)
         v4.7.2   (LTS: Argon)
         v4.7.3   (LTS: Argon)
         v4.8.0   (LTS: Argon)
         v4.8.1   (LTS: Argon)
         v4.8.2   (LTS: Argon)
         v4.8.3   (LTS: Argon)
         v4.8.4   (LTS: Argon)
         v4.8.5   (LTS: Argon)
         v4.8.6   (LTS: Argon)
         v4.8.7   (LTS: Argon)
         v4.9.0   (LTS: Argon)
         v4.9.1   (Latest LTS: Argon)
         v5.0.0
         v5.1.0
         v5.1.1
         v5.2.0
         v5.3.0
         v5.4.0
         v5.4.1
         v5.5.0
         v5.6.0
         v5.7.0
         v5.7.1
         v5.8.0
         v5.9.0
         v5.9.1
        v5.10.0
        v5.10.1
        v5.11.0
        v5.11.1
        v5.12.0
         v6.0.0
         v6.1.0
         v6.2.0
         v6.2.1
         v6.2.2
         v6.3.0
         v6.3.1
         v6.4.0
         v6.5.0
         v6.6.0
         v6.7.0
         v6.8.0
         v6.8.1
         v6.9.0   (LTS: Boron)
         v6.9.1   (LTS: Boron)
         v6.9.2   (LTS: Boron)
         v6.9.3   (LTS: Boron)
         v6.9.4   (LTS: Boron)
         v6.9.5   (LTS: Boron)
        v6.10.0   (LTS: Boron)
        v6.10.1   (LTS: Boron)
        v6.10.2   (LTS: Boron)
        v6.10.3   (LTS: Boron)
        v6.11.0   (LTS: Boron)
        v6.11.1   (LTS: Boron)
        v6.11.2   (LTS: Boron)
        v6.11.3   (LTS: Boron)
        v6.11.4   (LTS: Boron)
        v6.11.5   (LTS: Boron)
        v6.12.0   (LTS: Boron)
        v6.12.1   (LTS: Boron)
        v6.12.2   (LTS: Boron)
        v6.12.3   (LTS: Boron)
        v6.13.0   (LTS: Boron)
        v6.13.1   (LTS: Boron)
        v6.14.0   (LTS: Boron)
        v6.14.1   (LTS: Boron)
        v6.14.2   (LTS: Boron)
        v6.14.3   (LTS: Boron)
        v6.14.4   (LTS: Boron)
        v6.15.0   (LTS: Boron)
        v6.15.1   (LTS: Boron)
        v6.16.0   (LTS: Boron)
        v6.17.0   (LTS: Boron)
        v6.17.1   (Latest LTS: Boron)
         v7.0.0
         v7.1.0
         v7.2.0
         v7.2.1
         v7.3.0
         v7.4.0
         v7.5.0
         v7.6.0
         v7.7.0
         v7.7.1
         v7.7.2
         v7.7.3
         v7.7.4
         v7.8.0
         v7.9.0
        v7.10.0
        v7.10.1
         v8.0.0
         v8.1.0
         v8.1.1
         v8.1.2
         v8.1.3
         v8.1.4
         v8.2.0
         v8.2.1
         v8.3.0
         v8.4.0
         v8.5.0
         v8.6.0
         v8.7.0
         v8.8.0
         v8.8.1
         v8.9.0   (LTS: Carbon)
         v8.9.1   (LTS: Carbon)
         v8.9.2   (LTS: Carbon)
         v8.9.3   (LTS: Carbon)
         v8.9.4   (LTS: Carbon)
        v8.10.0   (LTS: Carbon)
        v8.11.0   (LTS: Carbon)
        v8.11.1   (LTS: Carbon)
        v8.11.2   (LTS: Carbon)
        v8.11.3   (LTS: Carbon)
        v8.11.4   (LTS: Carbon)
        v8.12.0   (LTS: Carbon)
        v8.13.0   (LTS: Carbon)
        v8.14.0   (LTS: Carbon)
        v8.14.1   (LTS: Carbon)
        v8.15.0   (LTS: Carbon)
        v8.15.1   (LTS: Carbon)
        v8.16.0   (LTS: Carbon)
        v8.16.1   (LTS: Carbon)
        v8.16.2   (LTS: Carbon)
        v8.17.0   (Latest LTS: Carbon)
         v9.0.0
         v9.1.0
         v9.2.0
         v9.2.1
         v9.3.0
         v9.4.0
         v9.5.0
         v9.6.0
         v9.6.1
         v9.7.0
         v9.7.1
         v9.8.0
         v9.9.0
        v9.10.0
        v9.10.1
        v9.11.0
        v9.11.1
        v9.11.2
        v10.0.0
        v10.1.0
        v10.2.0
        v10.2.1
        v10.3.0
        v10.4.0
        v10.4.1
        v10.5.0
        v10.6.0
        v10.7.0
        v10.8.0
        v10.9.0
       v10.10.0
       v10.11.0
       v10.12.0
       v10.13.0   (LTS: Dubnium)
       v10.14.0   (LTS: Dubnium)
       v10.14.1   (LTS: Dubnium)
       v10.14.2   (LTS: Dubnium)
       v10.15.0   (LTS: Dubnium)
       v10.15.1   (LTS: Dubnium)
       v10.15.2   (LTS: Dubnium)
       v10.15.3   (LTS: Dubnium)
       v10.16.0   (LTS: Dubnium)
       v10.16.1   (LTS: Dubnium)
       v10.16.2   (LTS: Dubnium)
       v10.16.3   (LTS: Dubnium)
       v10.17.0   (LTS: Dubnium)
       v10.18.0   (LTS: Dubnium)
       v10.18.1   (LTS: Dubnium)
       v10.19.0   (LTS: Dubnium)
       v10.20.0   (LTS: Dubnium)
       v10.20.1   (LTS: Dubnium)
       v10.21.0   (LTS: Dubnium)
       v10.22.0   (LTS: Dubnium)
       v10.22.1   (LTS: Dubnium)
       v10.23.0   (LTS: Dubnium)
       v10.23.1   (LTS: Dubnium)
       v10.23.2   (LTS: Dubnium)
       v10.23.3   (LTS: Dubnium)
       v10.24.0   (LTS: Dubnium)
       v10.24.1   (Latest LTS: Dubnium)
        v11.0.0
        v11.1.0
        v11.2.0
        v11.3.0
        v11.4.0
        v11.5.0
        v11.6.0
        v11.7.0
        v11.8.0
        v11.9.0
       v11.10.0
       v11.10.1
       v11.11.0
       v11.12.0
       v11.13.0
       v11.14.0
       v11.15.0
        v12.0.0
        v12.1.0
        v12.2.0
        v12.3.0
        v12.3.1
        v12.4.0
        v12.5.0
        v12.6.0
        v12.7.0
        v12.8.0
        v12.8.1
        v12.9.0
        v12.9.1
       v12.10.0
       v12.11.0
       v12.11.1
       v12.12.0
       v12.13.0   (LTS: Erbium)
       v12.13.1   (LTS: Erbium)
       v12.14.0   (LTS: Erbium)
       v12.14.1   (LTS: Erbium)
       v12.15.0   (LTS: Erbium)
       v12.16.0   (LTS: Erbium)
       v12.16.1   (LTS: Erbium)
       v12.16.2   (LTS: Erbium)
       v12.16.3   (LTS: Erbium)
       v12.17.0   (LTS: Erbium)
       v12.18.0   (LTS: Erbium)
       v12.18.1   (LTS: Erbium)
       v12.18.2   (LTS: Erbium)
       v12.18.3   (LTS: Erbium)
       v12.18.4   (LTS: Erbium)
       v12.19.0   (LTS: Erbium)
       v12.19.1   (LTS: Erbium)
       v12.20.0   (LTS: Erbium)
       v12.20.1   (LTS: Erbium)
       v12.20.2   (LTS: Erbium)
       v12.21.0   (LTS: Erbium)
       v12.22.0   (LTS: Erbium)
       v12.22.1   (LTS: Erbium)
       v12.22.2   (LTS: Erbium)
       v12.22.3   (LTS: Erbium)
       v12.22.4   (LTS: Erbium)
       v12.22.5   (LTS: Erbium)
       v12.22.6   (LTS: Erbium)
       v12.22.7   (LTS: Erbium)
       v12.22.8   (LTS: Erbium)
       v12.22.9   (LTS: Erbium)
      v12.22.10   (LTS: Erbium)
      v12.22.11   (LTS: Erbium)
      v12.22.12   (Latest LTS: Erbium)
        v13.0.0
        v13.0.1
        v13.1.0
        v13.2.0
        v13.3.0
        v13.4.0
        v13.5.0
        v13.6.0
        v13.7.0
        v13.8.0
        v13.9.0
       v13.10.0
       v13.10.1
       v13.11.0
       v13.12.0
       v13.13.0
       v13.14.0
        v14.0.0
        v14.1.0
        v14.2.0
        v14.3.0
        v14.4.0
        v14.5.0
        v14.6.0
        v14.7.0
        v14.8.0
        v14.9.0
       v14.10.0
       v14.10.1
       v14.11.0
       v14.12.0
       v14.13.0
       v14.13.1
       v14.14.0
       v14.15.0   (LTS: Fermium)
       v14.15.1   (LTS: Fermium)
       v14.15.2   (LTS: Fermium)
       v14.15.3   (LTS: Fermium)
       v14.15.4   (LTS: Fermium)
       v14.15.5   (LTS: Fermium)
       v14.16.0   (LTS: Fermium)
       v14.16.1   (LTS: Fermium)
       v14.17.0   (LTS: Fermium)
       v14.17.1   (LTS: Fermium)
       v14.17.2   (LTS: Fermium)
       v14.17.3   (LTS: Fermium)
       v14.17.4   (LTS: Fermium)
       v14.17.5   (LTS: Fermium)
       v14.17.6   (LTS: Fermium)
       v14.18.0   (LTS: Fermium)
       v14.18.1   (LTS: Fermium)
       v14.18.2   (LTS: Fermium)
       v14.18.3   (LTS: Fermium)
       v14.19.0   (LTS: Fermium)
       v14.19.1   (LTS: Fermium)
       v14.19.2   (LTS: Fermium)
       v14.19.3   (LTS: Fermium)
       v14.20.0   (LTS: Fermium)
       v14.20.1   (LTS: Fermium)
       v14.21.0   (LTS: Fermium)
       v14.21.1   (LTS: Fermium)
       v14.21.2   (LTS: Fermium)
       v14.21.3   (Latest LTS: Fermium)
        v15.0.0
        v15.0.1
        v15.1.0
        v15.2.0
        v15.2.1
        v15.3.0
        v15.4.0
        v15.5.0
        v15.5.1
        v15.6.0
        v15.7.0
        v15.8.0
        v15.9.0
       v15.10.0
       v15.11.0
       v15.12.0
       v15.13.0
       v15.14.0
        v16.0.0
        v16.1.0
        v16.2.0
        v16.3.0
        v16.4.0
        v16.4.1
        v16.4.2
        v16.5.0
        v16.6.0
        v16.6.1
        v16.6.2
        v16.7.0
        v16.8.0
        v16.9.0
        v16.9.1
       v16.10.0
       v16.11.0
       v16.11.1
       v16.12.0
       v16.13.0   (LTS: Gallium)
       v16.13.1   (LTS: Gallium)
       v16.13.2   (LTS: Gallium)
       v16.14.0   (LTS: Gallium)
       v16.14.1   (LTS: Gallium)
       v16.14.2   (LTS: Gallium)
       v16.15.0   (LTS: Gallium)
       v16.15.1   (LTS: Gallium)
       v16.16.0   (LTS: Gallium)
       v16.17.0   (LTS: Gallium)
       v16.17.1   (LTS: Gallium)
       v16.18.0   (LTS: Gallium)
       v16.18.1   (LTS: Gallium)
       v16.19.0   (LTS: Gallium)
       v16.19.1   (LTS: Gallium)
       v16.20.0   (LTS: Gallium)
       v16.20.1   (LTS: Gallium)
       v16.20.2   (Latest LTS: Gallium)
        v17.0.0
        v17.0.1
        v17.1.0
        v17.2.0
        v17.3.0
        v17.3.1
        v17.4.0
        v17.5.0
        v17.6.0
        v17.7.0
        v17.7.1
        v17.7.2
        v17.8.0
        v17.9.0
        v17.9.1
        v18.0.0
        v18.1.0
        v18.2.0
        v18.3.0
        v18.4.0
        v18.5.0
        v18.6.0
        v18.7.0
        v18.8.0
        v18.9.0
        v18.9.1
       v18.10.0
       v18.11.0
       v18.12.0   (LTS: Hydrogen)
       v18.12.1   (LTS: Hydrogen)
       v18.13.0   (LTS: Hydrogen)
       v18.14.0   (LTS: Hydrogen)
       v18.14.1   (LTS: Hydrogen)
       v18.14.2   (LTS: Hydrogen)
       v18.15.0   (LTS: Hydrogen)
       v18.16.0   (LTS: Hydrogen)
       v18.16.1   (LTS: Hydrogen)
       v18.17.0   (LTS: Hydrogen)
       v18.17.1   (LTS: Hydrogen)
       v18.18.0   (LTS: Hydrogen)
       v18.18.1   (LTS: Hydrogen)
       v18.18.2   (LTS: Hydrogen)
       v18.19.0   (LTS: Hydrogen)
       v18.19.1   (LTS: Hydrogen)
       v18.20.0   (LTS: Hydrogen)
       v18.20.1   (LTS: Hydrogen)
       v18.20.2   (LTS: Hydrogen)
       v18.20.3   (LTS: Hydrogen)
       v18.20.4   (Latest LTS: Hydrogen)
        v19.0.0
        v19.0.1
        v19.1.0
        v19.2.0
        v19.3.0
        v19.4.0
        v19.5.0
        v19.6.0
        v19.6.1
        v19.7.0
        v19.8.0
        v19.8.1
        v19.9.0
        v20.0.0
        v20.1.0
        v20.2.0
        v20.3.0
        v20.3.1
        v20.4.0
        v20.5.0
        v20.5.1
        v20.6.0
        v20.6.1
        v20.7.0
        v20.8.0
        v20.8.1
        v20.9.0   (LTS: Iron)
       v20.10.0   (LTS: Iron)
       v20.11.0   (LTS: Iron)
       v20.11.1   (LTS: Iron)
       v20.12.0   (LTS: Iron)
       v20.12.1   (LTS: Iron)
       v20.12.2   (LTS: Iron)
       v20.13.0   (LTS: Iron)
       v20.13.1   (LTS: Iron)
       v20.14.0   (LTS: Iron)
       v20.15.0   (LTS: Iron)
       v20.15.1   (LTS: Iron)
       v20.16.0   (Latest LTS: Iron)
        v21.0.0
        v21.1.0
        v21.2.0
        v21.3.0
        v21.4.0
        v21.5.0
        v21.6.0
        v21.6.1
        v21.6.2
        v21.7.0
        v21.7.1
        v21.7.2
        v21.7.3
        v22.0.0
        v22.1.0
        v22.2.0
        v22.3.0
        v22.4.0
        v22.4.1
        v22.5.0
        v22.5.1
        v22.6.0
root@8b3416ca7088:/# nvm install v20
Downloading and installing node v20.16.0...
Downloading https://nodejs.org/dist/v20.16.0/node-v20.16.0-linux-x64.tar.gz...
################################################################################################################################################################# 100.0%
Computing checksum with sha256sum
Checksums matched!
Now using node v20.16.0 (npm v10.8.1)
Creating default alias: default -> v20 (-> v20.16.0)
root@8b3416ca7088:/#
bash: docker: command not found
root@8b3416ca7088:/# node --version
v20.16.0
root@8b3416ca7088:/# npm --version
10.8.1 สรุปคำสั่งตั้งแต่เริ่มต้น



anchisa@IE3311-27:~$ docker commit 8b3416ca7088  ounka
sha256:7dd062dac69d2535fe8fcdce001945f7bdd9b689f1141f57741ba164e49169af
anchisa@IE3311-27:~$ docker images
REPOSITORY          TAG       IMAGE ID       CREATED              SIZE
ounka               latest    7dd062dac69d   6 seconds ago        341MB
<none>              <none>    1b60d8972f59   About a minute ago   341MB
anchisa             latest    9a7773d2e20a   6 days ago           209MB
nginx               latest    a72860cb95fd   7 weeks ago          188MB
ubuntu              latest    35a88802559d   2 months ago         78.1MB
bcbcarl/hollywood   latest    8a85ac985999   6 years ago          533MB
anchisa@IE3311-27:~$ docker commit 35a88802559d ounka
Error response from daemon: No such container: 35a88802559d
anchisa@IE3311-27:~$ docker commit 8b3416ca7088  ounka
sha256:2a5b2b27f02dcd5ef780ed3bac9daf9fbc6c02225990f4d2ac8f4eb0c6e66541
anchisa@IE3311-27:~$ docker container run -dp 80;3000 ounka
"docker container run" requires at least 1 argument.
See 'docker container run --help'.

Usage:  docker container run [OPTIONS] IMAGE [COMMAND] [ARG...]

Create and run a new container from an image
3000: command not found
anchisa@IE3311-27:~$ docker run -dp 80:3000 ounka
c615194204f338e652be6887b9e7d2799c029e2a671a45e11ad06af967bf7d22
docker: Error response from daemon: driver failed programming external connectivity on endpoint confident_payne (ededa035bf6a7efe03aa66b90958970e269fe9039472af62c42038d7fb3d0e46): Bind for 0.0.0.0:80 failed: port is already allocated.
anchisa@IE3311-27:~$ docker run -dp 8080:3000 ounka
e9cb8d7d39b7d1f54e3fdc25e68160d404b91cb8de6c9e943ed51797753c5859
anchisa@IE3311-27:~$ docker ps
CONTAINER ID   IMAGE     COMMAND                  CREATED             STATUS             PORTS                               NAMES
6a1b0513f706   nginx     "/docker-entrypoint.…"   15 minutes ago      Up 15 minutes      0.0.0.0:80->80/tcp, :::80->80/tcp   elated_montalcini
8b3416ca7088   ubuntu    "/bin/bash"              About an hour ago   Up About an hour                                       test-node
anchisa@IE3311-27:~$ docker exec -it elated_motalcini /bin/bash
Error response from daemon: No such container: elated_motalcini
anchisa@IE3311-27:~$ docker exec -it elated_montalcini /bin/bash
root@6a1b0513f706:/# ls
bin  boot  dev  docker-entrypoint.d  docker-entrypoint.sh  etc  home  lib  lib64  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
root@6a1b0513f706:/# cd root
root@6a1b0513f706:~# ls
root@6a1b0513f706:~# exit
exit
anchisa@IE3311-27:~$ docker ps
CONTAINER ID   IMAGE     COMMAND                  CREATED             STATUS             PORTS                               NAMES
6a1b0513f706   nginx     "/docker-entrypoint.…"   16 minutes ago      Up 16 minutes      0.0.0.0:80->80/tcp, :::80->80/tcp   elated_montalcini
8b3416ca7088   ubuntu    "/bin/bash"              About an hour ago   Up About an hour                                       test-node
anchisa@IE3311-27:~$ docker exec -it elated_montalcini /bin/bash
root@6a1b0513f706:/# node -v
bash: node: command not found
root@6a1b0513f706:/# exit
exit
anchisa@IE3311-27:~$ docker exec -it test-node /bin/bash
root@8b3416ca7088:/# node -v
v20.16.0
root@8b3416ca7088:/# exit
exit
anchisa@IE3311-27:~$ docker commit 8b3416ca7088  ounka
sha256:0e8fc760fd1cfc3b4778c26bf94ad6a1338ae17bb02925b51676fcf7a88a8df0
anchisa@IE3311-27:~$ docker run -dp 8080:3000 ounka
3caf4ddce99e39c7b7a842d2012923b0f3b0433a31eaa7b8cc211640b67407a6
anchisa@IE3311-27:~$ docker ps
CONTAINER ID   IMAGE     COMMAND                  CREATED             STATUS             PORTS                               NAMES
6a1b0513f706   nginx     "/docker-entrypoint.…"   18 minutes ago      Up 18 minutes      0.0.0.0:80->80/tcp, :::80->80/tcp   elated_montalcini
8b3416ca7088   ubuntu    "/bin/bash"              About an hour ago   Up About an hour                                       test-node
anchisa@IE3311-27:~$ docker container ls
CONTAINER ID   IMAGE     COMMAND                  CREATED             STATUS             PORTS                               NAMES
6a1b0513f706   nginx     "/docker-entrypoint.…"   18 minutes ago      Up 18 minutes      0.0.0.0:80->80/tcp, :::80->80/tcp   elated_montalcini
8b3416ca7088   ubuntu    "/bin/bash"              About an hour ago   Up About an hour                                       test-node
anchisa@IE3311-27:~$ docker run -dp 8080:3000 --name test ounka
4c66b5889b86462a56bab6a42d2e9159678eba5d8a81b4c2bfcb192aa0e7157d
anchisa@IE3311-27:~$ docker container ls
CONTAINER ID   IMAGE     COMMAND                  CREATED             STATUS             PORTS                               NAMES
6a1b0513f706   nginx     "/docker-entrypoint.…"   19 minutes ago      Up 19 minutes      0.0.0.0:80->80/tcp, :::80->80/tcp   elated_montalcini
8b3416ca7088   ubuntu    "/bin/bash"              About an hour ago   Up About an hour                                       test-node
anchisa@IE3311-27:~$ docker images
REPOSITORY          TAG       IMAGE ID       CREATED              SIZE
ounka               latest    0e8fc760fd1c   About a minute ago   341MB
<none>              <none>    2a5b2b27f02d   12 minutes ago       341MB
<none>              <none>    7dd062dac69d   13 minutes ago       341MB
<none>              <none>    1b60d8972f59   14 minutes ago       341MB
anchisa             latest    9a7773d2e20a   7 days ago           209MB
nginx               latest    a72860cb95fd   7 weeks ago          188MB
ubuntu              latest    35a88802559d   2 months ago         78.1MB
bcbcarl/hollywood   latest    8a85ac985999   6 years ago          533MB
anchisa@IE3311-27:~$ docker system prune
WARNING! This will remove:
  - all stopped containers
  - all networks not used by at least one container
  - all dangling images
  - all dangling build cache

Are you sure you want to continue? [y/N] y
Deleted Containers:
4c66b5889b86462a56bab6a42d2e9159678eba5d8a81b4c2bfcb192aa0e7157d
3caf4ddce99e39c7b7a842d2012923b0f3b0433a31eaa7b8cc211640b67407a6
e9cb8d7d39b7d1f54e3fdc25e68160d404b91cb8de6c9e943ed51797753c5859
c615194204f338e652be6887b9e7d2799c029e2a671a45e11ad06af967bf7d22
ca04e706deeaf084f4bb86a032e39b4703136820d447ed122597edfc0b8a03fb
37eb96feb66c186342faf1e40ba7289fa7987e4c5bc07fb84a984ae0bf2e2c49
5287a5bd180f1aa5068290fe8aece918f6f987cbce62a6273a3f7e930257ee9d
97b8a783af8e9383177ca69b438da0692f325de230f1a8769ee587de3cde12f9

Deleted Images:
deleted: sha256:1b60d8972f59355bfa96d16e8000de46933241299293f48ceeab4c650a161800
deleted: sha256:7dd062dac69d2535fe8fcdce001945f7bdd9b689f1141f57741ba164e49169af
deleted: sha256:2a5b2b27f02dcd5ef780ed3bac9daf9fbc6c02225990f4d2ac8f4eb0c6e66541
deleted: sha256:615c86a69428186df9d0ea6c508bda66d6e36cca444a95122a1e8d62d4e2762d

Total reclaimed space: 263.2MB
anchisa@IE3311-27:~$ docker ps
CONTAINER ID   IMAGE     COMMAND                  CREATED             STATUS             PORTS                               NAMES
6a1b0513f706   nginx     "/docker-entrypoint.…"   19 minutes ago      Up 19 minutes      0.0.0.0:80->80/tcp, :::80->80/tcp   elated_montalcini
8b3416ca7088   ubuntu    "/bin/bash"              About an hour ago   Up About an hour                                       test-node
anchisa@IE3311-27:~$ docker run -it -dp 8080:3000 --name test ounka
030c9dd934beba57a9419f5b93fd1d25923faf389061e717b17905615667eb0c
anchisa@IE3311-27:~$ docker ps
CONTAINER ID   IMAGE     COMMAND                  CREATED             STATUS             PORTS                                       NAMES
030c9dd934be   ounka     "/bin/bash"              3 seconds ago       Up 2 seconds       0.0.0.0:8080->3000/tcp, :::8080->3000/tcp   test
6a1b0513f706   nginx     "/docker-entrypoint.…"   20 minutes ago      Up 20 minutes      0.0.0.0:80->80/tcp, :::80->80/tcp           elated_montalcini
8b3416ca7088   ubuntu    "/bin/bash"              About an hour ago   Up About an hour                                               test-node
anchisa@IE3311-27:~$ docker exec -it test /bin/bash
root@030c9dd934be:/# node -v
v20.16.0
root@030c9dd934be:/# nano server.js
root@030c9dd934be:/# node server
Server running at http://localhost:3000
Node.js v20.16.0
root@030c9dd934be:/# nano server.js
root@030c9dd934be:/# node server.js
Server running at http://localhost:3000

root@030c9dd934be:/# nano server.js
root@030c9dd934be:/# node server.js
Server running at http://localhost:3000
