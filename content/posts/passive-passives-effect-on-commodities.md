---
title: Massive Passives Effect on Commodities
date: 2021-08-08T21:16:24+08:00
lastmod: 2021-08-08T21:16:24+08:00
author: Derek Wong
# avatar: /img/author.jpg
# authorlink: https://author.site
cover: /posts/covers/pexels-mark-stebnicki-2749165.jpg
# images:
#   - /img/cover.jpg
categories:
  - "MarketResearch"
tags:
  - "Commodities"
  - "Passive"
# nolastmod: true
draft: False
---

**Introduction:** "Massive Passive” has heavily influenced the equities sector, completely changing the dynamics of the stock market and the make-up of its participants. Now more people are getting exposure to commodities via long-only indexes and swap products. I am taking Irwin and Sanders's paper *[The Impact of Index and Swap Funds on Commodity Futures Markets](https://www.oecd-ilibrary.org/docserver/5kmd40wl1t5f-en.pdf?expires=1628413452&id=id&accname=guest&checksum=3B53FAD94ECD6D2C200D23AD34C0FA5E)* and extending it.

<!--more-->

First, I am using more recent data as the Irwin study was done in 2010. I include precious metals that were not included in the original study. Third, I will examine the changes in the return distribution, volatility, and autocorrelation.

## The current state of passive commodity funds

Let us examine the current market situation concerning inflows of AUM into passive funds. I will select the iShares S&P GSCI Commodity Index ETF ticker *GSG* as an example. It is a representative fund and has a long history as well as a well-known index underlying.

