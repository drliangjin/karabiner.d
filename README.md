# oh-my-karabiner

## TODO:
- Ctrl_R to ?
- devices? swap Command with Alt if built-in macOS keyboard

- Ctrl + l
- Meta + l
- Ctrl + c
- Meta + c
- Ctrl + u
```
"description": "Change control+u to delete-to-beginning-of-line",
                                "from": {
                                    "key_code": "u",
                                    "modifiers": {
                                        "mandatory": [
                                            "control"
                                        ],
                                        "optional": [
                                            "caps_lock"
                                        ]
                                    }
                                },
                                "to": [
                                    {
                                        "key_code": "a",
                                        "modifiers": [
                                            "left_control",
                                            "left_shift"
                                        ]
                                    },
                                    {
                                        "key_code": "delete_or_backspace"
                                    },
                                    {
                                        "key_code": "vk_none"
                                    }
                                ],
                                "type": "basic"
                            },
```
- Meta + u


- Ctrl + w
- Ctrl + y
- Ctrl + j
```
"description": "Change control+j to return",
                                "from": {
                                    "key_code": "j",
                                    "modifiers": {
                                        "mandatory": [
                                            "control"
                                        ],
                                        "optional": [
                                            "caps_lock"
                                        ]
                                    }
                                },
                                "to": [
                                    {
                                        "key_code": "return_or_enter"
                                    }
                                ],
                                "type": "basic"
                            },
```
- Ctrl + a

- Ctrl + e
