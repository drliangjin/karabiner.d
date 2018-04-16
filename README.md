# oh-my-karabiner

## TODO:
- CapsLock to Ctrl_L, ESC if pressed alone;
- Enter to Ctrl_R, Enter if pressed alone;
- Ctrl_L to Hyper
- Ctrl_R to ?
- swap Command with Alt if built-in macOS keyboard

- Ctrl + v
```
{
                                "from": {
                                    "key_code": "v",
                                    "modifiers": {
                                        "mandatory": [
                                            "right_control"
                                        ],
                                        "optional": [
                                            "any"
                                        ]
                                    }
                                },
                                "to": [
                                    {
                                        "key_code": "page_down"
                                    }
                                ],
                                "type": "basic"
                            }
```
- Meta + v
```
{
                                "from": {
                                    "key_code": "v",
                                    "modifiers": {
                                        "mandatory": [
                                            "right_option"
                                        ],
                                        "optional": [
                                            "any"
                                        ]
                                    }
                                },
                                "to": [
                                    {
                                        "key_code": "page_up"
                                    }
                                ],
                                "type": "basic"
                            }
```
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
- Ctrl + h
```
"from": {
                                    "key_code": "h",
                                    "modifiers": {
                                        "mandatory": [
                                            "left_control"
                                        ],
                                        "optional": [
                                            "caps_lock",
                                            "option"
                                        ]
                                    }
                                },
                                "to": [
                                    {
                                        "key_code": "delete_or_backspace"
                                    }
                                ],
                                "type": "basic"
                            },
```
- meta + h

- ctrl + d
```
"from": {
                                    "key_code": "d",
                                    "modifiers": {
                                        "mandatory": [
                                            "left_control"
                                        ],
                                        "optional": [
                                            "caps_lock",
                                            "option"
                                        ]
                                    }
                                },
                                "to": [
                                    {
                                        "key_code": "delete_forward"
                                    }
                                ],
                                "type": "basic"
                            }
```
- meta + d



- Ctrl + i
```
"from": {
                                    "key_code": "i",
                                    "modifiers": {
                                        "mandatory": [
                                            "left_control"
                                        ],
                                        "optional": [
                                            "caps_lock"
                                        ]
                                    }
                                },
                                "to": [
                                    {
                                        "key_code": "tab"
                                    }
                                ],
                                "type": "basic"
                            },
```
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
- Ctrl + b ==> left_arrow

- Ctrl + f ==> right_arrow

- Ctrl + n ==> down_arrow

- Ctrl + p ==> up_arrow

- Ctrl + a

- Ctrl + e
