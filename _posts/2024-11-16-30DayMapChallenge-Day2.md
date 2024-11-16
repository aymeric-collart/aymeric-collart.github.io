---
title: '#30DayMapChallenge, Day 2. Getting the data, Part 1: Who is fluent in Formosan languages?'
date: 2024-11-16
share: false
permalink: /posts/blog-30DayMapChallenge-Day2/
tags:
  - Taiwan indigenous languages
  - Data
  - 30DayMapChallenge
---

Day 2 of the <a href="https://bsky.app/hashtag/30DayMapChallenge" target = "_blank">#30DayMapChallenge</a>. I'm entering the preparatory phase: Figuring out what data are available to plot the maps. Since my main interest is about language, let's start with the crucial and orthodox question: What is the proportion of fluent speakers of indigenous languages in Taiwan?

<!--more-->
Anyone interested in Formosan languages knows that they are endangered. A quick chat with indigenous people or researchers will tell you that the most fluent speakers are the older ones. The question is to:<br>

General question: What is the number of speakers by language?
====

This question is not easy to answer, for the only reason that it's hard to define what a 'fluent speaker' is. The ideal way to do so would be to rely on standardized tests and to have everyone taking them... but as always, ideal situations face the reality of life!
<br><br>

First question: Who is fluent in Formosan languages?
====

Prof. Ai-yu Apay Tang (National Dong Hwa University) looked at this issue in Truku, using behavioral methods to provide psycholinguistic assessments (see her book published in 2021, <i>From diagnosis to remedial plan : a psycholinguistic assessment of language shift, intergenerational linguistic proficiency, and language planning in Truku</i>). Several groups of participants were involved depending on their age: (a) 10-15 years old, (b) 16-25 years old, (c) 26-40 years old, and (d) 41-65 years old. And the results are quite straightforward: The younger the participants, the less fluent they were in Truku. Coupled to the fact that generally they can speak Mandarin Chinese, the results reflect a shift in terms of dominance of L1: While the dominant L1 was still Truku for the group of oldest participants, this was not the case for the three other groups.
<br><br>
As always when dealing with Formosan languages, we shound never assume that what we observe in one language is generalizable to other languages. Do the results found for Truku also hold for other ones?
<br>
The Foundation for the Research and Development of Indigenous Languages (in Chinese: 原住民族語言研究發展基金會) has published a huge survey they conducted in 2020 (but only in Chinese, <a href="https://www.ilrdf.org.tw/basic/?node=10064" target = "_blank">here</a>), with responses from 480 people, covering 16 indigenous tribes (another bigger survey is on-going).
<br>
We can find the results to the question "what is your dominant L1" on pages 35-36.

<i>Table 1. Proportion of language dominance by age group</i>

| Dominant language | Indigenous language    | Mandarin Chinese    | Other |
| Age group         |                        |                     |       |
| :---:             | :---:                  | :---:               | :---: |
| Below 10          | 8.1%                   | 91.9%               | 0%    |
| 11-20             | 6.2%                   | 93.8%               | 0%    |
| 21-30             | 5%                     | 92.5%               | 2.5%  |
| 31-40             | 18.3%                  | 75%                 | 6.7%  |
| 41-50             | 43.4%                  | 53%                 | 3.6%  |
| 51-60             | 64.6%                  | 26.8%               | 8.6%  |
| Above 61          | 81.8%                  | 11.7%               | 6.5%  |

Again, the situation is quite clear, as one's own indegineous language is aslo your dominant L1 when you're older. But unlike the study by Ai-yu Apay Tang, we can see that this is the case for speakers older than 50 years old!
<br>
There are also differences depending on the ethnic group, as showed on page 37. But these data were aggregated over the age groups, so it's not easy to really interpret such differences.
<br><br>
We have now an answer to the first question, we can refine the general question: 

What is the number of (fluent) speakers of Formosan language <i>by</i> language?
====

This is a simple calculation, which is certainly wrong because it won't represent the reality on the field, and I'm completely ignoring differences between groups, the actual usage of the language in the everyday life, where they live (in metropolitan/urban areas or in the villages), etc.. But at least, we can have a first estimate:<br>

