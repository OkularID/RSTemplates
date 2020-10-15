# Reservasi Dulu Frontend Templates


Clone the core repository to you local machine
```zsh
$ git clone git@github.com:icoldplayer/events.git

# move to events directory
$ cd events
```
Once you get the core project cloned into you machine, next is to clone the frontend / template.


```zsh
$ mkdir frontend & cd frontend 

# clone the frontend repo
$ git clone git@github.com:OkularID/RSTemplates.git
```

Create virtual environment on you machine
```zsh
$ python -m venv env

# activate it
$ source env/bin/activate
```

Install the project dependencies:
```zsh
$ pip install -r requirements.txt
```

Makemigrations & migrate

Linux / Mac
```zsh
# makemigrations
$ ./manage.py makemigrations

# migrate the dbs
$ ./manage.py migrate

# create superuser
$ ./manage.py createsuperuser
```

Windows
```bash
# makemigrate
$ python manage.py makemigrations

# dbs migrate
$ python manage.py migrate

# create user
$ python manage.py createsuperuser
```

Once all the project dependencies installed, you can now run the server with:

```zsh
# linux / mac
$ ./manage.py runserver

# windows
$ python manage.py runserver
```

That's all.


### To do list
- [ ] Pada saat status belum login - tombol get started di highlight dan tombol login di outline
- [ ] Pada saat status sudah login - tombol account di highlight dan tombol logout di outline
- [ ] spacing antara menu di navigasi utama dilebarin dikit
- [ ] perlu tambain bagian demo - seperti https://anrsvp.com/#home di bagian tengah page mereka kasi akses untuk orang test webnya
- [x] navigasi utama perlu tambain menu FAQ
- [x] paket produk di homepage linknya belum tersambung
- [x] send button di contact form ilang
- [x] warna di lengan baju anak kecil di bagian footer ilang
- [x] page Tour: bagian header seharusnya “Receiving” bukan “Recieving"
- [x] page why us: link untuk "show me the templates” salah
- [x] page why us: bagian bawah ”Lastly but not the last” seharusnya “Last but not the least”
- [ ] Untuk menu yang sedang dalam aktif page. pastikan di underline
