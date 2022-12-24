+++
title = "Hidden Tethering App"
description = "Sneaking a tethering app into the iPhone App Store (2012)"
date = 2022-03-24
categories = [
    "Developer"
]
tags = [
    "iOS",
    "dev"
]
image = "question-unsplash.jpg"
+++

> _In early 2012, I released an application that secretly contained tethering functionality._
>
> _The application reached the #2 paid app position in the App Store and made over $20,000 before being removed._
>
> _Here's the story._

#### The Idea

One day in December of 2011, a headline popped up on a news site about an iPhone application that reached the top paid App Store position in a little under two hours.

According to the article, there were only three others like it in the existence of the App Store; with all three having reached the top one or two position in a similar amount of time.

What surprised me most wasn’t that the application reached the top paid position in under two hours, it was that only three applications had ever attempted such a feat.

If each of these apps could reach the top position in so little time, then why hadn’t anyone else attempted it? The reason, as you might have guessed, is because it violates the Apple developer agreement.

All three of the applications contained the same feature: Tethering.

Tethering is a feature that enables you to share the network connection from your mobile device to your laptop or desktop computer. Tethering is barred from the iOS App Store. The reasons why aren't 100% clear, but, in Apple’s own words, are due to “causing excessive or unduly burden on a carrier’s network” – in other words, carriers lose money.

Although Apple strictly forbids tethering functionality on the App Store, many carriers now include it in their unlimited plans.  Back in 2012, tethering allowed users to skirt carrier fees and bypass extra costs associated with the feature on a mobile plan, which could help save a lot of money.

#### The Execution

I gathered as much information as I could about tethering and previous tethering applications.

In total, I found that there had actually been 5 public iPhone applications that contained tethering capabilities. Only two of those applications were sanctioned by Apple with the intent of being sold openly as tethering applications: NetShare and iTether. (iTether being the only fully-fledged application that also had a desktop application to help users connect.)

The remaining three applications that snuck in were a mix match of utility applications, with varying degrees of functionality:

* Handy Light - a simple flashlight
* QuasiDisk - a file manager
* Payupsucker – a note taker

These applications utilized either a proxy, or in the case of iTether, a reverse SSH tunnel.  In researching, there are many ways to tether a network connection.  In no particular order, you could:

* Utilize a SOCKS proxy
* Develop a mobile hotspot solution over Wi-Fi or Bluetooth
* Reverse SSH tunnel over USB

Any developer can create an application with tethering functionality. In fact, there were two open-source iPhone applications available in 2011: "iPhone-SOCKS-proxy" and "Tabi".

Inspired by "iPhone-SOCKS-proxy", I put all of my other projects on hold and set out to create a tethering application. In two days, I crafted a very basic SOCKS proxy tethering application. I plugged in my iPhone to test the application and to my surprise it actually worked!

#### iRandomizer Numbers

Thus, the application "iRandomizer Numbers".

![iRandomizer Numbers icon](irandomizer-icon.png)

iRandomizer Numbers cost a whopping **$4.99**. Quite a bit for a simple utility application.

![iRandomizer screenshot](irandomizer-device.png)

To be safe, the tethering feature was hidden behind a self-contained password in the application input.

![iRandomizer secret code](irandomizer-screenshot.png)

> Another dreadful fart app in the world of “pull my finger”.

![iRandomizer tethering functionality](tethering-device.png)

Within a week, even with the same name, icon, and functionality as my free application "iRandomizer", iRandomizer Numbers was accepted into the App Store.

About a week after the release, the feature leaked onto a public forum. From there, the word spread like wildfire.

A little over a week after the initial leak, a reporter called asking for a statement. I admitted that the app contained the feature and explained that I planned to let it stay up until Apple removed it. The story released later that evening and application sales took off.

iRandomizer Numbers skyrocketed to the top #40 paid application spot, rapidly surpassing other top applications and finally getting to the #2 Paid position in the App Store. Downloads were up from 0 sales a day to 40, 100, and into the thousands.

#### Removed from sale

After **over 5,000 purchases in one day totaling over $20k**, iRandomizer Numbers was officially removed by Apple.

#### Aftermath

The following week, I received a phone call from a member of the App Store Review Team.

The employee expressed extreme displeasure about the application. I was told, in no uncertain terms, that I would be lucky to keep my developer license and that additional app reviews would be given increased scrutiny. The reasons the application was pulled included:

* Excessive bandwidth usage
* Hidden features

That’s the story of iRandomizer Numbers.
