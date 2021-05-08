---
title: Haikou Temples with Photos
---

### Qiongtai Fudi (琼台福地 Qióng tái fúdì)Temple on Wenzhuang Road (文庄路 Wén zhuāng lù):

Well looked after, medium sized temple built to protect the local area. Lots of detailed stone carvings.
<div class="mb-5" id="fudi-photos" style="max-width:90%;margin:auto"></div>

### Qiongtai College (琼台书院 Qióng tái shūyuàn)

This is not actually a temple but an ancient college. Qiongtai College is credited with bringing modern academic study
to Hainan from elsewhere in China. The interior has been restored and in some ways looks similar to a temple. Part of
the college space is often used as an art gallery for locally inspired art.

Entrance fee: 5 RMB
<div id="qiongtai-college-photos" style="max-width:90%;margin:auto"></div>

### Five Officials Temple (五公祠 Wǔ gōng cí)

Photos of Five Officials Temple (五公祠 Wǔ gōng cí)
<div id="wugongci-photos" style="max-width:90%;margin:auto"></div>

### Lake Temple 湖中寺 Hú zhōng sì

A real temple still used by Buddhists. Normally most lively in the morning, expect lots of incense, chanting, and music.

Near Xiuying port on Haigang Road (海港路 Hǎigǎng lù) behind the Kaiwei Hotel (凯威大酒店 Kǎi wēi dà jiǔdiàn).

Buddha's Birthday ceremonies normally held in June.

Buses: 28, 7, 6, 39, 35.

Lake Temple Photos:

<div id="lake-temple-photos" style="max-width:90%;margin:auto"></div>

### Baishamen Tianhou Temple 白沙门天后宫 Báishā mén tiān hòugōng

This small temple is situated in Baishamen Village on Haidian Island in the north of Haikou City.

The temple is dedicated to Mazu. Mazu (妈祖, māzǔ) is a sea goddess from the first century AD and is worshipped by Chinese
fisherman in the south-east of China.

The temple was first built in the Song Dynasty by a merchant from Fujian Province. It has since been rebuilt 4 times.


### Tianning Temple 天宁寺 Tiān níng sì

Small, one room temple near Five Officials Temple.

Address: 海口市琼山区红城湖路, Hǎikǒu shì, qióngshān qū, hóngchéng hú lù

<div class="mb-5" id="tianning-temple-photos" style="max-width:90%;margin:auto"></div>


#### Other Temples in and around Haikou

Renxin Temple on Haidian Island, 仁心寺, Rén xīn sì.

Shengmu Temple 圣母庙 Shèngmǔ miào

地址：海口市龙华区海垦路

Guansheng Temple 关圣庙 Guān shèngmiào

地址：海口市山高路附近

Taihua Nunnery 泰华寺 Tài huá sì (aka: 泰华庵 Tài huá Ān)

Located in Lingshan.
永庆寺 Yǒng qìng sì

<div id="haidian-temples-photos" style="max-width:90%;margin:auto"></div>

<script src="https://product-gallery.cloudinary.com/all.js" type="text/javascript"></script>

<script type="text/javascript">
  // temples tab galleries
  const fudiGallery = cloudinary.galleryWidget({
    "container": "#fudi-photos",
    "cloudName": "dfjb9p5ri",
    "displayProps": {
      "mode": "expanded",
      "columns": 3
    },
    "mediaAssets": [{ tag: "fudi-temple" }],
    "zoomProps": { "type": "popup", "trigger": "click" }
  });
  const qiongtaiGallery = cloudinary.galleryWidget({
    "container": "#qiongtai-college-photos",
    "cloudName": "dfjb9p5ri",
    "displayProps": {
      "mode": "expanded",
      "columns": 3
    },
    "mediaAssets": [{ tag: "qiongtai-college" }],
    "zoomProps": { "type": "popup", "trigger": "click" }
  });
  const wugongciGallery = cloudinary.galleryWidget({
    "container": "#wugongci-photos",
    "cloudName": "dfjb9p5ri",
    "displayProps": {
      "mode": "expanded",
      "columns": 3
    },
    "mediaAssets": [{ tag: "wugongci" }],
    "zoomProps": { "type": "popup", "trigger": "click" }
  });

  const lakeTempleGallery = cloudinary.galleryWidget({
    "container": "#lake-temple-photos",
    "cloudName": "dfjb9p5ri",
    "displayProps": {
      "mode": "expanded",
      "columns": 3
    },
    "mediaAssets": [{ tag: "lake-temple" }],
    "zoomProps": { "type": "popup", "trigger": "click" }
  });
  const tianningGallery = cloudinary.galleryWidget({
    "container": "#tianning-temple-photos",
    "cloudName": "dfjb9p5ri",
    "displayProps": {
      "mode": "expanded",
      "columns": 3
    },
    "mediaAssets": [{ tag: "tianning-temple" }],
    "zoomProps": { "type": "popup", "trigger": "click" }
  });
  const haidianGallery = cloudinary.galleryWidget({
    "container": "#haidian-temples-photos",
    "cloudName": "dfjb9p5ri",
    "displayProps": {
      "mode": "expanded",
      "columns": 3
    },
    "mediaAssets": [{ tag: "haidian-temples" }],
    "zoomProps": { "type": "popup", "trigger": "click" }
  });


  console.log("render galleries");
  fudiGallery.render();
  qiongtaiGallery.render();
  wugongciGallery.render();
  lakeTempleGallery.render();
  tianningGallery.render();
  haidianGallery.render();

</script>