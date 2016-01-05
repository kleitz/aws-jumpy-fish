AWS Jumpy Fish for Shanghai Submit 2015
===========

A Lambda Function as "Flappy Bird" like game backend.

![](architect.png)


## Running on AWS

- Create a bulket on S3 and enable the static website feather, upload all the static resources to this bulket.

- Create a lambda function used the [source code](lambda_functions/aws-bird.js)

- Create a DynomDB table named `aws-bird-highscore` used `uuid` as hash index.

- At last brower the S3 website to test!



## Some nice games made with this project

- **Campaja 404 page** - http://campanja.com/404/ (Wait 10 seconds before the game start)
- **Clumsy Marlet** by [@amedeedaboville](http://github.com/amedeedaboville) - http://amedeedaboville.github.io/clumsy-martlet/
- **Flappy Flamant** by [@leliondoc](http://github.com/leliondoc) - http://gruissan-mediterranee dot com/flappyflamant/
- **Hungry Willbo** by [@dougdiehnelt](http://github.com/dougdiehnelt), [@ferentchak](http://github.com/ferentchak) [@willklein](http://github.com/willklein) and [@city41](http://github.com/city41) - http://hungrywillbo.com/
- **Flappy Dragon** by [@sunzhuoshi](http://github.com/sunzhuoshi) - http://flappydragon.net
- **BurguerFest** by [@PanManAms](http://github.com/panmanams) - http://burgerfest.nl
- **Flappy Tom**  by [@jeshuamaxey](http://github.com/jeshuamaxey) - http://votetom.in/flappy-tom
- **Clippy Jam** by [@jkeatinco](http://github.com/jkeatinco) - http://jkeatinco.github.io/
- **Ducky momo** by [@codex8](http://github.com/codex8) - https://ilmtechlab.com/DuckyMomo/
- **Derpy Duck** by [@EmmettTan](http://github.com/emmettTan) and [@TheOneAmir](http://github.com/theoneamir) - http://ahdavies.github.io/Derpy-Duck/
- **Flippy Cat** (@Github's Game Off 2015 Winner) by [@t4nuj](http://github.com/t4nuj) - https://t4nuj.github.io/clumsy-bird

If you made something with this code, please [share here](https://github.com/ellisonleao/clumsy-bird/wiki/Games-using-clumsy-bird-code) and i'll be happy to add your game into the list.

Thanks a lot for our HK SA for contribute [Ellison Leão](https://medium.com/@ellisonleao/clumsy-bird-an-open-source-flappy-bird-clone-cf615724730f)
