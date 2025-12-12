---
title: "The Price of Progress - The Revenue Impact of Google Deprecating Placements and GAM Resellers"
---

# The Price of Progress - The Revenue Impact of Google Deprecating Placements and GAM Resellers

# The Price of Progress - The Revenue Impact of Google Deprecating Placements and GAM Resellers

* ![Writer: Felix Braberg]()

  Felix Braberg
* Aug 1, 2023
* 3 min read

![ree](https://static.wixstatic.com/media/105e8c_d82b360924924be3beaaa777ce6a9e1f~mv2.jpg/v1/fill/w_147,h_98,al_c,q_80,usm_0.66_1.00_0.01,blur_2,enc_avif,quality_auto/105e8c_d82b360924924be3beaaa777ce6a9e1f~mv2.jpg)

Google's [announcement](https://support.google.com/admob/answer/13543848?hl=en#:~:text=Google%20Ads%20recently%20announced%20that,for%20some%20multi%2Dcall%20requests.) that they will move to real time bidding and deprecate placements on third party mediation platforms on 31st of October 2023 was widely perceived in the mobile community as a good thing. Bidding would mean less technical overhead for publishers, and in theory generate the same revenues. However, it was not long before the mood was dampened by rumours that on the same date, Google would also cut [AdX demand for Google Ad Manager](https://www.felixbraberg.com/post/the-end-of-gam-networks-on-mobile) resellers on mobile. This would essentially end the most profitable ad monetization hack of the last 3 years, and cause publishers to earn less ad revenue. How much less? I've been running tests for the last few weeks to find that out. Here are the results that I saw from running a normal ad stack without Admob Placements and GAM resellers.

**What is the eCPM Impact of losing GAM and Admob placements?**

They say that a picture paints a thousand words. The graph below shows average global Android banner eCPM for a large mobile gaming title. GAM and Admob placements were switched off on the 23rd of July.

![ree](https://static.wixstatic.com/media/105e8c_d3a6abd1f0c844d2aca643f96b02db4a~mv2.png/v1/fill/w_59,h_32,al_c,q_85,usm_0.66_1.00_0.01,blur_2,enc_avif,quality_auto/105e8c_d3a6abd1f0c844d2aca643f96b02db4a~mv2.png)

Over the 8 days where GAM and Admob placements were paused and only Google Bidding was running, Android Banner eCPMs decreased by 26%. Banners, which has long been Google's speciality was the worst impacted with Interstitial and Rewarded Video eCPM also taking a hit, although not as much.

![ree](https://static.wixstatic.com/media/105e8c_c9139b00ac454e27a0018deb52a84b2e~mv2.png/v1/fill/w_65,h_64,al_c,q_85,usm_0.66_1.00_0.01,blur_2,enc_avif,quality_auto/105e8c_c9139b00ac454e27a0018deb52a84b2e~mv2.png)

As you can see all ad units are negatively impacted across both iOS and Android.

**What is the AdARPDAU Impact of losing GAM and Admob placements?**

Showing off eCPM is fine and all, but what anyone with a little Ad Monetization experience will tell you is that showing eCPM figures is only half of the story. We care first and foremost about ad revenue, which is eCPM plus fill rate. In theory, a publisher would gladly take less eCPM for more fill rate as this could also increase ad revenue. The best way to measure the true impact is to look ad Ad ARPDAU (Ad Revenue Per Daily Active User) as this takes UA fluctuations of a mobile title into account. So what do the Ad ARPDAU numbers say?

![ree](https://static.wixstatic.com/media/105e8c_a2509c79a49f427185fa4eddefe90027~mv2.png/v1/fill/w_70,h_66,al_c,q_85,usm_0.66_1.00_0.01,blur_2,enc_avif,quality_auto/105e8c_a2509c79a49f427185fa4eddefe90027~mv2.png)

The Ad ARPDAU numbers also look overwhelming negative specially on Banners and Rewarded video. Overall if you're looking for a headline number its safe to say that if you switched off Admob placements and GAM resellers today you as a publisher would earn *anywhere between 7-17% less ad revenue as seen on the graph below*.

![ree](https://static.wixstatic.com/media/105e8c_f0103287521e4a76975d1504ccd888c6~mv2.png/v1/fill/w_50,h_29,al_c,q_85,usm_0.66_1.00_0.01,blur_2,enc_avif,quality_auto/105e8c_f0103287521e4a76975d1504ccd888c6~mv2.png)

**What will really happen on the 31st of October?**

On the 31st of October, Google will force the settings that I created in the tests above on all mobile publishers world-wide. The major caveat is what will happen to the AdX demand that publishers have access too right now via GAM resellers? Most likely it was deprecated to fold it into Google bidding's demand stream to bolster it's performance. Thus, we should expect the revenue delta to close somewhat. However, we cannot expect the revenue gap to close completely, as in the current mediation setup we had that AdX demand competing against Admob as a stand alone network, which has pushed up the ad revenue immensely.

**What can mobile Publishers do to avoid the revenue loss?**

The depreciation of AdX demand and Admob placements on mobile symbolises the closing of a monetization hack that has been very profitable for the years. When one door closes another one opens. There's plenty of things that publishers can do to avoid the revenue loss by adding specific new ad partners. I'm currently testing new things with my clients that are showing promise. If you're curious to learn more please reach out to me and I'd be happy to have a chat.

Want more ad monetization news? Sign up to my newsletter [here](https://www.felixbraberg.com/) or subscribe to the [2.5 Gamers podcast](https://www.youtube.com/watch?v=QUVvO9hjSj8&t=439s&ab_channel=two%26ahalfgamers) for all the latest UA, Game design and Ad Monetization news!