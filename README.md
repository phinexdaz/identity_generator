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
```



### API

http://127.0.0.1:5000/api/identidycard

http://127.0.0.1:5000/api/identidycard?num=2

http://127.0.0.1:5000/api/identidycard?num=5&min=20

http://127.0.0.1:5000/api/identidycard?num=10&min=20&max=40

http://127.0.0.1:5000/api/identidycard?num=10&min=20&max=40&sex=1



### WEB

http://127.0.0.1:5000/?num=2

http://127.0.0.1:5000/?num=5&min=20

http://127.0.0.1:5000/?num=10&min=20&max=40

http://127.0.0.1:5000/?num=10&min=20&max=40&sex=1




