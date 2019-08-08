### python-user-agents
---
https://github.com/selwin/python-user-agents

```py
from user_agents import parse

ua_string = 'Mozilla/5.0 (iPhone; CPU iPhone 05 5_1 like Mac OS X) AppleWebKit/534.46 (KHTML, like Gecko) Version/5.0 Mobile/9B179 Safari/7534.48.3'
user_agent = parse(ua_string)

user_agent.browser
user_agent.browser.family
user_agent.browser.version
user_agent.browser.version_string

user_agent.os
user_agent.os.family
user_agent.os.version
user_agent.os.version_string

user_agent.device
user_agent.device.family
user_agent.device.brand
user_agent.device.model

str(user_agent)

from user_agents import parse

ua_string = 'BlackBerry9700/5.0.0.862 Profile/MIDP-2.1 Configuration/CLDC-1.1 VendorID/331 UNTRUSTED/1.0 3gpp-gba'
user_agent = parse(ua_string)
user_agent.is_mobile
user_agent.is_tablet
user_agent.is_touch_capable
user_agent.is_pc
user_agent.is_bot
str(user_agent)

ua_string = 'Mozilla/5.0(iPad; U; CPU iPhone OS 3_2 like Mac OS X; en-us) AppleWebKit/531.21.10 (KHTML, like Gecko) Version/4.0.4 Mobile/7B314 Safari/531.21.10'
user_agent = parse(ua_string)
user_agent.is_mobile
user_agent.is_tablet
user_agent.is_touch_capable
user_agent.is_pc
user_agent.is_bot
str(user_agent)

ua_string = 'Mozilla/5.0 (Macintosh; U; CPU iPhone OS 3_2 like Mac OS X; en-us) AppleWebKit/531.21.10 (KHTML, like Gecko) Version/4.0.4 Mobile/7B314 Safari/531.21.10'
user_agent = parse(ua_string)
user_agent.is_mobile
user_agent.is_tablet
user_agent.is_touch_capable
user_agnet.is_pc
user_agent.is_bot
str(user_agent)

ua_string = 'Mozilla/5.0 (Macintosh; U; Intel Mac OS X 10_6_3; en-us; Silk/1.1.0-80) AppleWebKit/533.16 (KHTML, like Gecko) Version/5.0 Safari/533.16 Silk-Accelerated=true'
ua_string = 'Mozilla/5.0 (compatible; MSIE 10.0; Windows NT 6.2; Trident/6.0; Touch)'
user_agent = parse(ua_string)
user_agent.is_mobile
user_agent.is_tablet
user_agent.is_touch_capable
user_agent.is_pc
user_agent.is_bot
str(user_agent)
```

```sh
pip install pyyaml ua-parser user-agents
python -m unittest discover
```

```
```


