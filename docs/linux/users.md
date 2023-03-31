# Users

## Check Users in Server.

To check users in Server Linux, you need to execute any of the commands below.

```
$ cat /etc/passwd

$ less /etc/passwd

$ more /etc/passwd
```

## Add user in server and give permission sudo / root.

Create User.

`sudo adduser newuser`

Add the user to the sudo\root group .

`usermod -aG sudo newuser`
`usermod -aG root newuser`

Create .ssh directory.

`mkdir /home/newuser/.ssh`

Create authorized_keys file inside the .ssh folder and add the public key.

`vim /home/newuser/.ssh/authorized_keys`

And paste your SSH public key here, save and close file.
Verify SSH remote login.