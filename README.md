### pagan
---
https://github.com/daboth/pagan

```
python setup.py install
pip install pagan

pagan hello
pagan -h

cd /tools/webserver/
python webserver.py
curl http://127.0.0.1:8080/

docker build -t pagan .
docker run -d -p 8080:8080 -t pagan
curl http://127.0.0.1:8080/
ssh -X pagan@dockercontainerip

pip install pytest
pytest
pip install tox
tox
```

```py
import pagan
inpt = 'pagan'
img = pagan.Avatar(inpt, pagan.SHA512)
img.show()
outpath = 'output/'
filename = inpt
img.save(outpath, filename)
img.change('new input', pagan.SHA256)
```

```
```


