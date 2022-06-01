snj@snj-ThinkPad-T440p:~/coookieAI$ touch readme.md
snj@snj-ThinkPad-T440p:~/coookieAI$ touch setup.py
snj@snj-ThinkPad-T440p:~/coookieAI$ python -m pip install –-user –-upgrade setuptools wheel
Command 'python' not found, did you mean:
  command 'python3' from deb python3
  command 'python' from deb python-is-python3
snj@snj-ThinkPad-T440p:~/coookieAI$ python3 -m pip install –-user –-upgrade setuptools wheel
/usr/bin/python3: No module named pip
snj@snj-ThinkPad-T440p:~/coookieAI$ pip
Command 'pip' not found, but can be installed with:
sudo apt install python3-pip
snj@snj-ThinkPad-T440p:~/coookieAI$ sudo apt install python3-pip
[sudo] password for snj: 
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following packages were automatically installed and are no longer required:
  chromium-codecs-ffmpeg-extra gstreamer1.0-vaapi libgstreamer-plugins-bad1.0-0
Use 'sudo apt autoremove' to remove them.
The following additional packages will be installed:
  build-essential dpkg-dev fakeroot g++ g++-11 gcc gcc-11 javascript-common
  libalgorithm-diff-perl libalgorithm-diff-xs-perl libalgorithm-merge-perl libasan6
  libatomic1 libc-dev-bin libc-devtools libc6-dev libcc1-0 libcrypt-dev
  libdpkg-perl libexpat1-dev libfakeroot libfile-fcntllock-perl libgcc-11-dev
  libitm1 libjs-jquery libjs-sphinxdoc libjs-underscore liblsan0 libnsl-dev
  libpython3-dev libpython3.10-dev libstdc++-11-dev libtirpc-dev libtsan0 libubsan1
  linux-libc-dev lto-disabled-list make manpages-dev python3-dev python3-distutils
  python3-setuptools python3-wheel python3.10-dev rpcsvc-proto zlib1g-dev
Suggested packages:
  debian-keyring g++-multilib g++-11-multilib gcc-11-doc gcc-multilib autoconf
  automake libtool flex bison gcc-doc gcc-11-multilib gcc-11-locales apache2
  | lighttpd | httpd glibc-doc bzr libstdc++-11-doc make-doc python-setuptools-doc
The following NEW packages will be installed:
  build-essential dpkg-dev fakeroot g++ g++-11 gcc gcc-11 javascript-common
  libalgorithm-diff-perl libalgorithm-diff-xs-perl libalgorithm-merge-perl libasan6
  libatomic1 libc-dev-bin libc-devtools libc6-dev libcc1-0 libcrypt-dev
  libdpkg-perl libexpat1-dev libfakeroot libfile-fcntllock-perl libgcc-11-dev
  libitm1 libjs-jquery libjs-sphinxdoc libjs-underscore liblsan0 libnsl-dev
  libpython3-dev libpython3.10-dev libstdc++-11-dev libtirpc-dev libtsan0 libubsan1
  linux-libc-dev lto-disabled-list make manpages-dev python3-dev python3-distutils
  python3-pip python3-setuptools python3-wheel python3.10-dev rpcsvc-proto
  zlib1g-dev
