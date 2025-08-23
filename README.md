## ACCESS GRANTED [NETRUNR VER.15.9329] CONNECTION STABLE [97.02%]



```text
               __                                                   
    ___   ____/ /____ _ ___   _____ __  __ ____   ____   ___   _____
   / _ \ / __  // __ `// _ \ / ___// / / // __ \ / __ \ / _ \ / ___/
  /  __// /_/ // /_/ //  __// /   / /_/ // / / // / / //  __// /    
  \___/ \__,_/ \__, / \___//_/    \__,_//_/ /_//_/ /_/ \___//_/     
              /____/                                                
```
Чумба, закинь демонов ему в локалку и валим, нас спалили

```python
from netrunutils import fastscan as fs
from kiroshi.targeted import networktarget as nt
import blackicexploit

def infiltrate():
    target = nt.get_current_target() 
    nodes = fs.scan(target, mode='stealth')
    exploit = blackicexploit.launch(
        target, nodes=nodes,
        type='overload',
        power='450',
        cpu='device_2_EOF19JG',
    )

    return exploit.is_successful()

# V1c5MUlHdHViM2NnZVc5MUlHUnBaRzRuZENCc2IzTmxJSFJvWlNCelpXeG1M
# V052Ym5SdmJBcE1aWFFuY3lCVGRHRnlkQ0JoZENCMGFHVWdjbUZwYm1KdmR3
# cG1jbTl0SUV4MVkza2dkRzhnUkdGMmFXUT0=

if __name__ == "__main__":
    success = infiltrate()
    exit(0 if success else 1)
```
У МЕНЯ НЕ КОМИТИТСЯ С ЭТОГО АККА НУ ЧТО ЗА НЕЗАДАЧА АХАХА)
Я НЕ ХОЧУ ТЕРЯТЬ АКТИВ ПОЭТОМУ Я ПРОСТО БУДУ СЮДА КОММИТИТЬ А ЧТО ПОДЕЛАТЬ) ПОТОМ ВОССТАНОВЛЮ ТАМ АКТИВ(
а самое главное ребят....

друзья я коммичу ну вы поймите я не могу аккаунты поменять прошу поймите
David: 1.3_5-da3monsneverstop caf

[CONNECTION STABLE]:
_timelog_: 2079.11.14_17:35:11
