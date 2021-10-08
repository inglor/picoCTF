# Python Wrangling

Python scripts are invoked kind of like programs in the Terminal...

Can you run this Python script using this password to get the flag?

```bash
$  python --version                                                                                                                                                                      
Python 3.10.0
$ python 003_Python_Wrangling/ende.py
Traceback (most recent call last):
  File "/Users/inglor/workspace/picoCTF/003_Python_Wrangling/ende.py", line 4, in <module>
    from cryptography.fernet import Fernet
ModuleNotFoundError: No module named 'cryptography'
$ pip install cryptography
$ python 003_Python_Wrangling/ende.py -d 003_Python_Wrangling/flag.txt.en
Please enter the password:ac9bd0ffac9bd0ffac9bd0ffac9bd0ff
```

```text
picoCTF{4p0110_1n_7h3_h0us3_ac9bd0ff}
```
