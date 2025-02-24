# spot
* download python 3.9.8
* type python to check the version
* cd into Folder named Spot
* python3 -m pip install bosdyn-client==4.0.3 bosdyn-mission==4.0.3 bosdyn-choreography-client==4.0.3 bosdyn-orbit==4.0.3
* python3.9 -m venv spot_env
* source spot_env/bin/activate (mac)
* .\spot_env\Scripts\activate.bat (windows)

## spot_env
cd spot_env

## spot-sdk
* git clone https://github.com/boston-dynamics/spot-sdk.git
* cd spot-sdk
* git reset --hard 665de1bc1467c86e97cca9df905aa6e9a2c0a5a8
* cd python/examples/**Any File**
* python3 -m pip install -r requirements.txt
* python3 **Any File**.py **Spot's IP**
