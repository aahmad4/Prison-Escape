<h1 align="center">Prison Escape</h1> 

<p align="center">
An aerial prison escape game made with Python and Pygame. I created this game out of a personal interest for Pygame and to get better at object orientated programming at the same time. This was definitely a fun game to make as well as a fun game to play.
</p>

<p align="center">
A link to an online demo version can be found here: <a href="https://repl.it/@aahmad4/Prison-Escape
" target="_blank">repl.it/@aahmad4/Prison-Escape</a>
</p>

## Gameplay Snippet

![](assets/gameplay.gif)

## Rules

The rules of the game are very simple:
* Upon initializing the game, there are 5 lives given and you are spawned in level 1. After clearing a certain amount of prisoners, you can regenerate to the next level. 
* Below your character, the police man, there is a health bar which keeps track of your current hitpoints. If you loose all your hitpoints, the game ends. You loose hitpoints by running into a prisoner or by getting shot by one of their lasers.
* Likewise, everytime a prisoner gets past you, you loose a life. If you hit 0 lives, the game ends.
* Move the character with your arrow keys and shoot your lasers with the space bar. 

## Setup

#### Clone
```
git clone https://github.com/aahmad4/Prison-Escape
```

#### Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required packages.
```
pip install -r requirements.txt
```

#### Usage
```
cd Prison-Escape
```

```
python main.py
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
