Windows app that combines different APIs (<a href="http://www.xfyun.cn/services/voicedictation">iFlytek-科大讯飞</a>, <a href="https://traslate.google.cn">Google Translate</a>, <a href="https://azure.microsoft.com/en-us/services/cognitive-services/speech/">Bing Speech</a>, <a href="http://fanyi-api.baidu.com/api/trans/product/index">Baidu Translate</a>) to get the best translated caption/subtitles for China market:

<p align="center"><img src="https://user-images.githubusercontent.com/24521991/32063973-2f13fd20-baab-11e7-93c1-61155a152a3c.png" width="500"></p>

<p align="center">Except Google Translate, for each other service you need to get an ID</p>
<br/>

Screenshot of the program:
<p align="center"><img src="https://user-images.githubusercontent.com/24521991/32085308-d218c690-bb00-11e7-86d1-debebfe03c76.jpg"></p>
<ul>Comments:
<li>No matter what is on the screen (powerpoint, video, etc.) the subtitles will always be on top of it</li>
</ul>
<br/>

1. For a speaker that talks in Chinese and requires English caption/subtitles on the screen, the program uses:
  Chinese voice recognition (iFlytek-科大讯飞) + Chinese to English translation (Google Translate)

<p align="center"><img src="https://user-images.githubusercontent.com/24521991/32063586-2729e396-baaa-11e7-9f0d-71f921fba63f.png" width="500"></p>
<br/>

2. For a speaker that talks in English and requires Chinese caption/subtitles on the screen, the program uses:
  English voice recognition (Bing Speech) + English to Chinese translation (Baidu Translate)

<p align="center"><img src="https://user-images.githubusercontent.com/24521991/32063559-108eba8a-baaa-11e7-93b2-f4baecc82aff.png" width="500"></p>

Open to any suggestion! Thanks!!
