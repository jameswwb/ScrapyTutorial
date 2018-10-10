# ScrapyTutorial
for study scrapy

## Setup Env
    - install Anaconda
        - install Scrapy under Anaconda
    - install VScode

## Startproject Tutorial
    - Create tutorial project
        scrapy startproject tutorial
    - run spider
        - scrapy crawl quotes

## Debug setting for Scrapy
    - Add configuration on launch.json

```
        {
            "name": "Scrapy",
            "type": "python",
            "request": "launch",
            "cwd":"${workspaceFolder}/tutorial",
            "module": "scrapy",
            "args": [
                "crawl",
                "quotes"
            ]
        },
```