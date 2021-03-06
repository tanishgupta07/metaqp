## metaqp 
**The metaX Project: Question paper search**

[![forthebadge made-with-javascript](http://ForTheBadge.com/images/badges/made-with-javascript.svg)](https://www.node.org/)
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
![metaqp](https://github.com/akhilesh-k/metaqp/blob/master/resources/images/test.png)

Aki is a studious child. Seriously? Is he lazy? Not at all! 
He always keeps asking, 'How to get the freaking question papers?'. He is in search of his Question papers for T1 and sick of clicking numerous folders for hours on the boring dot6 space. Boom! He got an idea. He started to search the question papers from the search bar. He went to dot6. 

Wow! What a beautiful place it is! He found the Question paper and checked department semesters, examinations, found out the matching one, and finally, he solved the paper. 

Maybe it was too late and some stud who had a better access, solved papers much before. Aki asked him, 'Bro, how did you find it earlier?'. He replied, 'Use **MetaQP** son!'.

### Development

**Host machine**

```
$ git clone https://github.com/akhilesh-k/metaqp.git
$ cd metaqp
$ sudo npm install http-server
$ http-server metaqp
```

### Generating Data in JSON format

`python3 build_search_data.py`

This script logs the address of question paper files and output the required JSON data.

#### Buitifying `data.json`

You can use any JSON utility that is installed on your computer.
[`jq`](https://stedolan.github.io/jq/) is recommended.

```sh
$ jq '' data/list.json > data/data.json
$ mv data/data.json data/list.json
```

## Wiki
We've a list of FAQ [here](https://github.com/metajuit/metaqp/wiki/FAQ). If you've any queries, find the answer from there. If your question is not there, add it by yourself. We would love to answer.

## Contributions

PRs are most welcome!

[![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html)

## Contributor


Made with <span style="font-size:130%;color:red;">&hearts;</span> [Akhilesh Kumar](http://akhileshkumar.me), [Lavish Kumar](github.com/lavish-kumar) and [Prashasy Ashok](http://github.com/prashasy)

## Data Contributor
+ [Samad Khan](https://github.com/khansamad99)
+ [Prakhar Singh]()
+ [Bhawna Dey]()
+ [Sudhanshu Sridhar]()
+ [Varun Singh]()
+ [Astitva Shrestha]()
+ [Arpit Garg]()


## Maintainer

[Akhilesh Kumar](http://akhileshkumar.me) (@akhilesh-k on [metajuit Slack](https://metajuit.herokuapp.com).)

