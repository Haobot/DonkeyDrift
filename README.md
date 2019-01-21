# DonkeyDrift
This is a new project which is based on donkeyCar.
We have already modified the video capture algorithm and locked tensorflow's version at tensorflow-1.8.0 and cloned the donkeycar version with 2.5.1 branch.
* You can download the model that we have already trained at local.
* You can join us and give us some advices. 
## How to use it
* clone the repository by:
* git clone https://github.com/Mavengers/DonkeyDrift
* cd DonkeyDrift/
## How to create a new car instance. 
*  $donkey createcar ./mycar
## How to train my car.
* $python manager.py train --tub=./data/your_tub_name --model=./models/your_model_name
## How to dirve my car.
* $python manager.py drive 
## Have fun!

