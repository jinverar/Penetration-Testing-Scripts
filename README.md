# Penetration-Testing-Scripts
My recon and vuln scripts

These files are ment to work with juypter notebook.

# requirements

juypter notebook
```
pip3 install --upgrade pip

pip3 install jupyter
```

# run juypter

jupyter notebook

# enable ssl with juypter
```
openssl req -x509 -nodes -days 365 -newkey rsa:1024 -keyout mykey.key -out jupytercert.pem

jupyter notebook  --config=/home/*user*/.jupyter/jupyter_notebook_config.py --certfile=/home/*user*/.jupyter/jupytercert.pem --keyfile /home/*user*/.jupyter/mykey.key --ip=*ip*
```
# play with some juypter extentions
```
pip install jupyter_contrib_nbextensions

jupyter contrib nbextension install --user

pip install --upgrade six

jupyter nbextension list
```
# enable drag and drop with juypter
```
jupyter nbextension enable dragdrop
```
https://*ipaddress*:8888/nbextensions
```
make sure to uncheck the box unter configureable nbextensions > then enable drag and drop
```

Please help Contribute!

1. Fork it!
2. Create your feature branch: git checkout -b my-new-feature
3. Commit your changes: git commit -am 'Add some feature'
4. Push to the branch: git push origin my-new-feature
5. Submit a Pull Request
