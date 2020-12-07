# wanmei_campus
完美校园模拟登录

```python3
from Card import open_device, CampusCard

if __name__ == '__main__':
    campus = CampusCard("17321026644", "ZJzjzj228039", open_device('userinfo.txt'))
    bills = campus.get_bill("2019-06-01", "2019-07-31")
    print(campus.get_main_info())
    print(bills)
```
