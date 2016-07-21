# IdentityCard

A chinese identity card generator.

![screenshot](screenshot.png)



## Usage

### Command

```
Usage: IdentityCard.py [options] arg1 arg2
Options:
  --version   show program's version number and exit
  -h, --help  show this help message and exit
  --num=NUM   Number of idcardnumber [default: 1]
  --min=MIN   Minimum age [default: 0]
  --max=MAX   Maximum age [default: 100]
  --sex=SEX      Random 0, Female 1 or Male 2 [default: 0]
  --year=YEAR    Birth year [default: 0] 
  --month=MONTH   Birth month [default: 0] 
  --day=DAY      Birth day [default: 0]
```



### API

http://identity.daoapp.io/api

http://identity.daoapp.io/api?num=2

http://identity.daoapp.io/api?num=5&min=20

http://identity.daoapp.io/api?num=10&min=20&max=40

http://identity.daoapp.io/api?num=10&min=20&max=40&sex=1

http://identity.daoapp.io/api?num=3&min=20&max=40&sex=1&year=1988&month=4&day=20



### WEB

http://identity.daoapp.io/?num=2

http://identity.daoapp.io/?num=5&min=20

http://identity.daoapp.io/?num=10&min=20&max=40

http://identity.daoapp.io/?num=10&min=20&max=40&sex=1

http://identity.daoapp.io/?num=3&min=20&max=40&sex=1&year=1988&month=4&day=20