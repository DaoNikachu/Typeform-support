0. https://hiretechfast.typeform.com/to/OevzxRDD
1. There is a problem with thankyou_screen. Property "redirect_url" is not working as expected. There is necessary ending, but lack of redirecting.
  How to fix it to redirect to url, when the ending is encountered?
  {
            "ref": "successful_tys",
            "title": "_",
            "properties": {
                "redirect_url": "https://example.com",
                "show_button": false,
                "share_icons": false
            }
        }
2. Another issue is the block of code in logic related to adding a value to a variable. There is condition from yes_no question type, and
  I don't fully understand how to render it with specific equal condition. Postman gives an error.
  {
            "type": "field",
            "ref": "20547658-3011-4f1f-a1b2-01974a99dfa7",
            "actions": [
                {
                    "action": "add",
                    "details": {
                        "target": {
                            "type": "variable",
                            "value": "is_moveable"
                        },
                        "value": {
                            "type": "constant",
                            "value": 1
                        }
                    },
                    "condition": {
                        "op": "equal",
                        "vars": [
                            {
                                "type": "field",
                                "value": "20547658-3011-4f1f-a1b2-01974a99dfa7"
                            },
                            {
                                "type": "boolean",
                                "value": true
                            }
                        ]
                    }
                }
            ]
        }
