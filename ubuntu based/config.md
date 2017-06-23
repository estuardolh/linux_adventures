# configurations

### gksu
A password requester for kde, for root access!

example:

```
gksu thunar

gksu 'exo-open --launch FileManager %u'
```

### chromium proxy settings
To config proxy for chromium is necesary to edit a file "/usr/share/applications/Chromium Web Browser"

And, in "Exec" label add:

```
--proxy-server='<ip>:<port>'
```

example:

```
Exec=chromium-browser %U --proxy-server='192.999.99.9:9999'
``` 

### add environment variables

sudo nano ./bashrc

export VARIABLE="valor"


### mount folder machine
on Virtual box
name: folder_machine
automount yes
permanent yes

on Xubuntu

sudo mount -t vboxsf folder_machine dir_xubuntu_folder