> Estimate number of (more or less) fluent speakers = n(51-60 years old) * 64.6% + n(above 61 years old) * 81.8%

The <i>Council of Indigenous Peoples</i> in Taiwan provides monthly statistics about the population number of indigenous people based on different factors (see <a href = "https://www.cip.gov.tw/zh-tw/news/data-list/940F9579765AC6A0/283F23E8500A85D2FF69791FDE74F1A9-info.html" target = "_blank">here</a> for the most recent one so far, September 2024). The problem is that <b>there is no statistical table for the population number in terms of ethnic group and age</b>! But we have other data, so let's see what we can do.
<br><br>
First, we have the total population number for each ethnic group, and according to whether they live in mountain areas (which is super crucial as you'll remark great differences between the groups!).

<i>Table 2. Population number for each ethnic group (according to their living area)</i>

|              | Non-mountain areas| Mountain areas | Total     | 
| :---:        | :---:             | :---:          | :---:     | 
| Total        |  283 595          |  324 349       | 607 944   | 
| Amis         |  225 254          |  1341          | 226 595   |  
| Atayal       |  1937             |  97 159        | 99 096    |  
| Paiwan       |  23 272           |  86 573        | 109 845   | 
| Bunun        |  353              |  63 001        | 63 354    | 
| Rukai        |  2 806            |  11 283        | 14 089    | 
| Puyuma       |  15 641           |  122           | 15 763    | 
| Tsou         |  16               |  6869          | 6885      | 
| Saisiyat     |  4813             |  2417          | 7230      | 
| Yami         |  12               |  4951          | 4963      | 
| Thao         |  910              |  6             | 916       | 
| Kavalan      |  1654             |  2             | 1656      | 
| Truku        |  165              |  35 117        | 35 282    |  
| Sakizaya     |  1118             |  2             | 1120      |
| Seediq       |  28               |  11 480        | 11 508    |
| Saaroa       |  3                |  485           | 488       |
| Kanakanavu   |  1                |  445           | 446       |
| Not declared |  5612             |  3098          | 8708      |

Second, we have the table of the repartition of the population accordind to their age and whether they live in mountain areas. I just give the numbers of interest here:

<i>Table 3. Population number and proportion based on the group of age (all ethnic groups aggregated)</i>

|                      | Non-mountain areas   | Mountain areas       | 
| :---:                | :---:                | :---:                | 
| Total                |  283 595  (100%)     |  324 349  (100%)     | 
| 0-50 years old       |  200 135  (70.57%)   |  243 936  (75.21%)   |  
| 51-60 years old      |  36 599   (12.91%)   |  38 772   (11.95%)   | 
| Above 61 years old   |  46 861   (16.52%)   |  41 641   (12.84%)   | 

What I can do now is just to assume (because I have no other choice so far) that this proportion is the same for each group, and we obtain the following table:

<i>Table 4. Estimate population number for each ethnic group (above 51 years old)</i>

|              | Non-mountain areas<br>51-60|Non-mountain areas<br>Above 60| Mountain areas<br>51-60|Mountain areas<br>Above 60|
| :---:        | :---:                      | :---:                        | :---:                  | :---:                    | 
| Total        |  36 612                    | 45 850                       | 38 760                 | 41 646                   |
| Amis         |  29 080                    | 37 212                       | 160                    | 172                      |
| Atayal       |  250                       | 320                          | 11 611                 | 12 475                   |  
| Paiwan       |  3004                      | 3845                         | 10 345                 | 11 116                   |
| Bunun        |  46                        | 58                           | 7529                   | 8089                     |
| Rukai        |  362                       | 464                          | 1348                   | 1449                     |
| Puyuma       |  2019                      | 2584                         | 15                     | 16                       |
| Tsou         |  2                         | 3                            | 821                    | 882                      |
| Saisiyat     |  621                       | 795                          | 289                    | 310                      |
| Yami         |  2                         | 2                            | 592                    | 636                      |
| Thao         |  117                       | 150                          | 1                      | 1                        |
| Kavalan      |  214                       | 273                          | 0                      | 0                        |
| Truku        |  21                        | 27                           | 4196                   | 4509                     |
| Sakizaya     |  144                       | 185                          | 0                      | 0                        |
| Seediq       |  4                         |  5                           | 1372                   | 1474                     |
| Saaroa       |  0                         |  0                           | 58                     | 62                       |
| Kanakanavu   |  0                         |  0                           | 53                     | 57                       |
| Not declared |  725                       |  927                         | 370                    | 398                      |


This table only shows the population number by age group, but we know based on Table 1 that their indigenous language may not be their dominant language. So we need to calculate one more time based on the proportion numbers described in Table 1. This gives us the 

<i>Table 5. Estimate population number whose dominant language is their indigenous language for each ethnic group</i>

|              | Non-mountain areas<br>51-60|Non-mountain areas<br>Above 60| Mountain areas<br>51-60|Mountain areas<br>Above 60| Total      |
| :---:        | :---:                      | :---:                        | :---:                  | :---:                    |  :---:     |
| Total        |  23 651                    | 38 323                       | 25 039                 | 34 067                   | 121 080    |
| Amis         |  18 786                    | 30 439                       | 104                    | 141                      | 49 470     |
| Atayal       |  162                       | 262                          | 7500                   | 10 205                   | 18 128     |
| Paiwan       |  1941                      | 3145                         | 6683                   | 9093                     | 20 862     |
| Bunun        |  29                        | 48                           | 4863                   | 6617                     | 11 558     |
| Rukai        |  234                       | 379                          | 871                    | 1185                     | 2669       |
| Puyuma       |  1304                      | 2114                         | 9                      | 13                       | 3440       |
| Tsou         |  1                         | 2                            | 530                    | 721                      | 1255       |
| Saisiyat     |  401                       | 650                          | 187                    | 254                      | 1492       |
| Yami         |  1                         | 2                            | 382                    | 520                      | 905        |
| Thao         |  76                        | 123                          | 0                      | 1                        | 200        |
| Kavalan      |  138                       | 224                          | 0                      | 0                        | 362        |
| Truku        |  14                        | 22                           | 2711                   | 3688                     | 6435       |
| Sakizaya     |  93                        | 151                          | 0                      | 0                        | 245        |
| Seediq       |  2                         |  4                           | 886                    | 1206                     | 2098       |
| Saaroa       |  0                         |  0                           | 37                     | 51                       | 89         |
| Kanakanavu   |  0                         |  0                           | 34                     | 47                       | 81         |
| Not declared |  468                       |  758                         | 239                    | 325                      | 1791       |

<br>

Final remarks
====

We have an answer to the question in this post. Overall, this means that less than 20% of the people of each ethnic group is dominant in their indigenous language.<br>
But there are many things I need to warn (also to myself!). This is the most optimistic situation as this only corresponds to the highest numbers on the scale. I wouldn't be surprised if the actual numbers are only half of what I report here, or even lower for the most endangered languages.
<br><br>
The reason is just that there are many factors that aren't taken into account in this estimation:<br>
- What does 'mountain' and 'non-mountain' areas mean? In particular, if 'non-mountain' areas cover very urban areas, such as Taipei city, New Taipei city, Taoyuan city or Kaohsiung city, then the situation is more than certainly worse! Unfortunately, the data weren't fine-grained enough in the reports we can find online.<br>
- I used the notion of 'L1 dominance', but we all agree that this should be seen as a scale. We can be dominant in the same language, this doesn't mean that we are equally competent.<br>
- Plus, it doesn't mean that the speakers are not compentent in a second language. The reality is that they are certainly bilingual, and interferences from the other language (mostly Mandarin Chinese or Taiwanese Southern Min, or even another Formosan language) can't be avoided.<br>
- It's also possible that the number of responses from the survey of L1 dominance was not representative enough. If that's the case, I'm looking forward to the results of the on-going survey!<br>
<br>
Overall, I believe that these numbers are helpful. We need a starting point. But they fail to reflect the dynamicity of these languages, and they erase individual differences and sociolinguistic phenomena we can observe on the field. So my take-home message is: <b><i>You can refer to this estimation, but with a lot, a lot, A LOT of caution!</i></b>