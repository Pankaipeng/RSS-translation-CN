# rss-translate

rss translate any to any

![](https://github.com/Pankaipeng/RSS-Translation/workflows/circle_translate/badge.svg)
![](https://github.com/Pankaipeng/RSS-Translation/workflows/Deploy/badge.svg)

you can edit [test.ini](https://github.com/Pankaipeng/RSS-Translation/edit/main/test.ini) to add orginal rss url. [help](https://github.com/Pankaipeng/RSS-Translation/issues/2)

next find the translated link in [https://talengu.github.io/rss-translate/](https://talengu.github.io/rss-translate/)

## 20230814 update
- support proxy mode. you can set `action = "proxy"` in test.ini like [source010](https://github.com/Pankaipeng/RSS-Translation/blob/f6648c5262f4fa0926310dbe43fff820bf727ac7/test.ini#L67)

## 20230702 update 
- use [main2.py](https://github.com/Pankaipeng/RSS-Translation/blob/main/main2.py) in [circle_translate.yml](https://github.com/Pankaipeng/RSS-Translation/blob/aeb61bc36eb1a22fd003677b5209291cf7cb4a87/.github/workflows/circle_translate.yml#L38)
- atom is bad now base on an atom paraser to find. NOW SUPPORT
        use [feedparser](https://pythonhosted.org/feedparser/)
- fix google translate limit . NOW SUPPORT

## rss translate links

 - source001 [https://rsshub.app/economist/latest](https://rsshub.app/economist/latest) -> [economist_latest_cn.xml](rss/economist_latest_cn.xml)
 - source002 [https://news.ycombinator.com/rss](https://news.ycombinator.com/rss) -> [hacker_news_cn.xml](rss/hacker_news_cn.xml)
