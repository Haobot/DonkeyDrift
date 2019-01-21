# DonkeyDrift
This is a new project from Shanghai, China, which is originally based on DonkeyCar.
We have already modified several functions and locked tensorflow's version at tensorflow-1.8.0 and cloned the donkeycar version with v2.5.1 branch.

## Instruction and Tools:
| https://pan.baidu.com/s/1ClZaB69cioZtovuSzdv84g |
| ----------------------------------------------- |
| Password：or89                                  |

## Clone this repository:
```
git clone https://github.com/Haobot/DonkeyDrift

cd DonkeyDrift/
```

## Install DonkeyDrift:

```
activate donkey
pip install -e .
```

## Create new instance:

```
donkey createcar ./mycar
cd  mycar/
```

## Calibrate car:

```
donkey calibrate --channel = 0
donkey calibrate --channel = 1
```

## Drive car:

```
python manage.py drive 
```

## Train Model on PC or Server:
```
python manage.py train --tub=./data/your_tub_name --model=./models/your_model_name
```

## Test Model with Unity simulators:

```
donkey sim --model=./models/your_model_name --type=linear
```

P.S. Simulators are just works for Linux and MAC now, Windows version need to fix problems.

## Drive car with model for Auto Drive:

```
python manage.py drive --model=./models/your_model_name
```

## Have fun!