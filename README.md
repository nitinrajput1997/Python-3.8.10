# Python-3.8.10

```bash
sudo apt install build-essential zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev libssl-dev libreadline-dev libffi-dev libsqlite3-dev wget libbz2-dev
wget https://www.python.org/ftp/python/3.8.10/Python-3.8.10.tgz
tar -xf Python-3.8.10.tgz
```

Install
```bash
cd Python-3.8.10
./configure --enable-optimizations
make -j 8
sudo make altinstall
python3 --version
```

