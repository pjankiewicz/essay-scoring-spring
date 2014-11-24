Installation
========================

This code uses Python. Linux environment is needed for the code to run smoothly.

Setting up the environment

**Create Python environment** 
```
virtualenv --no-site-packages env
```

**Activate the environment**
```
source env/bin/activate
```

**Install requirements**
```
pip install -r requirements.txt
```

Importing data
========================

1. Put xml files in data/xml/training/ and data/xml/validation
2. Run script

```
python 1_import_raw_data.py
```

It will combine and transform the XML files into CSV format.


Creating models
========================

