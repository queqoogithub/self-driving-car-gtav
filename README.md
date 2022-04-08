# self-driving-car-gtav :car:
* refactoring code to new year 2022 library version support 
* learning by doing the CNN on the self driving car.

## Steps
### Infra
* install GTA-V (Grand Theft Auto V)
* then open GTA-V you just to set the GTA-V screen to 800x600 (the smallest) and place it on top-left of your mornitor screen   
* install Native Trainer (Optional)
* pip install requirements.txt
### Run
* main.py => open the game to collect data (i recommend to adjust the view (by Ctrl+V) to first person view to fix the screen.)
* balance_data.py => to balance data (left-right keys)
* train_model.py => train (During training, i recommend to close the game to reduce the use of resource.)
* test_model.py => test with open the game

## Tensorboard
tensorboard --logdir=C:/Users/.../self_driving/log


## Credit and Source Code : 
* Sentdex 
* [https://pythonprogramming.net/game-frames-open-cv-python-plays-gta-v/]
