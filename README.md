# CLUS 2019 DEVWKS-1671

This repository contains code examples and Lab Guide used for DEVWKS-1671 Programmability with SD-WAN session.

## Requirements

To run the Labs on this workshop you will need.

* Postman
* Python 3.6+


### Install and Setup

Clone the code to your local machine.

```
git clone https://github.com/jaileon/DEVWKS-1671.git
cd DEVWKS-1671
```

Setup Python Virtual Environment (requires Python 3.7+)

```
virtualenv devwks-1671 -p python3.7
source devwks-1671/bin/activate
pip install -r requirements.txt
```


### Using the Scripts

Once installed and setup, you can now get started (i.e.)


`python CL2019_LAB2.py`

OUTPUT

```
Please choose a valid option:
1- Create Aplication Aware Routing Policy (DC1 --> BR3). POST.
2- Create Template Policy. POST.
3- Activate Policy. POST.
4- Deactivate Policy. POST
Press any key to exit.

YOUR OPTION?:
```
### POSTMAN

I've also included a POSTMAN collection as json file or link to import it.

	https://www.getpostman.com/collections/a15b3e29d99f54a56d86