0 upgraded, 47 newly installed, 0 to remove and 13 not upgraded.
Need to get 58.5 MB of archives.
After this operation, 205 MB of additional disk space will be used.
Do you want to continue? [Y/n] Y
Get:1 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libc-dev-bin amd64 2.35-0ubuntu3 [20.3 kB]
Get:2 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libcrypt-dev amd64 1:4.4.27-1 [112 kB]
Get:3 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 rpcsvc-proto amd64 1.4.2-0ubuntu6 [68.5 kB]
Get:4 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libtirpc-dev amd64 1.3.2-2build1 [192 kB]
Get:5 http://security.ubuntu.com/ubuntu jammy-security/main amd64 linux-libc-dev amd64 5.15.0-33.34 [1,281 kB]
Get:6 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libnsl-dev amd64 1.3.0-2build2 [71.3 kB]
Get:7 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libc6-dev amd64 2.35-0ubuntu3 [2,099 kB]
Get:8 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libcc1-0 amd64 12-20220319-1ubuntu1 [47.2 kB]
Get:9 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libitm1 amd64 12-20220319-1ubuntu1 [30.2 kB]
Get:10 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libatomic1 amd64 12-20220319-1ubuntu1 [10.4 kB]
Get:11 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libasan6 amd64 11.2.0-19ubuntu1 [2,283 kB]
Get:12 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 liblsan0 amd64 12-20220319-1ubuntu1 [1,069 kB]
Get:13 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libtsan0 amd64 11.2.0-19ubuntu1 [2,261 kB]
Get:14 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libubsan1 amd64 12-20220319-1ubuntu1 [976 kB]
Get:15 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libgcc-11-dev amd64 11.2.0-19ubuntu1 [2,526 kB]
Get:16 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 gcc-11 amd64 11.2.0-19ubuntu1 [20.1 MB]
Get:17 http://security.ubuntu.com/ubuntu jammy-security/main amd64 libdpkg-perl all 1.21.1ubuntu2.1 [237 kB]
Get:18 http://security.ubuntu.com/ubuntu jammy-security/main amd64 dpkg-dev all 1.21.1ubuntu2.1 [922 kB]
Get:19 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 gcc amd64 4:11.2.0-1ubuntu1 [5,112 B]
Get:20 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libstdc++-11-dev amd64 11.2.0-19ubuntu1 [2,083 kB]
Get:21 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 g++-11 amd64 11.2.0-19ubuntu1 [11.4 MB]
Get:22 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 g++ amd64 4:11.2.0-1ubuntu1 [1,412 B]
Get:23 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 make amd64 4.3-4.1build1 [180 kB]
Get:24 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 lto-disabled-list all 24 [12.5 kB]
Get:25 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 build-essential amd64 12.9ubuntu3 [4,744 B]
Get:26 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libfakeroot amd64 1.28-1ubuntu1 [31.5 kB]
Get:27 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 fakeroot amd64 1.28-1ubuntu1 [60.4 kB]
Get:28 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 javascript-common all 11+nmu1 [5,936 B]
Get:29 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libalgorithm-diff-perl all 1.201-1 [41.8 kB]
Get:30 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libalgorithm-diff-xs-perl amd64 0.04-6build3 [11.9 kB]
Get:31 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libalgorithm-merge-perl all 0.08-3 [12.0 kB]
Get:32 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libc-devtools amd64 2.35-0ubuntu3 [28.9 kB]
Get:33 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libexpat1-dev amd64 2.4.7-1 [147 kB]
Get:34 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libfile-fcntllock-perl amd64 0.22-3build7 [33.9 kB]
Get:35 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libjs-jquery all 3.6.0+dfsg+~3.5.13-1 [321 kB]
Get:36 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libjs-underscore all 1.13.2~dfsg-2 [118 kB]
Get:37 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libjs-sphinxdoc all 4.3.2-1 [139 kB]
Get:38 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 zlib1g-dev amd64 1:1.2.11.dfsg-2ubuntu9 [164 kB]
Get:39 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libpython3.10-dev amd64 3.10.4-3 [4,758 kB]
Get:40 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 libpython3-dev amd64 3.10.4-0ubuntu2 [7,242 B]
Get:41 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 manpages-dev all 5.10-1ubuntu1 [2,309 kB]
Get:42 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 python3.10-dev amd64 3.10.4-3 [507 kB]
Get:43 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 python3-distutils all 3.10.4-0ubuntu1 [138 kB]
Get:44 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 python3-dev amd64 3.10.4-0ubuntu2 [26.0 kB]
Get:45 http://in.archive.ubuntu.com/ubuntu jammy/main amd64 python3-setuptools all 59.6.0-1.2 [339 kB]
Get:46 http://in.archive.ubuntu.com/ubuntu jammy/universe amd64 python3-wheel all 0.37.1-2 [31.9 kB]
Get:47 http://in.archive.ubuntu.com/ubuntu jammy/universe amd64 python3-pip all 22.0.2+dfsg-1 [1,306 kB]
Fetched 58.5 MB in 18s (3,292 kB/s)                                                 
Extracting templates from packages: 100%
Selecting previously unselected package libc-dev-bin.
(Reading database ... 201006 files and directories currently installed.)
Preparing to unpack .../00-libc-dev-bin_2.35-0ubuntu3_amd64.deb ...
Unpacking libc-dev-bin (2.35-0ubuntu3) ...
Selecting previously unselected package linux-libc-dev:amd64.
Preparing to unpack .../01-linux-libc-dev_5.15.0-33.34_amd64.deb ...
Unpacking linux-libc-dev:amd64 (5.15.0-33.34) ...
Selecting previously unselected package libcrypt-dev:amd64.
Preparing to unpack .../02-libcrypt-dev_1%3a4.4.27-1_amd64.deb ...
Unpacking libcrypt-dev:amd64 (1:4.4.27-1) ...
Selecting previously unselected package rpcsvc-proto.
Preparing to unpack .../03-rpcsvc-proto_1.4.2-0ubuntu6_amd64.deb ...
Unpacking rpcsvc-proto (1.4.2-0ubuntu6) ...
Selecting previously unselected package libtirpc-dev:amd64.
Preparing to unpack .../04-libtirpc-dev_1.3.2-2build1_amd64.deb ...
Unpacking libtirpc-dev:amd64 (1.3.2-2build1) ...
Selecting previously unselected package libnsl-dev:amd64.
Preparing to unpack .../05-libnsl-dev_1.3.0-2build2_amd64.deb ...
Unpacking libnsl-dev:amd64 (1.3.0-2build2) ...
Selecting previously unselected package libc6-dev:amd64.
Preparing to unpack .../06-libc6-dev_2.35-0ubuntu3_amd64.deb ...
Unpacking libc6-dev:amd64 (2.35-0ubuntu3) ...
Selecting previously unselected package libcc1-0:amd64.
Preparing to unpack .../07-libcc1-0_12-20220319-1ubuntu1_amd64.deb ...
Unpacking libcc1-0:amd64 (12-20220319-1ubuntu1) ...
Selecting previously unselected package libitm1:amd64.
Preparing to unpack .../08-libitm1_12-20220319-1ubuntu1_amd64.deb ...
Unpacking libitm1:amd64 (12-20220319-1ubuntu1) ...
Selecting previously unselected package libatomic1:amd64.
Preparing to unpack .../09-libatomic1_12-20220319-1ubuntu1_amd64.deb ...
Unpacking libatomic1:amd64 (12-20220319-1ubuntu1) ...
Selecting previously unselected package libasan6:amd64.
Preparing to unpack .../10-libasan6_11.2.0-19ubuntu1_amd64.deb ...
Unpacking libasan6:amd64 (11.2.0-19ubuntu1) ...
Selecting previously unselected package liblsan0:amd64.
Preparing to unpack .../11-liblsan0_12-20220319-1ubuntu1_amd64.deb ...
Unpacking liblsan0:amd64 (12-20220319-1ubuntu1) ...
Selecting previously unselected package libtsan0:amd64.
Preparing to unpack .../12-libtsan0_11.2.0-19ubuntu1_amd64.deb ...
Unpacking libtsan0:amd64 (11.2.0-19ubuntu1) ...
Selecting previously unselected package libubsan1:amd64.
Preparing to unpack .../13-libubsan1_12-20220319-1ubuntu1_amd64.deb ...
Unpacking libubsan1:amd64 (12-20220319-1ubuntu1) ...
Selecting previously unselected package libgcc-11-dev:amd64.
Preparing to unpack .../14-libgcc-11-dev_11.2.0-19ubuntu1_amd64.deb ...
Unpacking libgcc-11-dev:amd64 (11.2.0-19ubuntu1) ...
Selecting previously unselected package gcc-11.
Preparing to unpack .../15-gcc-11_11.2.0-19ubuntu1_amd64.deb ...
Unpacking gcc-11 (11.2.0-19ubuntu1) ...
Selecting previously unselected package gcc.
Preparing to unpack .../16-gcc_4%3a11.2.0-1ubuntu1_amd64.deb ...
Unpacking gcc (4:11.2.0-1ubuntu1) ...
Selecting previously unselected package libstdc++-11-dev:amd64.
Preparing to unpack .../17-libstdc++-11-dev_11.2.0-19ubuntu1_amd64.deb ...
Unpacking libstdc++-11-dev:amd64 (11.2.0-19ubuntu1) ...
Selecting previously unselected package g++-11.
Preparing to unpack .../18-g++-11_11.2.0-19ubuntu1_amd64.deb ...
Unpacking g++-11 (11.2.0-19ubuntu1) ...
Selecting previously unselected package g++.
Preparing to unpack .../19-g++_4%3a11.2.0-1ubuntu1_amd64.deb ...
Unpacking g++ (4:11.2.0-1ubuntu1) ...
Selecting previously unselected package make.
Preparing to unpack .../20-make_4.3-4.1build1_amd64.deb ...
Unpacking make (4.3-4.1build1) ...
Selecting previously unselected package libdpkg-perl.
Preparing to unpack .../21-libdpkg-perl_1.21.1ubuntu2.1_all.deb ...
Unpacking libdpkg-perl (1.21.1ubuntu2.1) ...
Selecting previously unselected package lto-disabled-list.
Preparing to unpack .../22-lto-disabled-list_24_all.deb ...
Unpacking lto-disabled-list (24) ...
Selecting previously unselected package dpkg-dev.
Preparing to unpack .../23-dpkg-dev_1.21.1ubuntu2.1_all.deb ...
Unpacking dpkg-dev (1.21.1ubuntu2.1) ...
Selecting previously unselected package build-essential.
Preparing to unpack .../24-build-essential_12.9ubuntu3_amd64.deb ...
Unpacking build-essential (12.9ubuntu3) ...
Selecting previously unselected package libfakeroot:amd64.
Preparing to unpack .../25-libfakeroot_1.28-1ubuntu1_amd64.deb ...
Unpacking libfakeroot:amd64 (1.28-1ubuntu1) ...
Selecting previously unselected package fakeroot.
Preparing to unpack .../26-fakeroot_1.28-1ubuntu1_amd64.deb ...
Unpacking fakeroot (1.28-1ubuntu1) ...
Selecting previously unselected package javascript-common.
Preparing to unpack .../27-javascript-common_11+nmu1_all.deb ...
Unpacking javascript-common (11+nmu1) ...
Selecting previously unselected package libalgorithm-diff-perl.
Preparing to unpack .../28-libalgorithm-diff-perl_1.201-1_all.deb ...
Unpacking libalgorithm-diff-perl (1.201-1) ...
Selecting previously unselected package libalgorithm-diff-xs-perl.
Preparing to unpack .../29-libalgorithm-diff-xs-perl_0.04-6build3_amd64.deb ...
Unpacking libalgorithm-diff-xs-perl (0.04-6build3) ...
Selecting previously unselected package libalgorithm-merge-perl.
Preparing to unpack .../30-libalgorithm-merge-perl_0.08-3_all.deb ...
Unpacking libalgorithm-merge-perl (0.08-3) ...
Selecting previously unselected package libc-devtools.
Preparing to unpack .../31-libc-devtools_2.35-0ubuntu3_amd64.deb ...
Unpacking libc-devtools (2.35-0ubuntu3) ...
Selecting previously unselected package libexpat1-dev:amd64.
Preparing to unpack .../32-libexpat1-dev_2.4.7-1_amd64.deb ...
Unpacking libexpat1-dev:amd64 (2.4.7-1) ...
Selecting previously unselected package libfile-fcntllock-perl.
Preparing to unpack .../33-libfile-fcntllock-perl_0.22-3build7_amd64.deb ...
Unpacking libfile-fcntllock-perl (0.22-3build7) ...
Selecting previously unselected package libjs-jquery.
Preparing to unpack .../34-libjs-jquery_3.6.0+dfsg+~3.5.13-1_all.deb ...
Unpacking libjs-jquery (3.6.0+dfsg+~3.5.13-1) ...
Selecting previously unselected package libjs-underscore.
Preparing to unpack .../35-libjs-underscore_1.13.2~dfsg-2_all.deb ...
Unpacking libjs-underscore (1.13.2~dfsg-2) ...
Selecting previously unselected package libjs-sphinxdoc.
Preparing to unpack .../36-libjs-sphinxdoc_4.3.2-1_all.deb ...
Unpacking libjs-sphinxdoc (4.3.2-1) ...
Selecting previously unselected package zlib1g-dev:amd64.
Preparing to unpack .../37-zlib1g-dev_1%3a1.2.11.dfsg-2ubuntu9_amd64.deb ...
Unpacking zlib1g-dev:amd64 (1:1.2.11.dfsg-2ubuntu9) ...
Selecting previously unselected package libpython3.10-dev:amd64.
Preparing to unpack .../38-libpython3.10-dev_3.10.4-3_amd64.deb ...
Unpacking libpython3.10-dev:amd64 (3.10.4-3) ...
Selecting previously unselected package libpython3-dev:amd64.
Preparing to unpack .../39-libpython3-dev_3.10.4-0ubuntu2_amd64.deb ...
Unpacking libpython3-dev:amd64 (3.10.4-0ubuntu2) ...
Selecting previously unselected package manpages-dev.
Preparing to unpack .../40-manpages-dev_5.10-1ubuntu1_all.deb ...
Unpacking manpages-dev (5.10-1ubuntu1) ...
Selecting previously unselected package python3.10-dev.
Preparing to unpack .../41-python3.10-dev_3.10.4-3_amd64.deb ...
Unpacking python3.10-dev (3.10.4-3) ...
Selecting previously unselected package python3-distutils.
Preparing to unpack .../42-python3-distutils_3.10.4-0ubuntu1_all.deb ...
Unpacking python3-distutils (3.10.4-0ubuntu1) ...
Selecting previously unselected package python3-dev.
Preparing to unpack .../43-python3-dev_3.10.4-0ubuntu2_amd64.deb ...
Unpacking python3-dev (3.10.4-0ubuntu2) ...
Selecting previously unselected package python3-setuptools.
Preparing to unpack .../44-python3-setuptools_59.6.0-1.2_all.deb ...
Unpacking python3-setuptools (59.6.0-1.2) ...
Selecting previously unselected package python3-wheel.
Preparing to unpack .../45-python3-wheel_0.37.1-2_all.deb ...
Unpacking python3-wheel (0.37.1-2) ...
Selecting previously unselected package python3-pip.
Preparing to unpack .../46-python3-pip_22.0.2+dfsg-1_all.deb ...
Unpacking python3-pip (22.0.2+dfsg-1) ...
Setting up python3-distutils (3.10.4-0ubuntu1) ...
Setting up javascript-common (11+nmu1) ...
Setting up manpages-dev (5.10-1ubuntu1) ...
Setting up lto-disabled-list (24) ...
Setting up python3-setuptools (59.6.0-1.2) ...
Setting up libfile-fcntllock-perl (0.22-3build7) ...
Setting up libalgorithm-diff-perl (1.201-1) ...
Setting up linux-libc-dev:amd64 (5.15.0-33.34) ...
Setting up python3-wheel (0.37.1-2) ...
Setting up libfakeroot:amd64 (1.28-1ubuntu1) ...
Setting up libasan6:amd64 (11.2.0-19ubuntu1) ...
Setting up fakeroot (1.28-1ubuntu1) ...
update-alternatives: using /usr/bin/fakeroot-sysv to provide /usr/bin/fakeroot (fakeroot) in auto mode
Setting up libtirpc-dev:amd64 (1.3.2-2build1) ...
Setting up rpcsvc-proto (1.4.2-0ubuntu6) ...
Setting up make (4.3-4.1build1) ...
Setting up libatomic1:amd64 (12-20220319-1ubuntu1) ...
Setting up python3-pip (22.0.2+dfsg-1) ...
Setting up libdpkg-perl (1.21.1ubuntu2.1) ...
Setting up libubsan1:amd64 (12-20220319-1ubuntu1) ...
Setting up libnsl-dev:amd64 (1.3.0-2build2) ...
Setting up libcrypt-dev:amd64 (1:4.4.27-1) ...
Setting up libjs-jquery (3.6.0+dfsg+~3.5.13-1) ...
Setting up libc-dev-bin (2.35-0ubuntu3) ...
Setting up libalgorithm-diff-xs-perl (0.04-6build3) ...
Setting up libcc1-0:amd64 (12-20220319-1ubuntu1) ...
Setting up liblsan0:amd64 (12-20220319-1ubuntu1) ...
Setting up libitm1:amd64 (12-20220319-1ubuntu1) ...
Setting up libc-devtools (2.35-0ubuntu3) ...
Setting up libjs-underscore (1.13.2~dfsg-2) ...
Setting up libalgorithm-merge-perl (0.08-3) ...
Setting up libtsan0:amd64 (11.2.0-19ubuntu1) ...
Setting up dpkg-dev (1.21.1ubuntu2.1) ...
Setting up libjs-sphinxdoc (4.3.2-1) ...
Setting up libgcc-11-dev:amd64 (11.2.0-19ubuntu1) ...
Setting up gcc-11 (11.2.0-19ubuntu1) ...
Setting up libc6-dev:amd64 (2.35-0ubuntu3) ...
Setting up gcc (4:11.2.0-1ubuntu1) ...
Setting up libexpat1-dev:amd64 (2.4.7-1) ...
Setting up libstdc++-11-dev:amd64 (11.2.0-19ubuntu1) ...
Setting up zlib1g-dev:amd64 (1:1.2.11.dfsg-2ubuntu9) ...
Setting up g++-11 (11.2.0-19ubuntu1) ...
Setting up libpython3.10-dev:amd64 (3.10.4-3) ...
Setting up python3.10-dev (3.10.4-3) ...
Setting up g++ (4:11.2.0-1ubuntu1) ...
update-alternatives: using /usr/bin/g++ to provide /usr/bin/c++ (c++) in auto mode
Setting up build-essential (12.9ubuntu3) ...
Setting up libpython3-dev:amd64 (3.10.4-0ubuntu2) ...
Setting up python3-dev (3.10.4-0ubuntu2) ...
Processing triggers for man-db (2.10.2-1) ...
Processing triggers for libc-bin (2.35-0ubuntu3) ...
snj@snj-ThinkPad-T440p:~/coookieAI$ python3 -m pip install –-user –-upgrade setuptools wheel
Defaulting to user installation because normal site-packages is not writeable
ERROR: Invalid requirement: '–-user'
snj@snj-ThinkPad-T440p:~/coookieAI$ pip install -U pip
Defaulting to user installation because normal site-packages is not writeable
Requirement already satisfied: pip in /usr/lib/python3/dist-packages (22.0.2)
Collecting pip
  Downloading pip-22.1.2-py3-none-any.whl (2.1 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.1/2.1 MB 5.6 MB/s eta 0:00:00
Installing collected packages: pip
  WARNING: The scripts pip, pip3 and pip3.10 are installed in '/home/snj/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
Successfully installed pip-22.1.2
snj@snj-ThinkPad-T440p:~/coookieAI$ pip uninstall setuptools
Found existing installation: setuptools 59.6.0
Uninstalling setuptools-59.6.0:
  Would remove:
    /usr/lib/python3/dist-packages/_distutils_hack
    /usr/lib/python3/dist-packages/debian
    /usr/lib/python3/dist-packages/pkg_resources
    /usr/lib/python3/dist-packages/setuptools
    /usr/lib/python3/dist-packages/setuptools-59.6.0.egg-info
Proceed (Y/n)? Y
ERROR: Exception:
Traceback (most recent call last):
  File "/usr/lib/python3.10/shutil.py", line 813, in move
    os.rename(src, real_dst)
PermissionError: [Errno 13] Permission denied: '/usr/lib/python3/dist-packages/_distutils_hack' -> '/tmp/pip-uninstall-fxyautmc'

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "/home/snj/.local/lib/python3.10/site-packages/pip/_internal/cli/base_command.py", line 167, in exc_logging_wrapper
    status = run_func(*args)
  File "/home/snj/.local/lib/python3.10/site-packages/pip/_internal/commands/uninstall.py", line 98, in run
    uninstall_pathset = req.uninstall(
  File "/home/snj/.local/lib/python3.10/site-packages/pip/_internal/req/req_install.py", line 642, in uninstall
    uninstalled_pathset.remove(auto_confirm, verbose)
  File "/home/snj/.local/lib/python3.10/site-packages/pip/_internal/req/req_uninstall.py", line 373, in remove
    moved.stash(path)
  File "/home/snj/.local/lib/python3.10/site-packages/pip/_internal/req/req_uninstall.py", line 271, in stash
    renames(path, new_path)
  File "/home/snj/.local/lib/python3.10/site-packages/pip/_internal/utils/misc.py", line 311, in renames
    shutil.move(old, new)
  File "/usr/lib/python3.10/shutil.py", line 831, in move
    rmtree(src)
  File "/usr/lib/python3.10/shutil.py", line 722, in rmtree
    _rmtree_safe_fd(fd, path, onerror)
  File "/usr/lib/python3.10/shutil.py", line 678, in _rmtree_safe_fd
    onerror(os.unlink, fullname, sys.exc_info())
  File "/usr/lib/python3.10/shutil.py", line 676, in _rmtree_safe_fd
    os.unlink(entry.name, dir_fd=topfd)
PermissionError: [Errno 13] Permission denied: 'override.py'
snj@snj-ThinkPad-T440p:~/coookieAI$ sudo pip uninstall setuptools
[sudo] password for snj: 
Found existing installation: setuptools 59.6.0
Not uninstalling setuptools at /usr/lib/python3/dist-packages, outside environment /usr
Can't uninstall 'setuptools'. No files were found to uninstall.
WARNING: Running pip as the 'root' user can result in broken permissions and conflicting behaviour with the system package manager. It is recommended to use a virtual environment instead: https://pip.pypa.io/warnings/venv
snj@snj-ThinkPad-T440p:~/coookieAI$ pip install 'setuptools<20.2'
Defaulting to user installation because normal site-packages is not writeable
Collecting setuptools<20.2
  Downloading setuptools-20.1.1-py2.py3-none-any.whl (472 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 472.7/472.7 kB 3.0 MB/s eta 0:00:00
Installing collected packages: setuptools
  WARNING: The scripts easy_install and easy_install-3.10 are installed in '/home/snj/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
Successfully installed setuptools-20.1.1
snj@snj-ThinkPad-T440p:~/coookieAI$ python3 -m pip install –-user –-upgrade setuptools wheel
Defaulting to user installation because normal site-packages is not writeable
ERROR: Invalid requirement: '–-user'
snj@snj-ThinkPad-T440p:~/coookieAI$ python3 -m pip install --user --upgrade setuptools wheel
Requirement already satisfied: setuptools in /home/snj/.local/lib/python3.10/site-packages (20.1.1)
Collecting setuptools
  Downloading setuptools-62.3.2-py3-none-any.whl (1.2 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.2/1.2 MB 4.5 MB/s eta 0:00:00
Requirement already satisfied: wheel in /usr/lib/python3/dist-packages (0.37.1)
Installing collected packages: setuptools
  Attempting uninstall: setuptools
    Found existing installation: setuptools 20.1.1
    Uninstalling setuptools-20.1.1:
      Successfully uninstalled setuptools-20.1.1
Successfully installed setuptools-62.3.2
snj@snj-ThinkPad-T440p:~/coookieAI$ python setup.py sdist bdist_wheel
Command 'python' not found, did you mean:
  command 'python3' from deb python3
  command 'python' from deb python-is-python3
snj@snj-ThinkPad-T440p:~/coookieAI$ python3 setup.py sdist bdist_wheel
Traceback (most recent call last):
  File "/home/snj/coookieAI/setup.py", line 3, in <module>
    with open("README.md", "r") as fh:
FileNotFoundError: [Errno 2] No such file or directory: 'README.md'
snj@snj-ThinkPad-T440p:~/coookieAI$ python3 -m pip install --user --upgrade setuptools wheel
Requirement already satisfied: setuptools in /home/snj/.local/lib/python3.10/site-packages (62.3.2)
Requirement already satisfied: wheel in /usr/lib/python3/dist-packages (0.37.1)
snj@snj-ThinkPad-T440p:~/coookieAI$ python3 setup.py sdist bdist_wheel
Traceback (most recent call last):
  File "/home/snj/coookieAI/setup.py", line 3, in <module>
    with open("README.md", "r") as fh:
FileNotFoundError: [Errno 2] No such file or directory: 'README.md'
snj@snj-ThinkPad-T440p:~/coookieAI$ python3 setup.py sdist bdist_wheel
running sdist
running egg_info
error: error in 'egg_base' option: 'quicksample/src' does not exist or is not a directory
snj@snj-ThinkPad-T440p:~/coookieAI$ python3 setup.py sdist bdist_wheel
running sdist
running egg_info
error: error in 'egg_base' option: 'cookieAI/src' does not exist or is not a directory
snj@snj-ThinkPad-T440p:~/coookieAI$ python3 setup.py sdist bdist_wheel
running sdist
running egg_info
creating cookieAI/src/coookieAI.egg-info
writing cookieAI/src/coookieAI.egg-info/PKG-INFO
writing dependency_links to cookieAI/src/coookieAI.egg-info/dependency_links.txt
writing top-level names to cookieAI/src/coookieAI.egg-info/top_level.txt
writing manifest file 'cookieAI/src/coookieAI.egg-info/SOURCES.txt'
file cookieAI/src/cookieAI.py (for module cookieAI) not found
reading manifest file 'cookieAI/src/coookieAI.egg-info/SOURCES.txt'
adding license file 'LICENSE'
writing manifest file 'cookieAI/src/coookieAI.egg-info/SOURCES.txt'
running check
creating coookieAI-2.3.7
creating coookieAI-2.3.7/cookieAI
creating coookieAI-2.3.7/cookieAI/src
creating coookieAI-2.3.7/cookieAI/src/coookieAI.egg-info
copying files to coookieAI-2.3.7...
copying LICENSE -> coookieAI-2.3.7
copying README.md -> coookieAI-2.3.7
copying setup.py -> coookieAI-2.3.7
copying cookieAI/src/coookieAI.egg-info/PKG-INFO -> coookieAI-2.3.7/cookieAI/src/coookieAI.egg-info
copying cookieAI/src/coookieAI.egg-info/SOURCES.txt -> coookieAI-2.3.7/cookieAI/src/coookieAI.egg-info
copying cookieAI/src/coookieAI.egg-info/dependency_links.txt -> coookieAI-2.3.7/cookieAI/src/coookieAI.egg-info
copying cookieAI/src/coookieAI.egg-info/top_level.txt -> coookieAI-2.3.7/cookieAI/src/coookieAI.egg-info
Writing coookieAI-2.3.7/setup.cfg
creating dist
Creating tar archive
removing 'coookieAI-2.3.7' (and everything under it)
running bdist_wheel
running build
running build_py
file cookieAI/src/cookieAI.py (for module cookieAI) not found
file cookieAI/src/cookieAI.py (for module cookieAI) not found
/home/snj/.local/lib/python3.10/site-packages/setuptools/command/install.py:34: SetuptoolsDeprecationWarning: setup.py install is deprecated. Use build and pip and other standards-based tools.
  warnings.warn(
installing to build/bdist.linux-x86_64/wheel
running install
running install_lib
warning: install_lib: 'build/lib' does not exist -- no Python modules to install

running install_egg_info
Copying cookieAI/src/coookieAI.egg-info to build/bdist.linux-x86_64/wheel/coookieAI-2.3.7-py3.10.egg-info
running install_scripts
adding license file "LICENSE" (matched pattern "LICEN[CS]E*")
creating build/bdist.linux-x86_64/wheel/coookieAI-2.3.7.dist-info/WHEEL
creating 'dist/coookieAI-2.3.7-py3-none-any.whl' and adding 'build/bdist.linux-x86_64/wheel' to it
adding 'coookieAI-2.3.7.dist-info/LICENSE'
adding 'coookieAI-2.3.7.dist-info/METADATA'
adding 'coookieAI-2.3.7.dist-info/WHEEL'
adding 'coookieAI-2.3.7.dist-info/top_level.txt'
adding 'coookieAI-2.3.7.dist-info/RECORD'
removing build/bdist.linux-x86_64/wheel
snj@snj-ThinkPad-T440p:~/coookieAI$ pip install -e .

Defaulting to user installation because normal site-packages is not writeable
Obtaining file:///home/snj/coookieAI
  Preparing metadata (setup.py) ... done
Installing collected packages: coookieAI
  Running setup.py develop for coookieAI
Successfully installed coookieAI-2.3.7
snj@snj-ThinkPad-T440p:~/coookieAI$ python -m pip install — user — upgrade twine
Command 'python' not found, did you mean:
  command 'python3' from deb python3
  command 'python' from deb python-is-python3
snj@snj-ThinkPad-T440p:~/coookieAI$ python3 -m pip install — user — upgrade twine
Defaulting to user installation because normal site-packages is not writeable
ERROR: Invalid requirement: '—'
snj@snj-ThinkPad-T440p:~/coookieAI$ python3 -m pip install -- user -- upgrade twine
Defaulting to user installation because normal site-packages is not writeable
ERROR: Invalid requirement: '--'
snj@snj-ThinkPad-T440p:~/coookieAI$ python3 -m pip install -user -upgrade twine

Usage:   
  /usr/bin/python3 -m pip install [options] <requirement specifier> [package-index-options] ...
  /usr/bin/python3 -m pip install [options] -r <requirements file> [package-index-options] ...
  /usr/bin/python3 -m pip install [options] [-e] <vcs project url> ...
  /usr/bin/python3 -m pip install [options] [-e] <local project path> ...
  /usr/bin/python3 -m pip install [options] <archive url/path> ...

no such option: -u
snj@snj-ThinkPad-T440p:~/coookieAI$ python3 -m pip install --user --upgrade twine
Collecting twine
  Downloading twine-4.0.0-py3-none-any.whl (36 kB)
Requirement already satisfied: keyring>=15.1 in /usr/lib/python3/dist-packages (from twine) (23.5.0)
Collecting rich>=12.0.0
  Downloading rich-12.4.4-py3-none-any.whl (232 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 232.0/232.0 kB 1.3 MB/s eta 0:00:00
Collecting requests-toolbelt!=0.9.0,>=0.8.0
  Downloading requests_toolbelt-0.9.1-py2.py3-none-any.whl (54 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 54.3/54.3 kB 949.0 kB/s eta 0:00:00
Requirement already satisfied: urllib3>=1.26.0 in /usr/lib/python3/dist-packages (from twine) (1.26.5)
Collecting pkginfo>=1.8.1
  Downloading pkginfo-1.8.2-py2.py3-none-any.whl (26 kB)
Requirement already satisfied: importlib-metadata>=3.6 in /usr/lib/python3/dist-packages (from twine) (4.6.4)
Collecting rfc3986>=1.4.0
  Downloading rfc3986-2.0.0-py2.py3-none-any.whl (31 kB)
Requirement already satisfied: requests>=2.20 in /usr/lib/python3/dist-packages (from twine) (2.25.1)
Collecting readme-renderer>=21.0
  Downloading readme_renderer-35.0-py3-none-any.whl (14 kB)
Collecting docutils>=0.13.1
  Downloading docutils-0.18.1-py2.py3-none-any.whl (570 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 570.0/570.0 kB 5.8 MB/s eta 0:00:00
Collecting Pygments>=2.5.1
  Downloading Pygments-2.12.0-py3-none-any.whl (1.1 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.1/1.1 MB 5.4 MB/s eta 0:00:00
Collecting bleach>=2.1.0
  Downloading bleach-5.0.0-py3-none-any.whl (160 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 160.3/160.3 kB 2.7 MB/s eta 0:00:00
Collecting commonmark<0.10.0,>=0.9.0
  Downloading commonmark-0.9.1-py2.py3-none-any.whl (51 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 51.1/51.1 kB 908.3 kB/s eta 0:00:00
Collecting webencodings
  Downloading webencodings-0.5.1-py2.py3-none-any.whl (11 kB)
Requirement already satisfied: six>=1.9.0 in /usr/lib/python3/dist-packages (from bleach>=2.1.0->readme-renderer>=21.0->twine) (1.16.0)
Installing collected packages: webencodings, pkginfo, commonmark, rfc3986, requests-toolbelt, Pygments, docutils, bleach, rich, readme-renderer, twine
  WARNING: The script pkginfo is installed in '/home/snj/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The script cmark is installed in '/home/snj/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The script pygmentize is installed in '/home/snj/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  WARNING: The script twine is installed in '/home/snj/.local/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
Successfully installed Pygments-2.12.0 bleach-5.0.0 commonmark-0.9.1 docutils-0.18.1 pkginfo-1.8.2 readme-renderer-35.0 requests-toolbelt-0.9.1 rfc3986-2.0.0 rich-12.4.4 twine-4.0.0 webencodings-0.5.1
snj@snj-ThinkPad-T440p:~/coookieAI$ python -m twine upload — repository pypi dist/*
Command 'python' not found, did you mean:
  command 'python3' from deb python3
  command 'python' from deb python-is-python3
snj@snj-ThinkPad-T440p:~/coookieAI$ python3 -m twine upload — repository pypi dist/*
snj@snj-ThinkPad-T440p:~/coookieAI$ python3 -m twine upload --repository testpypi dist/*
Uploading distributions to https://test.pypi.org/legacy/
Enter your username: shubham.joshi-1507J
Enter your password: 
Uploading coookieAI-2.3.7-py3-none-any.whl
100% ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 4.3/4.3 kB • 00:00 • ?
WARNING  Error during upload. Retry with the --verbose option for more details.      
snj@snj-ThinkPad-T440p:~/coookieAI$ python3 -m twine upload --repository testpypi dist/* --verbose
Uploading distributions to https://test.pypi.org/legacy/
INFO     dist/coookieAI-2.3.7-py3-none-any.whl (1.3 KB)                              
INFO     dist/coookieAI-2.3.7.tar.gz (1.4 KB)                                        
INFO     Querying keyring for username                                               
Enter your username: shubham.joshi-1507J
INFO     Querying keyring for password                                               
Enter your password: 
INFO     username: shubham.joshi-1507J                                               
INFO     password: <hidden>                                                          
Uploading coookieAI-2.3.7-py3-none-any.whl
100% ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 4.3/4.3 kB • 00:00 • ?
INFO     Response from https://test.pypi.org/legacy/:                                
         403 Invalid or non-existent authentication information. See                 
         https://test.pypi.org/help/#invalid-auth for more information.              
INFO     <html>                                                                      
          <head>                                                                     
           <title>403 Invalid or non-existent authentication information. See        
         https://test.pypi.org/help/#invalid-auth for more information.</title>      
          </head>                                                                    
          <body>                                                                     
           <h1>403 Invalid or non-existent authentication information. See           
         https://test.pypi.org/help/#invalid-auth for more information.</h1>         
           Access was denied to this resource.<br/><br/>                             
         Invalid or non-existent authentication information. See                     
         https://test.pypi.org/help/#invalid-auth for more information.              
                                                                                     
                                                                                     
          </body>                                                                    
         </html>                                                                     
snj@snj-ThinkPad-T440p:~/coookieAI$ python3 -m twine upload --repository pypi dist/* --verbose
Uploading distributions to https://upload.pypi.org/legacy/
INFO     dist/coookieAI-2.3.7-py3-none-any.whl (1.3 KB)                                                                                            
INFO     dist/coookieAI-2.3.7.tar.gz (1.4 KB)                                                                                                      
INFO     Querying keyring for username                                                                                                             
Enter your username: shubham.joshi-1507J
INFO     Querying keyring for password                                                                                                             
Enter your password: 
INFO     username: shubham.joshi-1507J                                                                                                             
INFO     password: <hidden>                                                                                                                        
Uploading coookieAI-2.3.7-py3-none-any.whl
100% ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 4.3/4.3 kB • 00:01 • ?
INFO     Response from https://upload.pypi.org/legacy/:                                                                                            
         200 OK                                                                                                                                    
Uploading coookieAI-2.3.7.tar.gz
100% ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 4.3/4.3 kB • 00:00 • ?
INFO     Response from https://upload.pypi.org/legacy/:                                                                                            
         200 OK                                                                                                                                    

View at:
https://pypi.org/project/coookieAI/2.3.7/
snj@snj-ThinkPad-T440p:~/coookieAI$ 