# pysteam

Python API for accessing local Steam information

## Currently Supported

* Get a list of all users that have logged in on the machine
* Convert between Steam community ID 32 and community ID 64
* Detect the location of the userdata folder
* Get a list of all non-Steam games for a user
* Set custom images for Steam games and non-Steam games

## Running the code

### Windows

Tested at git bash.

* Install python 2.7 and set up environment path with python
* Download [get-pip.py](https://bootstrap.pypa.io/get-pip.py), being careful to save it as a .py file rather than .txt.
* Install pip if you don't have it:
```sh
python get-pip.py
```
* Update pip if needed (at pip path)
```sh
./pip.exe install --upgrade pip
```
* Install dependencies
```sh
python setup.py install
```

### GNU/Linux or macOS

* Install python 2.7
* Install pip
```sh
pip install -U pip
```
* Update pip if needed
```sh
sudo pip install --upgrade pip
```
* Install dependencies
```sh
sudo python setup.py install
```

## Testing

* To run all unit test, at main path execute:
```
python -m unittest discover tests
```
