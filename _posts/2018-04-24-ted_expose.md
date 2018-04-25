---
layout: post
title: "ted_expose than you think"
description: interesting idea about data privacy
image: 'https://github.com/hbkimhbkim/hbkimhbkim.github.io/blob/master/_images/facebook_privacy.jpg?raw=true'
category: 'blog'
twitter_text: abc
introduction: defg
---

# How little we know about How much others know

![facebook_privacy](https://github.com/hbkimhbkim/hbkimhbkim.github.io/blob/master/_images/facebook_privacy.jpg)

## Facebook Scandal
------
<p>
  <strong>'I always looked at it as a relatively pastime'</strong>
</p>

<p>
When using Facebook, the majority of people read and press ' Like ' for fun. <br>
Very few people use social-media in deep consideration of how their digital traces will be processed and used by companies. However, after Facebook scandal, users will have a concerns to whether they shared <br>
information that may have been used to target specific ads.
</p>

## It's not a new story
------
 <p>
 It is not a new story that the social media, including Facebook, use private data for marketing. <br>
 There are many people already have warned of the data privacy. Following the video, from ted lecture, is a typical example. <br>
 </p>

<p>
https://www.youtube.com/watch?v=hgWie9dnssU

</p>

<p>
According to the video, the most important indicator that predicts high intelligence is 'liking a page for curly fries.<br>
This ridiculous result can be explained by the term 'homophily' from a sociological theory.<br>
In short, people are friends with people like them. So if you're smart, you tend to be friends with smart people, and if you're young, you tend to be friends with young people, and this is well established for hundreds of years.  So, if smart people liked it, then their friends saw it, and it spread to smart people group. It propagated through the network to a host of smart people. By the end, the action of liking the curly fries page is indicative of high intelligence, not because of the content, but because the actual action of liking reflects back the common attributes of other people who have done it.<br>

## More details about the article
------

<p>
Let's take a closer look at the paper she mentioned in the video('Private traits and attributes are predictable from digital records of human behavior'). The design of the study is presented above the image. <br>

They selected traits and attributes that reveal how accurate and potentially intrusive such a predictive analysis can be, including “sexual orientation,” “ethnic origin,” “political views,” “religion,” “personality,” “intelligence,” etc. And basic demographic attributes such as “age,” “gender,” “relationship status,” and “size and density of the friendship network.” Five Factor Model (9) personality scores (n = 54,373) were established using the International Personality Item Pool (IPIP) questionnaire with 20 items (25). Intelligence (n = 1,350) was measured using Raven’s Standard Progressive Matrices (SPM) (26). Age (n = 52,700; average, μ = 25.6; SD = 10), gender (n = 57,505; 62% female), relationship status (“single”/“in relationship”; n = 46,027; 49% single), political views (“Liberal”/“Conservative”; n = 9,752;
65% Liberal), religion (“Muslim”/“Christian”; n = 18,833; 90% Christian), and the Facebook social network information [n = 17,601; median size, ~X = 204; interquartile range (IQR), 206; median density, ~X = 0.03; IQR, 0.03] were obtained from users’ Facebook profiles.

![design1](https://github.com/hbkimhbkim/hbkimhbkim.github.io/blob/master/_images/design1.jpg)

<The study is based ona sample of 58,466 volunteers fromtheUnited States, obtained throughthemyPersonality Facebook application (www.mypersonality.org/wiki), which included their Facebook profile information, a list of their Likes (n = 170 Likes per person on average), psychometric test scores, and survey information. Users and their Likes were represented as a sparse user–Like matrix, the entries ofwhich were set to 1 if there existed an association between a user and a Like and 0 otherwise. The dimensionality of the user–Like matrix was reduced using singular-value decomposition (SVD) (24). Numeric variables such as age or intelligence were predicted using a linear regression model, whereas dichotomous variables such as gender or sexual orientation were predicted using logistic regression. In both cases,weapplied 10-fold cross-validation and used the k =100 top SVDcomponents. For sexual orientation, parents’ relationship status, and drug consumption only k = 30 top SVD components were used because of the smaller number of users for which this information was available.> </br>

The results are presented in two ways depending on the type of dependent variables, binary or numeric.

Prediction of Dichotomous Variables. The prediction accuracy of dichotomous variables expressed in terms of the area under the receiver-operating characteristic curve (AUC), which is equivalent to the probability of correctly classifying two randomly selected users one from each class (e.g., male and female). The highest accuracy was achieved for ethnic origin and gender.

Prediction of Numeric Variables. The accuracy of predicting numeric variables as expressed by the Pearson product–moment correlation coefficient between the actual and predicted values. The highest correlation was obtained for age (r = 0.75), followed by density (r = 0.52) and size (r = 0.47) of the Facebook friendship network. Closely following were the personality traits of “Openness” (r = 0.43), “Extraversion” (r = 0.40), and “Intelligence” (r = 0.39).

On the other hand, the predictability of individual attributes from digital records of behavior may have considerable negative implications, because it can easily be applied to large numbers of people without obtaining their individual consent and without them noticing. Commercial companies, governmental institutions,
or even one’s Facebook friends could use software to infer attributes such as intelligence, sexual orientation, or political views that an individual may not have intended to share.

There is a risk that the growing awareness of digital exposure may negatively affect people’s experience of digital technologies, decrease their trust in online services, or even completely deter them from using digital technology. It is our hope, however, that the trust and goodwill among parties interacting in the digital environment can be maintained by providing users with transparency and control over their information, leading to an individually controlled balance between the promises and perils of the Digital Age.

## Even if you decide not to publish it, they already know
------

<p>
According to an article, when we started writing something and then changed our minds not to post on Facebook, <br>
unfortunately the code in our browser that powers Facebook still knows what you typed. <br>
In Facebook’s Data Use Policy, under a section called "Information we receive and how it is used," it’s made clear that the company collects information you choose to share or when you "view or otherwise interact with things.” <br>

Typing and deleting text in a box could be considered a type of interaction, but I think very few of us would expect that data to be saved. <br>

## Predict personal things
------

<p>
Many data scientist have developed algorithms which can quite accurately predict things like your political preference, your personality score, gender, sexual orientation, religion, age, intelligence, along with things like how much you trust the people you know and how strong those relationships are. With the development of algorithms, the rate of prediction is increasing.
</P>

<p>
Take language analysis, a really powerful tool where we look at the kinds of words that you use — not even necessarily obvious things like curse words, but things like function words: how often you use “I” versus “we,” how often you use “the” versus “a,” these little words that are natural in the way that you develop language and inherent to your personality. It turns out that those reveal all sorts of personal traits. There’s a whole field of psycholinguistics in which people are doing deeper research into comparing the kinds of words you use and how often you use them with personal attributes, and that’s not something you can understand or control.
</P>

<em> References
http://www.slate.com/articles/technology/future_tense/2013/12/facebook_self_censorship_what_happens_to_the_posts_you_don_t_publish.html
http://www.slate.com/articles/technology/future_tense/2014/01/facebook_cleansing_how_to_delete_all_of_your_account_activity.html
https://www.ted.com/talks/jennifer_golbeck_the_curly_fry_conundrum_why_social_media_likes_say_more_than_you_might_think </em>
