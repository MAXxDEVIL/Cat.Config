```bash

{
    "$schema": "https://github.com/fastfetch-cli/fastfetch/raw/dev/doc/json_schema.json",
    "logo": {
        "source": "~/Pictures/Imp/crp.png",
        "type": "kitty",
        "height": 17,
        "width": 41,
        "padding": {
            "top": 4,
            "left": 1
        }
    },
    "modules": [
        "break",
        {
            "type": "custom",
            "format": "\u001b[90m┌──────────────────────Hardware──────────────────────┐"
        },
        {
            "type": "host",
            "key": " PC",
            "keyColor": "#5aba06"
        },
        {
            "type": "cpu",
            "key": "│ ├",
            "keyColor": "#5aba06"
        },
        {
            "type": "gpu",
            "key": "│ ├󰍛",
            "keyColor": "#5aba06"
        },
        {
            "type": "memory",
            "key": "│ ├󰍛",
            "keyColor": "#5aba06"
        },
        {
            "type": "custom",
            "format": "\u001b[90m└────────────────────────────────────────────────────┘"
        },
        "break",
        {
            "type": "custom",
            "format": "\u001b[90m┌──────────────────────Software──────────────────────┐"
        },
        {
            "type": "os",
            "key": "󰣇 OS",
            "keyColor": "#5aba06"
        },
        {
            "type": "kernel",
            "key": "│ ├",
            "keyColor": "#5aba06"
        },
        {
            "type": "packages",
            "key": "│ ├󰏖",
            "keyColor": "#5aba06"
        },
        {
            "type": "shell",
            "key": "└ └",
            "keyColor": "#5aba06"
        },
        "break",
        {
            "type": "de",
            "key": " DE",
            "keyColor": "#5aba06"
        },
        {
            "type": "lm",
            "key": "│ ├",
            "keyColor": "#5aba06"
        },
        {
            "type": "wm",
            "key": "│ ├",
            "keyColor": "#5aba06"
        },
        {
            "type": "wmtheme",
            "key": "└ └󰉼",
            "keyColor": "#5aba06"
        },
        {
            "type": "custom",
            "format": "\u001b[90m└────────────────────────────────────────────────────┘"
        },
        "break",
        {
            "type": "custom",
            "format": "\u001b[90m┌────────────────────Uptime / Age────────────────────┐"
        },
        {
            "type": "command",
            "key": "  OS Age ",
            "keyColor": "#5aba06",
            "text": "birth_install=$(stat -c %W /); current=$(date +%s); time_progression=$((current - birth_install)); days_difference=$((time_progression / 86400)); echo $days_difference days"
        },
        {
            "type": "uptime",
            "key": "  Uptime ",
            "keyColor": "#5aba06"
        },
        {
            "type": "custom",
            "format": "\u001b[90m└────────────────────────────────────────────────────┘"
        },

//        {
//            "type": "colors"
//        },



    ]
}


```