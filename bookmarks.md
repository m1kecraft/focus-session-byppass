**Unencoded**

`data:text/html,%3Cscript%3E%0Avar%20win%3Dwindow.open%28%22https%3A//drive.google.com%22%29%0A%20%20%20%20win.document.write%28%60%0A%20%20%20%20%3Cstyle%3E%0A%20%20%20%20%20%20%20%20*%7Bmargin%3A0%3Bpadding%3A0%3Bborder%3Anone%3B%7D%0A%20%20%20%20%20%20%20%20iframe%7Bwidth%3A100vw%3Bheight%3A100vh%7D%0A%20%20%20%20%3C/style%3E%0A%20%20%20%20%3Ciframe%20id%3D%22frame%22%3E%3C/iframe%3E%0A%20%20%20%20%3Cscript%3E%0A%20%20%20%20var%20frame%3Ddocument.getElementById%28%22frame%22%29%3B%0A%20%20%20%20frame.setAttribute%28%22src%22%2Cprompt%28%22Insert%20link%20to%20embed%20%3A%22%2C%22insert%20link%20to%20website%22%29%29%0A%20%20%20%20%3C%5C/script%3E%0A%60%29%0A%20%20%20%20window.close%28%29%20%20%20%20%0A%3C/script%3E`

**Encoded**

`data:text/html;base64,PHNjcmlwdD4KdmFyIHdpbj13aW5kb3cub3BlbigiaHR0cHM6Ly9kcml2ZS5nb29nbGUuY29tIikKICAgIHdpbi5kb2N1bWVudC53cml0ZShgCiAgICA8c3R5bGU+CiAgICAgICAgKnttYXJnaW46MDtwYWRkaW5nOjA7Ym9yZGVyOm5vbmU7fQogICAgICAgIGlmcmFtZXt3aWR0aDoxMDB2dztoZWlnaHQ6MTAwdmh9CiAgICA8L3N0eWxlPgogICAgPGlmcmFtZSBpZD0iZnJhbWUiPjwvaWZyYW1lPgogICAgPHNjcmlwdD4KICAgIHZhciBmcmFtZT1kb2N1bWVudC5nZXRFbGVtZW50QnlJZCgiZnJhbWUiKTsKICAgIGZyYW1lLnNldEF0dHJpYnV0ZSgic3JjIixwcm9tcHQoIkluc2VydCBsaW5rIHRvIGVtYmVkIDoiLCJpbnNlcnQgbGluayB0byB3ZWJzaXRlIikpCiAgICA8XC9zY3JpcHQ+CmApCiAgICB3aW5kb3cuY2xvc2UoKSAgICAKPC9zY3JpcHQ+`

**Bookmarklet**

`javascript:(function()%7Bvar%20win%3Dwindow.open(%22https%3A%2F%2Fdrive.google.com%22)win.document.write(%60%3Cstyle%3E*%7Bmargin%3A0%3Bpadding%3A0%3Bborder%3Anone%3B%7Diframe%7Bwidth%3A100vw%3Bheight%3A100vh%7D%3C%2Fstyle%3E%3Ciframe%20id%3D%22frame%22%3E%3C%2Fiframe%3E%3Cscript%3Evar%20frame%3Ddocument.getElementById(%22frame%22)%3Bframe.setAttribute(%22src%22%2Cprompt(%22Insert%20link%20to%20embed%20%3A%22%2C%22insert%20link%20to%20website%22))%3C%5C%2Fscript%3E%60)window.close()%7D)()`
