# diem
### A Linux CLI for disposable email addresses from [anonbox.net](https://www.anonbox.net/). Short for *Di*sposable *Em*ail.

### Installation
In order to run _diem_ you need `python3`.
You can download the file and execute it as it is. To make it easy on yourself, you might wanna make it available in your PATH. This can be done like this:

```
cd /usr/local/bin;sudo wget https://raw.githubusercontent.com/superDuperCyberTechno/diem/master/diem && sudo chmod +x diem;cd -;
```

This will download the file into the `/usr/local/bin` folder which should be a part of your PATH already, making it available everywhere in your terminal.

To uninstall:
```
sudo rm /usr/local/bin/diem
```

#### Dependencies
`diem` uses Python 3, as well as _pyperclip_ and _pyquery_. The 2 latter can be installed with `pip3`:

```
pip3 install pyperclip pyquery
```

### Usage
Simply run `diem` from your terminal and you will be fed an email address as well as the inbox URL to check incoming emails.
The email address is automatically added to your clipboad so you can paste it wherever.
