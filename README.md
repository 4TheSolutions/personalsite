# personalsite

## Instructions:
### Part 1
1. Visit https://git-scm.com/download/mac and run the Installer
2. Open a terminal (https://www.howtogeek.com/682770/how-to-open-the-terminal-on-a-mac/) and execute `git clone https://github.com/4TheSolutions/personalsite`
3. Execute `cd personalsite`


4. Download and install VS Code at https://code.visualstudio.com/
5. Open VS Code in personalsite by executing `code .` in your terminal

6. Open a terminal and Install Ruby using rvm (https://rvm.io/)
7. Close that terminal and open a new terminal and type `rvm install ruby 3`


```
~ % git clone https://github.com/4TheSolutions/personalsite
Cloning into 'personalsite'...
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (4/4), done.
~ % cd personalsite
~/personalsite % ls -alh
total 0
drwxrwxrwx 1 --- --- 512 Apr 19 16:29 .
drwxrwxrwx 1 --- --- 512 Apr 19 16:29 ..
drwxrwxrwx 1 --- --- 512 Apr 19 16:30 .git
-rwxrwxrwx 1 --- ---  56 Apr 19 16:29 .gitignore
-rwxrwxrwx 1 --- --- 307 Apr 19 16:40 README.md
~/personalsite % code .
~/personalsite % gpg2 --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
gpg: /Users/---/.gnupg/trustdb.gpg: trustdb created
gpg: key 105BD0E739499BDB: public key "Piotr Kuczynski <piotr.kuczynski@gmail.com>" imported
gpg: key 3804BB82D39DC0E3: new key but contains no user ID - skipped
gpg: Total number processed: 2
gpg:           w/o user IDs: 1
gpg:               imported: 1
~/personalsite % curl -sSL https://get.rvm.io | bash -s stable
Downloading https://github.com/rvm/rvm/archive/1.29.12.tar.gz
Downloading https://github.com/rvm/rvm/releases/download/1.29.12/1.29.12.tar.gz.asc
gpg: Signature made Fri 15 Jan 2021 12:46:22 PM CST
gpg:                using RSA key 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
gpg: Good signature from "Piotr Kuczynski <piotr.kuczynski@gmail.com>" [unknown]
gpg: WARNING: This key is not certified with a trusted signature!
gpg:          There is no indication that the signature belongs to the owner.
Primary key fingerprint: 7D2B AF1C F37B 13E2 069D  6956 105B D0E7 3949 9BDB
GPG verified '/Users/---/.rvm/archives/rvm-1.29.12.tgz'
Installing RVM to /Users/---/.rvm/
    Adding rvm PATH line to /Users/---/.profile /Users/---/.mkshrc /Users/---/.bashrc /Users/---/.zshrc.
    Adding rvm loading line to /Users/---/.profile /Users/---/.bash_profile /Users/---/.zlogin.
Installation of RVM in /Users/---/.rvm/ is almost complete:

  * To start using RVM you need to run `source /Users/---/.rvm/scripts/rvm`
    in all your open shell windows, in rare cases you need to reopen all shell windows.
Thanks for installing RVM 🙏
Please consider donating to our open collective to help us maintain RVM.

👉  Donate: https://opencollective.com/rvm/donate
```

Or on linux:
```
┌──(---@---)-[~]
└─$ git clone https://github.com/4TheSolutions/personalsite
Cloning into 'personalsite'...
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (4/4), done.
┌──(---@---)-[~]
└─$ cd personalsite
┌──(---@---)-[~/personalsite]
└─$ ls -alh
total 0
drwxrwxrwx 1 --- --- 512 Apr 19 16:29 .
drwxrwxrwx 1 --- --- 512 Apr 19 16:29 ..
drwxrwxrwx 1 --- --- 512 Apr 19 16:30 .git
-rwxrwxrwx 1 --- ---  56 Apr 19 16:29 .gitignore
-rwxrwxrwx 1 --- --- 307 Apr 19 16:40 README.md
┌──(---@---)-[~/personalsite]
└─$ code .
```