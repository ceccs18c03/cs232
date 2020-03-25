Script started on 2020-03-24 20:15:36+05:30 [TERM="xterm-256color" TTY="/dev/pts/0" COLUMNS="48" LINES="29"]
$ pkg upgrade
[33m0% [Working][0m[33m0% [Working][0m[33m0% [Working][0m[33m0% [Working][0m[33m0% [Working][0m[33m0% [Working][0m[33m0% [Working][0m[33m0% [Working][0m[33m0% [Working][0m[33m0% [Working][0m[33m0% [Working][0m[33m0% [Working][0m[33m0% [Working][0m[33m0% [Working][0m            Ign:2 https://dl.bintray.com/grimler/game-packages-24 games InRelease
[33m0% [Working][0m            Ign:3 https://dl.bintray.com/grimler/science-packages-24 science InRelease
[33m0% [Working][0m            Ign:1 https://dl.bintray.com/termux/termux-packages-24 stable InRelease
[33m0% [Working][0m[33m0% [Working][0m            Get:5 https://dl.bintray.com/grimler/game-packages-24 games Release [5344 B]
[33m0% [5 Release 0 B/5344 B 0%][0m                            Hit:5 https://dl.bintray.com/grimler/game-packages-24 games Release
[33m                            0% [Working][0m[33m0% [Release.gpg gpgv 5344 B][0m[33m0% [Release.gpg gpgv 5344 B][0m[33m0% [Release.gpg gpgv 5344 B][0m                            Get:6 https://dl.bintray.com/grimler/science-packages-24 science Release [5348 B]
[33m0% [Release.gpg gpgv 5344 B] [6 Release 3679 B/[0m[33m                                               0% [Release.gpg gpgv 5344 B][0m[33m                            0% [Working][0m            Get:4 https://dl.bintray.com/termux/termux-packages-24 stable Release [6061 B]
[33m0% [Working][0m            Get:8 https://dl.bintray.com/grimler/science-packages-24 science Release.gpg [475 B]
[33m0% [8 Release.gpg 0 B/475 B 0%][0m[33m                               0% [Working][0m[33m0% [8 Release.gpg gpgv 5348 B][0m                              Get:9 https://dl.bintray.com/termux/termux-packages-24 stable Release.gpg [821 B]
[33m0% [8 Release.gpg gpgv 5348 B][0m[33m0% [8 Release.gpg gpgv 5348 B][0m[33m                              0% [Working][0m[33m0% [9 Release.gpg gpgv 6061 B][0m                              Get:10 https://dl.bintray.com/grimler/science-packages-24 science/stable aarch64 Packages [5991 B]
[33m0% [9 Release.gpg gpgv 6061 B][0m[33m0% [10 Packages store 0 B] [9 Release.gpg gpgv [0m[33m                                               0% [9 Release.gpg gpgv 6061 B][0m[33m0% [9 Release.gpg gpgv 6061 B][0m[33m                              33% [Working][0m             Get:11 https://dl.bintray.com/termux/termux-packages-24 stable/main aarch64 Packages [114 kB]
[33m40% [11 Packages 13.5 kB/114 kB 12%][0m[33m57% [11 Packages 42.9 kB/114 kB 38%][0m[33m99% [Working]                      22.0 kB/s 0s[0m[33m99% [11 Packages store 0 B]        22.0 kB/s 0s[0m[33m100% [Working]                     22.0 kB/s 0s[0m                                               Fetched 133 kB in 12s (10.5 kB/s)
Reading package lists... 0%Reading package lists... 0%Reading package lists... 7%Reading package lists... 89%Reading package lists... 89%Reading package lists... 91%Reading package lists... 91%Reading package lists... 96%Reading package lists... 96%Reading package lists... Done
Building dependency tree... 0%Building dependency tree... 0%Building dependency tree... 1%Building dependency tree... 50%Building dependency tree... 50%Building dependency tree       
Reading state information... 0%Reading state information... 3%Reading state information... Done
3 packages can be upgraded. Run 'apt list --upgradable' to see them.
Reading package lists... 0%Reading package lists... 100%Reading package lists... Done
Building dependency tree... 0%Building dependency tree... 0%Building dependency tree... 50%Building dependency tree... 50%Building dependency tree       
Reading state information... 0%Reading state information... 3%Reading state information... Done
Calculating upgrade... 0%Calculating upgrade... 10%Calculating upgrade... Done
The following NEW packages will be installed:
  dialog
The following packages will be upgraded:
  game-repo science-repo termux-tools
3 upgraded, 1 newly installed, 0 to remove and 0 not upgraded.
Need to get 100 kB of archives.
After this operation, 213 kB of additional disk space will be used.
Do you want to continue? [Y/n] y
[33m0% [Working][0m[33m0% [Working][0m[33m0% [Working][0m[33m0% [Working][0m[33m0% [Working][0m[33m0% [Working][0m[33m0% [Working][0m            Get:1 https://dl.bintray.com/termux/termux-packages-24 stable/main aarch64 dialog aarch64 1.3-20200228-0 [91.8 kB]
[33m0% [1 dialog 0 B/91.8 kB 0%][0m[33m26% [1 dialog 33.0 kB/91.8 kB 36%][0m[33m                                  78% [Working][0m             Get:2 https://dl.bintray.com/termux/termux-packages-24 stable/main aarch64 termux-tools all 0.75 [5998 B]
[33m78% [2 termux-tools 0 B/5998 B 0%][0m[33m                                  88% [Working][0m             Get:3 https://dl.bintray.com/termux/termux-packages-24 stable/main aarch64 game-repo all 1.2 [1104 B]
[33m88% [3 game-repo 0 B/1104 B 0%][0m[33m                               94% [Working][0m             Get:4 https://dl.bintray.com/termux/termux-packages-24 stable/main aarch64 science-repo all 1.1 [1104 B]
[33m94% [4 science-repo 0 B/1104 B 0%][0m[33m                                  100% [Working][0m              Fetched 100 kB in 3s (26.2 kB/s)

7[0;28r8[1ASelecting previously unselected package dialog.
(Reading database ... (Reading database ... 5%(Reading database ... 10%(Reading database ... 15%(Reading database ... 20%(Reading database ... 25%(Reading database ... 30%(Reading database ... 35%(Reading database ... 40%(Reading database ... 45%(Reading database ... 50%(Reading database ... 55%(Reading database ... 60%(Reading database ... 65%(Reading database ... 70%(Reading database ... 75%(Reading database ... 80%(Reading database ... 85%(Reading database ... 90%(Reading database ... 95%(Reading database ... 100%(Reading database ... 4029 files and directories currently installed.)
Preparing to unpack .../dialog_1.3-20200228-0_aarch64.deb ...
7[29;0f[42m[30mProgress: [  0%][49m[39m [..........................] 87[29;0f[42m[30mProgress: [  4%][49m[39m [#.........................] 8Unpacking dialog (1.3-20200228-0) ...
7[29;0f[42m[30mProgress: [  9%][49m[39m [##........................] 8Setting up dialog (1.3-20200228-0) ...
7[29;0f[42m[30mProgress: [ 14%][49m[39m [###.......................] 87[29;0f[42m[30mProgress: [ 19%][49m[39m [####......................] 87[29;0f[42m[30mProgress: [ 23%][49m[39m [######....................] 8(Reading database ... (Reading database ... 5%(Reading database ... 10%(Reading database ... 15%(Reading database ... 20%(Reading database ... 25%(Reading database ... 30%(Reading database ... 35%(Reading database ... 40%(Reading database ... 45%(Reading database ... 50%(Reading database ... 55%(Reading database ... 60%(Reading database ... 65%(Reading database ... 70%(Reading database ... 75%(Reading database ... 80%(Reading database ... 85%(Reading database ... 90%(Reading database ... 95%(Reading database ... 100%(Reading database ... 4034 files and directories currently installed.)
Preparing to unpack .../termux-tools_0.75_all.deb ...
7[29;0f[42m[30mProgress: [ 28%][49m[39m [#######...................] 8Unpacking termux-tools (0.75) over (0.74) ...
7[29;0f[42m[30mProgress: [ 33%][49m[39m [########..................] 8Setting up termux-tools (0.75) ...
7[29;0f[42m[30mProgress: [ 38%][49m[39m [#########.................] 87[29;0f[42m[30mProgress: [ 42%][49m[39m [###########...............] 87[29;0f[42m[30mProgress: [ 47%][49m[39m [############..............] 8(Reading database ... (Reading database ... 5%(Reading database ... 10%(Reading database ... 15%(Reading database ... 20%(Reading database ... 25%(Reading database ... 30%(Reading database ... 35%(Reading database ... 40%(Reading database ... 45%(Reading database ... 50%(Reading database ... 55%(Reading database ... 60%(Reading database ... 65%(Reading database ... 70%(Reading database ... 75%(Reading database ... 80%(Reading database ... 85%(Reading database ... 90%(Reading database ... 95%(Reading database ... 100%(Reading database ... 4035 files and directories currently installed.)
Preparing to unpack .../archives/game-repo_1.2_all.deb ...
7[29;0f[42m[30mProgress: [ 52%][49m[39m [#############.............] 8Unpacking game-repo (1.2) over (1.1) ...
7[29;0f[42m[30mProgress: [ 57%][49m[39m [##############............] 8Preparing to unpack .../science-repo_1.1_all.deb ...
7[29;0f[42m[30mProgress: [ 61%][49m[39m [################..........] 8Unpacking science-repo (1.1) over (1.0) ...
7[29;0f[42m[30mProgress: [ 66%][49m[39m [#################.........] 8Setting up game-repo (1.2) ...
7[29;0f[42m[30mProgress: [ 71%][49m[39m [##################........] 87[29;0f[42m[30mProgress: [ 76%][49m[39m [###################.......] 8Downloading updated package list ...
[33m0% [Working][0m[33m0% [Working][0m[33m0% [Working][0m            Ign:2 https://dl.bintray.com/grimler/game-packages-24 games InRelease
[33m0% [Working][0m            Ign:3 https://dl.bintray.com/grimler/science-packages-24 science InRelease
[33m0% [Working][0m            Ign:1 https://dl.bintray.com/termux/termux-packages-24 stable InRelease
[33m0% [Working][0m[33m0% [Working][0m            Get:5 https://dl.bintray.com/grimler/game-packages-24 games Release [5344 B]
[33m0% [5 Release 0 B/5344 B 0%][0m                            Hit:5 https://dl.bintray.com/grimler/game-packages-24 games Release
[33m                            0% [Working][0m[33m0% [Release.gpg gpgv 5344 B][0m[33m0% [Release.gpg gpgv 5344 B][0m[33m0% [Release.gpg gpgv 5344 B][0m[33m                            0% [Working][0m            Get:7 https://dl.bintray.com/grimler/science-packages-24 science Release [5348 B]
[33m0% [7 Release 0 B/5348 B 0%][0m                            Hit:7 https://dl.bintray.com/grimler/science-packages-24 science Release
[33m                            0% [Working][0m[33m0% [Release.gpg gpgv 5348 B][0m[33m0% [Release.gpg gpgv 5348 B][0m[33m                            0% [Working][0m            Get:4 https://dl.bintray.com/termux/termux-packages-24 stable Release [6061 B]
[33m0% [4 Release 0 B/6061 B 0%][0m                            Hit:4 https://dl.bintray.com/termux/termux-packages-24 stable Release
[33m                            0% [Working][0m[33m0% [Release.gpg gpgv 6061 B][0m[33m0% [Release.gpg gpgv 6061 B][0m[33m                            100% [Working][0m              Reading package lists... 0%Reading package lists... 0%Reading package lists... 7%Reading package lists... 89%Reading package lists... 89%Reading package lists... 91%Reading package lists... 91%Reading package lists... 96%Reading package lists... 96%Reading package lists... Done
Building dependency tree... 0%Building dependency tree... 0%Building dependency tree... 1%Building dependency tree... 50%Building dependency tree... 50%Building dependency tree       
Reading state information... 0%Reading state information... 3%Reading state information... Done
All packages are up to date.
7[29;0f[42m[30mProgress: [ 80%][49m[39m [#####################.....] 8Setting up science-repo (1.1) ...
7[29;0f[42m[30mProgress: [ 85%][49m[39m [######################....] 87[29;0f[42m[30mProgress: [ 90%][49m[39m [#######################...] 8Downloading updated package list ...
[33m0% [Working][0m[33m0% [Working][0m[33m0% [Working][0m            Ign:2 https://dl.bintray.com/grimler/game-packages-24 games InRelease
[33m0% [Working][0m            Ign:3 https://dl.bintray.com/grimler/science-packages-24 science InRelease
[33m0% [Working][0m            Ign:1 https://dl.bintray.com/termux/termux-packages-24 stable InRelease
[33m0% [Working][0m[33m0% [Working][0m            Get:5 https://dl.bintray.com/grimler/game-packages-24 games Release [5344 B]
[33m0% [5 Release 0 B/5344 B 0%][0m                            Hit:5 https://dl.bintray.com/grimler/game-packages-24 games Release
[33m                            0% [Working][0m[33m0% [Release.gpg gpgv 5344 B][0m[33m0% [Release.gpg gpgv 5344 B][0m[33m0% [Release.gpg gpgv 5344 B][0m[33m                            0% [Working][0m            Get:7 https://dl.bintray.com/grimler/science-packages-24 science Release [5348 B]
[33m0% [7 Release 0 B/5348 B 0%][0m                            Hit:7 https://dl.bintray.com/grimler/science-packages-24 science Release
[33m                            0% [Working][0m[33m0% [Release.gpg gpgv 5348 B][0m[33m0% [Release.gpg gpgv 5348 B][0m[33m0% [Release.gpg gpgv 5348 B][0m[33m                            0% [Working][0m            Get:4 https://dl.bintray.com/termux/termux-packages-24 stable Release [6061 B]
[33m0% [4 Release 0 B/6061 B 0%][0m                            Hit:4 https://dl.bintray.com/termux/termux-packages-24 stable Release
[33m                            0% [Working][0m[33m0% [Release.gpg gpgv 6061 B][0m[33m0% [Release.gpg gpgv 6061 B][0m[33m100% [Working]                      2744 B/s 0s[0m                                               Reading package lists... 0%Reading package lists... 0%Reading package lists... 7%Reading package lists... 89%Reading package lists... 89%Reading package lists... 91%Reading package lists... 91%Reading package lists... 96%Reading package lists... 96%Reading package lists... Done
Building dependency tree... 0%Building dependency tree... 0%Building dependency tree... 1%Building dependency tree... 50%Building dependency tree... 50%Building dependency tree       
Reading state information... 0%Reading state information... 3%Reading state information... Done
All packages are up to date.
7[29;0f[42m[30mProgress: [ 95%][49m[39m [########################..] 8Processing triggers for man (1.14.5-1) ...

7[0;29r8[1A[J$ pkg [K[K[K[Kapt-get install open ssh
Reading package lists... 0%Reading package lists... 100%Reading package lists... Done
Building dependency tree... 0%Building dependency tree... 0%Building dependency tree... 50%Building dependency tree... 50%Building dependency tree       
Reading state information... 0%Reading state information... 3%Reading state information... Done
E: Unable to locate package open
E: Unable to locate package ssh
$ l[Kssh
usage: ssh [-46AaCfGgKkMNnqsTtVvXxYy] [-B bind_interface]
           [-b bind_address] [-c cipher_spec] [-D [bind_address:]port]
           [-E log_file] [-e escape_char] [-F configfile] [-I pkcs11]
           [-i identity_file] [-J [user@]host[:port]] [-L address]
           [-l login_name] [-m mac_spec] [-O ctl_cmd] [-o option] [-p port]
           [-Q query_option] [-R address] [-S ctl_path] [-W host:port]
           [-w local_tun[:remote_tun]] destination [command]
$ [K$ [K$ man
usage: man [-acfhklw] [-C file] [-M path] [-m path] [-S subsection]
	   [[-s] section] name ...
$ pkg [K[K[K[Kapt get im[K[K[K serach hit
E: Invalid operation get
$ apt get serach hit[K[K[K[K git
E: Invalid operation get
$ apt get serach git[1@-[1P
E: Invalid operation serach
$ apt-get serach git[C[C[C[C[C [C[C[C[C[C[C[C[C[C[C[C[C[C[Chit[C[Cman[Ksshapt-get install open ssh[C[C[13Ppkg upgrade[C[C[7Pexit[C[Cssh cs18c03@14.139.189.217[C[Cexit[K[C[Cssh cs18c03@14.139.189.217[C[Cls[Kcd 2203[C[Cls[Kcd Linux[C[Cls[Kcd ..[C[C[3Pls[1Pcssh cs18c03@14.139.189.217[C[C[C[1@ftp[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[Cls[Kcd downloads[C[Cls[Kcd ..[C[C[3Plscd ..[C[C[3Plssftp cs18c03@14.139.189.217[C[Cls[Kget 2103[C[C[5Pllssftp cs18c03@14.139.189.217[C[C[8Ppkg install openssh[C[Csftp cs18c03@14.139.189.217[C[Cexit[K[C[Cpasswd[C[C[Ckg install dropbear[C[C[C[C[C[C[9Pupgrade[C[CPrintMotd no[C[C[8Pexit[C[C[1Pr//stop[C[Cbash[C[Cpkg install beef[C[C[C[C[C[C[1Psearch[C[C[C[C[C[C[C[1Pvsftpd upgrade[C[Cpkg install vsftpd[C[C[C[C[C[C[1Psearch[C[C[C[C[C[C[C[C[C[3Papt-get updateqteate[C[Cpkg search vsftpd[C[C[3Papt-get update[K[K[K[K[K[Kupdqte[K[C[Cpkg search vsftpd[C[C[C[C[C[C[1@install[C[C[C[C[C[C[C[C[C[4Pvsftpd upgrade[C[Cpkg search beef[C[C[C[C[C[C[1@install[C[C[C[C[C[C[C[C[C[C[C[1Psearch[C[C[C[C[C[K[K[K[Kgit
Sorting... 0%Sorting... 0%Sorting... 17%Sorting... Done
Full Text Search... 50%Full Text Search... 50%Full Text Search... Done
[32mblackbox[0m/stable 1.20181219 all
  Safely store secrets in Git/Mercurial/Subversion

[32mdcraw[0m/stable 9.28.0-1 aarch64
  Raw digital camera images decoding utility

[32mgit[0m/stable 2.25.2 aarch64
  Fast, scalable, distributed revision control system

[32mgit-crypt[0m/stable 0.6.0-1 aarch64
  Enables transparent encryption and decryption of files for a git repository

[32mgit-delta[0m/stable 0.0.17-1 aarch64
  A syntax-highlighter for git and diff output

[32mgit-gitk[0m/stable 2.25.2 aarch64
  Git repository browser

[32mgit-gui[0m/stable 2.25.2 aarch64
  A graphical interface to Git

[32mgit-lfs[0m/stable 2.10.0 aarch64
  Git extension for versioning large files

[32mgitea[0m/stable 1.11.3 aarch64
  Git with a cup of tea, painless self-hosted git service

[32mhub[0m/stable 2.14.2 aarch64
  Command-line wrapper for git that makes you better at GitHub

[32mlibgit2[0m/stable 0.99.0 aarch64
  C library implementing Git core methods

[32mtexlive-langitalian[0m/stable 20190410-2 all
  Texlive's collection-langitalian

[32mtig[0m/stable 2.5.0 aarch64
  Ncurses-based text-mode interface for git

[32mvcsh[0m/stable 1.20151229 all
  Config manager based on Git

$ pkg search git[C[C[4@apt-get sera[C[C[C[C[C[C[K[K[K[K[K[K[K[K[K[Kinstall git
Reading package lists... 0%Reading package lists... 100%Reading package lists... Done
Building dependency tree... 0%Building dependency tree... 0%Building dependency tree... 50%Building dependency tree... 50%Building dependency tree       
Reading state information... 0%Reading state information... 3%Reading state information... Done
The following additional packages will be installed:
  pcre2
The following NEW packages will be installed:
  git pcre2
0 upgraded, 2 newly installed, 0 to remove and 0 not upgraded.
Need to get 4063 kB of archives.
After this operation, 23.1 MB of additional disk space will be used.
Do you want to continue? [Y/n] y
0% [Working]0% [Working]0% [Working]0% [Working]0% [Working]0% [Working]0% [Working]0% [Working]            Get:1 https://dl.bintray.com/termux/termux-packages-24 stable/main aarch64 pcre2 aarch64 10.34 [804 kB]
0% [1 pcre2 0 B/804 kB 0%]1% [1 pcre2 33.0 kB/804 kB 4%]2% [1 pcre2 84.8 kB/804 kB 11%]                               3% [1 pcre2 142 kB/804 kB 18%]4% [1 pcre2 228 kB/804 kB 28%]6% [1 pcre2 281 kB/804 kB 35%]7% [1 pcre2 356 kB/804 kB 44%]9% [1 pcre2 436 kB/804 kB 54%]10% [1 pcre2 512 kB/804 kB 64%]12% [1 pcre2 593 kB/804 kB 74%]   57.9 kB/s 59s13% [1 pcre2 680 kB/804 kB 85%]   57.9 kB/s 58s15% [1 pcre2 760 kB/804 kB 94%]   57.9 kB/s 57s26% [Working]                     57.9 kB/s 56s26% [Working]                     57.9 kB/s 56s                                               Get:2 https://dl.bintray.com/termux/termux-packages-24 stable/main aarch64 git aarch64 2.25.2 [3259 kB]
26% [2 git 0 B/3259 kB 0%]        57.9 kB/s 56s29% [2 git 145 kB/3259 kB 4%]     57.9 kB/s 53s32% [2 git 302 kB/3259 kB 9%]     57.9 kB/s 51s36% [2 git 494 kB/3259 kB 15%]    57.9 kB/s 47s40% [2 git 715 kB/3259 kB 22%]    57.9 kB/s 43s45% [2 git 953 kB/3259 kB 29%]    57.9 kB/s 39s51% [2 git 1286 kB/3259 kB 39%]     267 kB/s 7s60% [2 git 1755 kB/3259 kB 54%]     267 kB/s 5s70% [2 git 2263 kB/3259 kB 69%]     267 kB/s 3s78% [2 git 2669 kB/3259 kB 82%]     267 kB/s 2s81% [2 git 2794 kB/3259 kB 86%]     267 kB/s 1s81% [2 git 2804 kB/3259 kB 86%]     267 kB/s 1s84% [2 git 2959 kB/3259 kB 91%]     267 kB/s 1s88% [2 git 3182 kB/3259 kB 98%]     267 kB/s 0s100% [Working]                      267 kB/s 0s                                               Fetched 4063 kB in 16s (248 kB/s)
Selecting previously unselected package pcre2.
(Reading database ... (Reading database ... 5%(Reading database ... 10%(Reading database ... 15%(Reading database ... 20%(Reading database ... 25%(Reading database ... 30%(Reading database ... 35%(Reading database ... 40%(Reading database ... 45%(Reading database ... 50%(Reading database ... 55%(Reading database ... 60%(Reading database ... 65%(Reading database ... 70%(Reading database ... 75%(Reading database ... 80%(Reading database ... 85%(Reading database ... 90%(Reading database ... 95%(Reading database ... 100%(Reading database ... 4039 files and directories currently installed.)
Preparing to unpack .../pcre2_10.34_aarch64.deb ...
Unpacking pcre2 (10.34) ...
Selecting previously unselected package git.
Preparing to unpack .../git_2.25.2_aarch64.deb ...
Unpacking git (2.25.2) ...
Setting up pcre2 (10.34) ...
Setting up git (2.25.2) ...
Processing triggers for man (1.14.5-1) ...
$ [K$ [K$ [K$ apt-remove git
No command apt-remove found, did you mean:
 Command gst-remote in package smalltalk from the unstable-repo repository
$ apt--[K[K[K[K[Kpkg remove git
Reading package lists... 0%Reading package lists... 100%Reading package lists... Done
Building dependency tree... 0%Building dependency tree... 0%Building dependency tree... 50%Building dependency tree... 50%Building dependency tree       
Reading state information... 0%Reading state information... 2%Reading state information... Done
The following package was automatically installed and is no longer required:
  pcre2
Use 'apt autoremove' to remove it.
The following packages will be REMOVED:
  git
0 upgraded, 0 newly installed, 1 to remove and 0 not upgraded.
After this operation, 19.2 MB disk space will be freed.
Do you want to continue? [Y/n] y

7[0;28r8[1A(Reading database ... (Reading database ... 5%(Reading database ... 10%(Reading database ... 15%(Reading database ... 20%(Reading database ... 25%(Reading database ... 30%(Reading database ... 35%(Reading database ... 40%(Reading database ... 45%(Reading database ... 50%(Reading database ... 55%(Reading database ... 60%(Reading database ... 65%(Reading database ... 70%(Reading database ... 75%(Reading database ... 80%(Reading database ... 85%(Reading database ... 90%(Reading database ... 95%(Reading database ... 100%(Reading database ... 4680 files and directories currently installed.)
Removing git (2.25.2) ...
7[29;0f[42m[30mProgress: [  0%][49m[39m [..........................] 87[29;0f[42m[30mProgress: [ 25%][49m[39m [######....................] 87[29;0f[42m[30mProgress: [ 50%][49m[39m [#############.............] 87[29;0f[42m[30mProgress: [ 75%][49m[39m [###################.......] 8Processing triggers for man (1.14.5-1) ...

7[0;29r8[1A[J$ exit
exit

Script done on 2020-03-24 20:23:07+05:30 [COMMAND_EXIT_CODE="0"]