[![img](https://cdn.substack.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F64dcbb75-2525-47d5-89b2-d340f2b4a2bd_983x525.png)](https://cdn.substack.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F64dcbb75-2525-47d5-89b2-d340f2b4a2bd_983x525.png)

A major difference here we can see is that the Total Fund Assets are cyclical and not monotonic like in large-cap equity indices. This may lead to a different dynamic. Although a slight lead time decrease in TFA seems to lead to downturns, that is just a visual inspection and contains no backing. However, we can see the peak in 2011, and the AUM rose from 2006 until then. The OECD commissioned the original study during that time as AUM was increasing.

This increased participation of index funds and swaps has significantly changed the landscape. I felt that an understanding of their effect and the different levels of TFA was not well understood. Some thinking by analogy to the equities markets could lead us astray. Which in this case, I think it already has as the nature of the TFA is cyclical.

It is also important to note that storable commodities are convex. Here is a graphic from the Irwin et al. paper that describes this. This means that the dynamic heavily influences these index funds, as we saw with Crude oil in 2020. 

[![img](https://cdn.substack.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2Fc0b6c15d-aca2-4ef9-bd96-e35ca733f236_626x498.png)](https://cdn.substack.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2Fc0b6c15d-aca2-4ef9-bd96-e35ca733f236_626x498.png)

But I digress.

## Data 

For the process of this research, I used data from the Disaggregated Commitment of Traders Report on US  futures, as they have the most detailed and historically long data set. We start in 06-2006 and end 08-2021 for 791 weekly samples across 14 markets (Rbob Gasoline, Crude oil, Natural Gas, Coffee, Copper, Sugar, Gold, Wheat, Corn, Soymeal, Soybeans, KC Wheat, Cocao, and Feeder Cattle). I use daily data for the futures listed using the front-month contract rolling on a back adjusted basis for the last price. 

We infer index or passive investment using information discussed in a CFTC 2008 September report stating that swap dealers’ positions in agricultural markets mirror index trader positions reasonably. This is weaker for energy markets representing only 41% of long swap dealer positions in 2007-2008. However, I include these markets as we have no other way to proxy. There has been no official update on the statistics since then that I could find. Hence we measure the Long Swap positions of all of the futures contracts to measure the index / passive participation in that futures contract.

## Measuring the influence of index and swaps on future’s returns

I have selected 3 representative commodities: wheat, crude oil, and copper. We can see that the low amount of participation of indexes in the overall Long Swap(“Index Participation”) leads to a weak if no relationship. While agriculture is represented by wheat which was stated to have a strong relationship in the CTFC statement, however, post-2012, the relationship seems to be high. Copper stands in the middle where it may have some relationship, but it is clear. Bearing out the numbers using correlation coefficient, Wheat is 0.39, Crude Oil -0.06, and Copper at 0.07. 

[![img](https://cdn.substack.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2Fd1d9664f-803e-4d21-af8c-08e4ad80fe56_983x525.png)](https://cdn.substack.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2Fd1d9664f-803e-4d21-af8c-08e4ad80fe56_983x525.png)

[![img](https://cdn.substack.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F3528c8cd-dfed-435f-a5b6-5f34a74c54f4_983x525.png)](https://cdn.substack.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F3528c8cd-dfed-435f-a5b6-5f34a74c54f4_983x525.png)



[![img](https://cdn.substack.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2Fa9105d0d-ba56-4c24-8eb2-ee356d30f888_983x525.png)](https://cdn.substack.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2Fa9105d0d-ba56-4c24-8eb2-ee356d30f888_983x525.png)

## Index participation in relation to returns

I find no evidence that in relation to returns, index participation has any relationship. Let us look at wheat again, but instead of inspecting price, we look at returns.



[![img](https://cdn.substack.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F82379158-7d42-404c-ade4-5a74e1af271a_983x525.png)](https://cdn.substack.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F82379158-7d42-404c-ade4-5a74e1af271a_983x525.png)

We can see even in one of the most correlated categories on price, in returns space, the result is basically 0 slope and 0 $R^2$. I plot the rest below.

[![img](https://cdn.substack.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2Fda2d1ad8-5789-4bd5-b247-72fc8701fd71_1000x2000.png)](https://cdn.substack.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2Fda2d1ad8-5789-4bd5-b247-72fc8701fd71_1000x2000.png)



[![img](https://cdn.substack.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F8912390a-6118-4cbb-98d1-bc3c645856f4_251x396.png)](https://cdn.substack.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F8912390a-6118-4cbb-98d1-bc3c645856f4_251x396.png)

Here is have summarized the $R^2$ and Slope of each of the contemporaneous linear regressions. We can see that there are no significant $R^2$ or Slopes different from 0. **From this, I can say that long swaps, a.k.a index participation, do not affect contemporaneous returns for any major commodity future.**

## Does the level of long swaps affect the return distribution or volatility?

Here I create quartiles (divide the data into 4ths with the lowest being 1 and the highest being 4) in relation to the long swap positions. I then analyze the percent returns for each quartile and then do a quartile spread(4th quartile - 1st quartile). This helps determine any significant changes in the returns distribution based on how much or how little index participation there is. I will go through each of the measures and add my thoughts.



**Skew**

[![img](https://cdn.substack.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F417f5111-b44b-4be2-858b-601fe25b2863_992x188.png)](https://cdn.substack.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F417f5111-b44b-4be2-858b-601fe25b2863_992x188.png)

[![img](https://cdn.substack.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F87ded378-9d52-4e85-9414-903f47abc049_983x525.png)](https://cdn.substack.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F87ded378-9d52-4e85-9414-903f47abc049_983x525.png)

The difference between RBOB gasoline and Crude oil is what stands out to me. One increases negative skewness while the other positive. I do not have an economical answer for that. It could just be an interesting anomaly. **I would say it is just noise.**



**Kurtosis**

[![img](https://cdn.substack.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F9f1c8cd4-4d0f-482d-a777-f1f3b7922f66_999x191.png)](https://cdn.substack.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F9f1c8cd4-4d0f-482d-a777-f1f3b7922f66_999x191.png)

[![img](https://cdn.substack.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F75907042-d169-44aa-820b-dadae65144b1_983x525.png)](https://cdn.substack.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F75907042-d169-44aa-820b-dadae65144b1_983x525.png)

Crude oil stands out again with a Q1 kurtosis of 64 and then dropping slightly negative in Q4. Also, again, RBOB does exactly the opposite, starting at 0 in Q1 then becoming very leptokurtic at 7.7. Another almost 0 result is in Cocao, with kurtosis of 0.01 in the fourth quartile. **A majority of the distributions are becoming more leptokurtic, which implies that this action affects the distribution's tails,** although most of the underlying distributions were already positive. 



**Mean % Returns**

[![img](https://cdn.substack.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F09b6085d-87b6-457f-8f44-0555eb13b195_984x204.png)](https://cdn.substack.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F09b6085d-87b6-457f-8f44-0555eb13b195_984x204.png)

[![img](https://cdn.substack.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2Fcae83944-335a-4f9e-b82c-32b7b5f31319_983x525.png)](https://cdn.substack.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2Fcae83944-335a-4f9e-b82c-32b7b5f31319_983x525.png)

This chart is finally one that is telling. With a vast majority of the positive results and some with results at or above 1%, while the worse performer is Cocao at -0.40%. With participation from all sectors and the magnitude being significantly positive. **Index participation in commodities is adding a positive drift component that increases as more participation comes in.** 



**Annualized Volatility**

[![img](https://cdn.substack.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F7de8615b-4efa-4618-b2ba-99762f16e39a_994x206.png)](https://cdn.substack.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F7de8615b-4efa-4618-b2ba-99762f16e39a_994x206.png)

[![img](https://cdn.substack.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F2f2bb301-68ec-4616-af2a-6d2004abb8e5_983x525.png)](https://cdn.substack.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F2f2bb301-68ec-4616-af2a-6d2004abb8e5_983x525.png)

Similar to the returns chart, a majority of these are negative with larger downside magnitudes. **This shows that index participation generally reduces annualized volatility by 10% and sometimes more.** 



**Hurst Exponent**

[![img](https://cdn.substack.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F274c3d05-5f89-44e9-aeb8-ae448d311593_977x190.png)](https://cdn.substack.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F274c3d05-5f89-44e9-aeb8-ae448d311593_977x190.png)



[![img](https://cdn.substack.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2Fa13cf49e-bb12-4be9-97a2-22c8311907e3_983x525.png)](https://cdn.substack.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2Fa13cf49e-bb12-4be9-97a2-22c8311907e3_983x525.png)

This statistic bears a bit of explanation. The Hurst exponent is used to measure the long-term memory of a time series. Simply put, it is a measure of *autocorrelation. It* quantifies if a time series tends to revert to the mean or cluster in a single direction. Suppose the value is < 0.50 it is ‘mean-reverting,’ and >0.50. It is persistent or ‘trending’ with 0.50 being a perfect random walk. The Hurst exponent is not without its issues and does not perfectly measure mean reversion/trending, but it is a good measurement for our purposes. Here we measure the value with a lookback of 100 days.

Back to the findings. For most of the quartiles, most of the commodities spend their time above 0.50, which means they are persistent or ‘trending’ most of the time. **The agriculture complex benefits significantly for additional ‘trending’ from index participation, while the energies and metals suffer.** 

<!-- Begin Mailchimp Signup Form -->
<link href="//cdn-images.mailchimp.com/embedcode/horizontal-slim-10_7.css" rel="stylesheet" type="text/css">
<style type="text/css">
	#mc_embed_signup{background:#fff; clear:left; font:14px Helvetica,Arial,sans-serif; width:100%;}
	/* Add your own Mailchimp form style overrides in your site stylesheet or in this style block.
	   We recommend moving this block and the preceding CSS link to the HEAD of your HTML file. */
</style>
<div id="mc_embed_signup">
<form action="https://dwongresearch.us5.list-manage.com/subscribe/post?u=142fa4a592b63e3b9722442ef&amp;id=6c4483a227" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
    <div id="mc_embed_signup_scroll">
	<label for="mce-EMAIL">Subscribe</label>
	<input type="email" value="" name="EMAIL" class="email" id="mce-EMAIL" placeholder="email address" required>
    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
    <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_142fa4a592b63e3b9722442ef_6c4483a227" tabindex="-1" value=""></div>
    <div class="clear"><input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button"></div>
    </div>
</form>
</div>
<!--End mc_embed_signup-->

## **Conclusion**

We have explored the effect of passive investing and index funds on US commodity futures. **We have found that, specifically in effect on returns, there is no relationship with negligible correlations with the price to long swap field in the disaggregated COT report.** In the passive flows affect the return distribution, the findings for its changing skewness or kurtosis were weak at best except for crude oil. However, the energy complex does have the least relationship with the long swap inventory, which could be another 3rd factor we are not seeing.

We did see a significant influence in a few key areas. First and intuitively, we see **positive mean returns with increasing passive fund flows**. Since most of the funds and ETFs are long-only, it makes sense they are bidding up the price of the underlying they need to hold to replicate the basket of index returns. Second, in most of the commodities, **increased index participation leads to lower volatilities**. This also can be traced back to the intuitive sense of long-only funds and their clients. Most will hold for long periods (potentially weeks to months), while our measurement period is a week. This adds significant liquidity to the market, slowing down high turnover gyrations, acting almost as a commercial in the commodities. Their direction is known, and they will always have a position. The question is just how much, which does not change drastically in short periods but slowly over time.  Finally, most commodities are above 0.50 Hurst exponent and persistent. **Agriculture commodities benefit from additional index participation as it increases their persistence**. 



cover image: Photo by **[Mark Stebnicki](https://www.pexels.com/@nc-farm-bureau-mark?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels)** from **[Pexels](https://www.pexels.com/photo/selective-focus-photo-of-plants-2749165/?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels)**

