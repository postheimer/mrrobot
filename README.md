
## Getting Started

```
# apt install python3-pip
# pip3 install virtualenv
# virtualenv -p python3 venv
# . venv/bin/activate
# pip install -r requirements.txt
# pip install -r requirements-dev.txt
```

**Generating a wallet**

```
# python run.py client
MrRobot wallet > publickey
```
*copy your public key*
```
MrRobot wallet > privatekey
```
*copy your private key*

**Running a full node**
```
MrRobot wallet > quit
# python ./tools/encrypt.py
```
*enter a secure passphrase*
```
Choose a passphrase:
Re-enter your passphrase:
```
*enter your private key*
```
Secret:
Encrypted private key:
```
*copy your encrypted private key*

*edit config/config.yaml and populate the fields in the `user` section*

```
# python run.py full
MrRobot full node > help
```

**Running a mining node**
```
MrRobot full node > mine start
MrRobot full node > mine stop
```
