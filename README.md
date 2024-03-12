# PyBSVSend

![bsv dragon](/docs/SV_dragon_cmyk.gif)
***
Python script to send BSV to a wallet. Supports Testnet and Mainnet.

Used [Austecon bitsv guide](https://austecon.github.io/bitsv/guide/keys.html)


### Setup
***

Python 3.12.2. You can install the [bitsv](https://austecon.github.io/bitsv/guide/keys.html) library or use the requirements.txt file provided.

```
pip install -r requirements.txt
```
or 

```
python3 -m pip install bitsv
```

Add your private key locally using the export command. 

```
export CLIENT_PRIVATE_KEY="paste your private key here"
```

Add the wallet address you are sending BSV to by using the export command. 

```
export CLIENT_ADDRESS="paste wallet address here"
```

Send your money

```
python send.py
```





