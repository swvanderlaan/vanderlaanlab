---
title: A story about ExpressScan
date: 2022-01-13T14:44:32.839Z
draft: false
featured: true
authors:
  - admin
tags:
  - ExpressScan
  - slideToolKit
  - histology
  - glycophorin
  - WSI
projects:
  - high-throughput-imaging
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
Glad this #preprint <https://bit.ly/ExpressScan> by stellar 💫 MD-PhD [Joost Mekke](https://twitter.com/JMekke) on the #ExpressScan in the [AtheroExpress](http://www.atheroexpress.nl/) from the strategic [Circulatory Health](https://www.linkedin.com/in/circulatory-health-umc-utrecht-2a25171aa) theme is finally out. 

It's been a long and winding road. Here's the story👇🏽.

### First a little background

Cardiovascular diseases #CVD are the leading cause of death in the world; [check out](https://bit.ly/3m9Uz3g) this great graphic 👇🏽 - that sums it up nicely. #Atherosclerosis is the primary underlying mechanism of #CVD leading to #plaque formation in the arteries. 

*
*
*
*
*

Add alt text![https://bit.ly/3m9Uz3g](https://media-exp1.licdn.com/dms/image/C4E12AQErsrN6zOSNVg/article-inline_image-shrink_1000_1488/0/1629710052587?e=1647475200&v=beta&t=9I8jGtCLrq70gP9-Ts3hWETaP-3nE01MQU-SJzISJyQ)

### Athero-Express

Since [2002](https://doi.org/10.1007/s10564-004-2304-6) we have collected over 3,600 #plaques in the #AtheroExpress. We paraffin-embed, cut, and stain these #plaques for commonly present cells and structures ('phenotypes'), and manually study #plaques through #microscopy 🔬

*
*
*
*
*

Add alt text[![No alt text provided for this image](https://media-exp1.licdn.com/dms/image/C4E12AQEKxYXXXmbToA/article-inline_image-shrink_1500_2232/0/1629710217847?e=1647475200&v=beta&t=dYp0Bl_MvCNszXrVayjgoehz2vMT-8fOHjdhx4PgP64)](http://doi.org/10.1007/s10564-004-2304-6)

In 2010 we [found](https://doi.org/10.1161/CIRCULATIONAHA.109.887497) that intraplaque hemorrhage #IPH associates with secondary outcome after carotid endarterectomy #CEA👇🏽.

*
*
*
*
*

Add alt text[![No alt text provided for this image](https://media-exp1.licdn.com/dms/image/C4E12AQGVU-tkN2J1uw/article-inline_image-shrink_1000_1488/0/1629710231462?e=1647475200&v=beta&t=f2w0Dq3qnH9OlA106VTWgqK-8jIHRsIUlAFONuWoH9Q)](http://doi.org/10.1161/CIRCULATIONAHA.109.887497)



In 2013 we [found](https://doi.org/10.1161/STROKEAHA.113.002633) that \[#sex / #gender] associates with #IPH and modulates the association with secondary outcome after #CEA, more in men ♂ than women ♀👇🏽. This work was led by Joyce Vrijenhoek and @Hester den Ruijter and marked the start of research into sex differences in CVD at the UMC Utrecht.

*
*
*
*
*

Add alt text[![No alt text provided for this image](https://media-exp1.licdn.com/dms/image/C4E12AQGFFuDhx79Rew/article-inline_image-shrink_1000_1488/0/1629710187503?e=1647475200&v=beta&t=HBuNGM7o_eUTZ9szmRhXG3CCHu2HFlZOFy8CLmq5Ggk)](http://doi.org/10.1161/STROKEAHA.113.002633)



### ExpressScan

But manual analysis is cumbersome 😣😓😮💨. So back in 2014 💫 \[MD/coder] Bas Nelissen created #slideToolKit: a collection of scripts that enable fast, reproducible, and automated processing of high-throughput whole-slide images #WSI for analysis with [CellProfiler](https://cellprofiler.org/). You can find the GitHub here <https://github.com/swvanderlaan/slideToolKit> and be sure to read the [original paper in PLoS One](https://doi.org/10.1371/journal.pone.0110289).

*
*
*
*
*

Add alt text![slideToolKit: a collection of scripts to enable fast, reproducible, and automated processing of whole-slide images. ](https://media-exp1.licdn.com/dms/image/C4E12AQFWpty5sM5H9g/article-inline_image-shrink_1000_1488/0/1629710289483?e=1647475200&v=beta&t=fS3f7t93ocen6qROfII-mJRcJmX3NwWgT6OHwbrvpm8)

Since then we have been crawling through all the slide cabinets 🤪, cleaned the slides🧼🧽, and used #pathology scanners to obtain over 25,000 high-resolution #WSI for all #plaques. This totals up to about 20Tb 😬. A hell of a job involving multiple people, microscopic lamps breaking down, and pathology scanners from #Roche and #Hamamatsu.

"Oh, but Sander, what does it look like 🧐?", you might wonder. Here's an example, this sample was stained for CD68 a protein that is expressed by macrophages (left), and ACTA2 which is expressed by smooth muscle cells (right).

*
*
*
*
*

Add alt text![No alt text provided for this image](https://media-exp1.licdn.com/dms/image/C4E12AQG83BdD0R2R2A/article-inline_image-shrink_1000_1488/0/1629710597770?e=1647475200&v=beta&t=uL-qbdPLXhnIl1A72nUObNIoxZYwoiN_ZZcM8LFggV4)

Fast forward to 2021. Glycophorin C #GLYCC is a [glycoprotein](https://en.wikipedia.org/wiki/Glycophorin_C) found on the membrane of red blood cells and a presumed marker of the degree of #IPH. We quantified #GLYCC using #slideToolKit and CellProfiler, and investigated the relation of #GLYCC and six other markers with symptoms and secondary outcome.

*
*
*
*
*

Add alt text![No alt text provided for this image](https://media-exp1.licdn.com/dms/image/C4E12AQGhhFKoHsNxMw/article-inline_image-shrink_1000_1488/0/1629711150325?e=1647475200&v=beta&t=q9joBTfbJlijNE5JVrf10zstcE7yfhOKdjZfIbqREj4)

Here are the 3️⃣ main findings 👇🏽

1️⃣The total area of positive #GLYCC stain was larger in individuals with manually scored #IPH, and more so in men ♂ than women ♀. 

*
*
*
*
*

Add alt text![No alt text provided for this image](https://media-exp1.licdn.com/dms/image/C4E12AQH2B761dOB1ZA/article-inline_image-shrink_1000_1488/0/1629711782314?e=1647475200&v=beta&t=q4aQe9InPZz7gLnrQdsUqK4s5mbckBHVpEylDtf6jjU)

2️⃣As #IPH is one of the causes of #plaque rupture, we assessed the correlation of #GLYCC with symptoms prior to #CEA (upper graph, below).

3️⃣#GLYCC associates with secondary #MACE after #CEA (lower graph, below).

*
*
*
*
*

Add alt text![No alt text provided for this image](https://media-exp1.licdn.com/dms/image/C4E12AQGBJ1WjSYdUzg/article-inline_image-shrink_1000_1488/0/1629711828758?e=1647475200&v=beta&t=jfNrvxU2_g90Klz1quNprkT-cE2Thvg7pVL11qXV4SQ)

### The future is bright

But, for me this 7 year story does not end with the current #preprint on #GLYCC in #plaques. Here's why  👇🏽

☝🏽Automated, high-throughput quantification of #WSI is easy with #slideToolKit; it takes less than a day to analyse all #WSI 👊🏽.

✌🏽#WSI quantification opens up a whole range of new analyses 🧐🔬🧑🏽🔬👨🏻🔬👩🏼🔬🥼🧫.

Some ideas💡we are working on:

💡 genotype-phenotype analyses 👉🏽 another 💫 PhD Kai Cui is working on this, stay tuned for her presentation at the #eshg2021 😀.

💡 discovery of clinically relevant features in #WSI through #machinelearning 👉🏽 the ✨PhD Yipei Song is working with me and @clintomics to finish #CONVOCALS and #DEEPENIGMA.

💡 In the spirit of #OpenScience #ExpressScan should be #OpenAccess. That's easier said than done. First step is to open it up to the wider @CirculatHealth community. So watch this space for more.

### Finally

It's been a long time coming, with a lot of hurdles 🙈🙉🙊to overcome, but I am very happy with this first milestone of #ExpressScan 🤩🥳. The #preprint is open for #MOPR 👉🏽 https://bit.ly/ExpressScan and the codes 💻are 👉🏽https://bit.ly/ExpressScanCode.

A big thank you 🤗 to all the co-authors (in no particular order) Clint Miller, Gerard Pasterkamp, Hester den Ruijter, Michal Mokry, Tim Sakkers, Yipei Song, Noortje van den Dungen, Dominique de Kleijn, Maarten Verwer, Gert Jan de Borst. A special thank you 🙇🏽should go to Saskia Haitjema and Joost Mekke for pulling this off and co-leading this part of the project! And of course we owe a debt of gratitude 🙏🏽 to all those that worked on #ExpressScan in the past: Bas Nelissen (#ExpressScan would not have been possible without his work), Joyce Vrijenhoek, Marijke Linschoten, Tim van de Kerkhof, Robin Reijers, Tim Bezemer, Sander Reukema, Joelle van Bennekom, and many more. Lastly, we should acknowledge and be grateful to the hundreds of patients willing to participate in the #AtheroExpress, without their support and altruism there is no scientific progress.