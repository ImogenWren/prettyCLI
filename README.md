# prettyCLI
Python Dictionary for Command Line Interface text formatting


Text Foreground Colour: Usually Supported
Sample Text Here, FG Colour:  default       
Sample Text Here, FG Colour:  black       
Sample Text Here, FG Colour:  red       
Sample Text Here, FG Colour:  green       
Sample Text Here, FG Colour:  brown       
Sample Text Here, FG Colour:  lilac       
Sample Text Here, FG Colour:  magenta       
Sample Text Here, FG Colour:  dark-cyan       
Sample Text Here, FG Colour:  grey       
Sample Text Here, FG Colour:  dark-grey       
Sample Text Here, FG Colour:  rich-red       
Sample Text Here, FG Colour:  deep-green       
Sample Text Here, FG Colour:  yellow       
Sample Text Here, FG Colour:  blue       
Sample Text Here, FG Colour:  pink       
Sample Text Here, FG Colour:  cyan       
Sample Text Here, FG Colour:  white       

Text Background Colour: Usually Supported
Sample Text Here, BG Colour:  default       
Sample Text Here, BG Colour:  default       
Sample Text Here, BG Colour:  black       
Sample Text Here, BG Colour:  black       
Sample Text Here, BG Colour:  salmon       
Sample Text Here, BG Colour:  salmon       
Sample Text Here, BG Colour:  green       
Sample Text Here, BG Colour:  green       
Sample Text Here, BG Colour:  brown       
Sample Text Here, BG Colour:  brown       
Sample Text Here, BG Colour:  lilac       
Sample Text Here, BG Colour:  lilac       
Sample Text Here, BG Colour:  magenta       
Sample Text Here, BG Colour:  magenta       
Sample Text Here, BG Colour:  dark-cyan       
Sample Text Here, BG Colour:  dark-cyan       
Sample Text Here, BG Colour:  grey       
Sample Text Here, BG Colour:  grey       
Sample Text Here, BG Colour:  dark-grey       
Sample Text Here, BG Colour:  dark-grey       
Sample Text Here, BG Colour:  rich-red       
Sample Text Here, BG Colour:  rich-red       
Sample Text Here, BG Colour:  deep-green       
Sample Text Here, BG Colour:  deep-green       
Sample Text Here, BG Colour:  yellow       
Sample Text Here, BG Colour:  yellow       
Sample Text Here, BG Colour:  blue       
Sample Text Here, BG Colour:  blue       
Sample Text Here, BG Colour:  pink       
Sample Text Here, BG Colour:  pink       
Sample Text Here, BG Colour:  cyan       
Sample Text Here, BG Colour:  cyan       
Sample Text Here, BG Colour:  white       
Sample Text Here, BG Colour:  white       

Text FX: Often Unsupported
Sample Text Here, Effect:  bold       
Sample Text Here, Effect:  ul       
Sample Text Here, Effect:  nul       
Sample Text Here, Effect:  blink       
Sample Text Here, Effect:  noblink       
Sample Text Here, Effect:  inv       
Sample Text Here, Effect:  ninv       
Sample Text Here, Effect:  frame       
Sample Text Here, Effect:  noframe       
Sample Text Here, Effect:  cir       
Sample Text Here, Effect:  nocir       
Sample Text Here, Effect:  over       
Sample Text Here, Effect:  nover       

Text Fonts: Often Unsupported
Sample Text Here, Font:  0       
Sample Text Here, Font:  1       
Sample Text Here, Font:  2       
Sample Text Here, Font:  3       
Sample Text Here, Font:  4       
Sample Text Here, Font:  5       
Sample Text Here, Font:  6       
Sample Text Here, Font:  7       
Sample Text Here, Font:  8       
Sample Text Here, Font:  9       
Sample Text Here, Font:  default       


```
pcli = {
    "df":"\033[0m",
    "default":"\033[0m",
    "reset":"\033[0m",
    "fg":{
        "default": "\033[39m",
        "black":"\033[30m",
        "red":"\033[31m",
        "green":"\033[32m",
        "brown":"\033[33m",
        "lilac":"\033[34m",
        "magenta":"\033[35m",
        "dark-cyan":"\033[36m",
        "grey":"\033[37m",
        "dark-grey": "\033[90m",
        "rich-red": "\033[91m",
        "deep-green": "\033[92m",
        "yellow": "\033[93m",
        "blue": "\033[94m",
        "pink": "\033[95m",
        "cyan": "\033[96m",
        "white": "\033[97m",
    },
    "bg": {
        "default":"\033[49m",
        "black": "\033[40m",
        "salmon": "\033[41m",
        "green": "\033[42m",
        "brown": "\033[43m",
        "lilac": "\033[44m",
        "magenta": "\033[45m",
        "dark-cyan": "\033[46m",
        "grey": "\033[47m",
        "dark-grey": "\033[100m",
        "rich-red": "\033[101m",
        "deep-green": "\033[102m",
        "yellow": "\033[103m",
        "blue": "\033[104m",
        "pink": "\033[105m",
        "cyan": "\033[106m",
        "white": "\033[107m",
    },
    "font":{
        0 :"\033[10m",
        1 :"\033[11m",
        2 :"\033[12m",
        3 :"\033[13m",
        4 :"\033[14m",
        5 :"\033[15m",
        6 :"\033[16m",
        7 :"\033[17m",
        8 :"\033[18m",
        9 :"\033[19m",
        "default":"\033[10m"
    },
    "fx":{
    "bold":"\033[1m",
    "ul":"\033[4m",
    "nul":"\033[24m",
    "blink":"\033[5m",
    "noblink":"\033[25m",
    "inv":"\033[7m",
    "ninv":"\033[27m",
    "frame":"\033[51m",
    "noframe": "\033[54m",
    "cir": "\033[52m",
    "nocir": "\033[54m",
    "over": "\033[53m",
    "nover": "\033[55m"
    }
}
```

