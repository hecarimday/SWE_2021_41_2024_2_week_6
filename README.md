# SWE_2021_41_2024_2_week_6
---
## Week 4 Assignment
* Link of you repository
```python
def isHappy(n):
  look = set()
  while n not in look and n != 1:
    look.add(n)
    arr = [(int(m)) ** 2 for m in str(n)]
    n = sum(arr)

  if n == 1:
    return True
  else:
    return False
```
* Description of your code 
---
## Week 5 Assignment
> ```bash
> docker exec <your container> cat /etc/os-release
> ```
>* Explanation of commandline and your output

> ```bash
> docker exec <your container> git --version
> ```
>* Explanation of commandline and your output

> ```bash
> docker exec <your container> python3 --version
> ```
>* Explanation of commandline and your output

> ```bash
> docker inspect --format="{{ .HostConfig.Binds }}" <container_name>
> ```
>* Explanation of commandline and your output
