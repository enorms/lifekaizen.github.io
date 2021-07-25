---
layout: default
permalink: /writings/retirement
id: retirement
---

[draft]

# Why contribute to a retirement account?

Or specifically, _How do you convince a young person to contribute to a retirement account?_ was a question recently posed in our family call, where the person in question has a job that will match some amount of contribution to an IRA, which to the adults seemed like "free money" (which no sane person would turn down). I want to try to answer a bit more fully, but still quickly and back of the envelope-y, and also touch on why we even have to have such a conversation. First let's address the question, then the meta-question.

## I. Why take matching corporate funds and invest into a retirement account

There are a few ways in which it is useful to have assets in a retirement account, as early as possible:

- compound interest is helped with time and not withdrawing capital
- despite not having direct access - which helps with the compounding part - your (financial) net worth is still impacted (positively), and as money is fungible [^1] it can be used in other (what the industry likes to call taxable) accounts
- I would argue it makes filing taxes easier, since nothing in the retirement account triggers a reporting event (until decades later upon withdrawal). Usually, dividends or capital gains need to be reported. On the other hand, it might be more complicated later (when withdrawing), and if it's _not_ a Roth you may have to save paperwork tracking the cost basis
- there are some legal benefits where these assets tend not to be counted against you for things like student loan eligibility, and are also considered out of reach of bankruptcy or lawsuits, because it would not be humane to deprive an American of their retirement funds - though if they were not wealthy enough to have any well that's another story

The items other that first one are subjective and appeal to me, so let's dive into the first one only and assign some numbers. An unsophisticated return projection takes the starting capital, adds the annual return to get the value at the end of the first year, then does the same with this new number, and repeats as many times as there are years. So for example, if the person is `16`, plans to retire at `66`, and the annual return is `7%`, then the starting value is `$1` and the future is `($1 + ($1 x 7%))^(66-16)`, or `$1(1.07^50)`, which is `$29`. [^2] [^3] [^4] So to me, 1 turning into 29 is pretty amazing, and when I was younger it was mind-blowingly so. And so for me, that was the end of the story; I just wanted to see it happen, to test that it was really true, without really thinking about what it really meant to society or my value system.

And so if your company is matching your donation, they are essentially giving you $29 for every dollar you put in now, when you retire. Concretely, if you put in $2000 now you'll have 58,000 at retirement, and if they match you'll have double that. [^6]

One large caveat has to do with inflation. While $29 is the number of dollars in the future, $29 in 50 years is not worth $29 today. The easiest way to account for this is to take inflation out of the return, inflation is usually considered to be 3% long run - though lately has been more like 2% - so take the long run return of 7% and subtract 3% and call `4%` the post-inflation return. [^5] Then the return becomes `$7=$1(1.04^50)`. While not as impressive as $29, the implied meaning is something like taking $1 now and turning it into $7 also at now. [^7]

## II. Why does it matter

The short version is that I don't think it should, but the reality of the present US is that not having access to capital leaves one at the mercy of the government and sometimes that can be very painful. A recent example are the large delays in processing completely legitimate payment claims for things like unemployment, or implementing restrictions on late-rent evictions, etc. The US is not a great place to be if you do not have much wealth. If you plan to not have much wealth, there are much better places such as Canada, New Zealand, etc. [^8]

Why do you need the money at retirement? In case you get sick, basically. Since health is very expensive, you might not agree with what the insurance company, medicare guidelines, etc. decide. And you have less ability to use compounding, or working wages, to generate income to use as payment. In a society like Japan, they would respect your work over your life and (at least feel) that you have earned some freedom from these kind of stresses.

My idea America has free education, free healthcare, and maybe even some minimum living wage. With that in place, you would not have to care about turning $1 into $7 or $29. You would be able to care if you found it interesting, like I do or someone like Warren Buffett does, but you would not be required to figure it out or stress about it. But that's not the present reality, and that's why I would recommend doing at least the bare basic retirement / catastrophe savings. And I'll make it extremely easy: put as much away as you can spare, before you see it in your bank account, take any matches you can, and put it into a broad fund like the Vanguard Total Stock Index, lots of little purchases over time - and here's the key point: never look at it, at least as infrequently as possible, and avoid any news program or radio show that quotes you stock prices (NPR, please consider take this out of your morning report, or at least maybe consider not reporting a 1 point change which is under .01%, maybe just tell us if Black Friday happened). Then when you retire, you run the process in reverse, you withdraw lots of small amounts over a long period of time. That's basically the cutting edge of as close to a certain thing as it gets in finance, and I believe many, if not most, Profs of econ and finance do something similar.

{% include footer.md %}

###### Footnotes:

[^1]: Thanks NFTs for teaching us this arcane legalistic accounting term that I had previously only heard used by my MBA JD CPA childhood friend when discussing some test he was taking.
[^2]: 7% is generally considered the long run average return of the stock market. I first heard this number at UPenn as Wharton Prof. Jeremy Siegel published a well regarded 200 year study, in book form known as "Stocks for the long run." But in practice, even pension funds, which actually have multi-decade time horizons, seem to estimate larger returns. And if you asked an average American (given they had some basic idea of markets) what the stock market returns, I bet they'd say at least 10%, if not 20%. But over time, Black Fridays happen, and a 30% drop is not made whole by a 30% gain, and so a very long stretch of time, you get 7%. One other thing of note, this is better other asset classes (if other consists of bonds, gold, and cash). In chart form: <https://www.financial.com/wp-content/uploads/2016/07/siegel_returns_large.png>
[^3]: The standard form being `FV = PV(1 + r)^t`, where `FV` is future value, `PV` is present value, `r` is the annual return, and `t` is the time in number of years. There is a more complicated form which allows for other time periods, but this one is good for rough calculations, it's often easier to get the annualized return rate and use this formula (APR).
[^4]:
    A more sophisticated analysis would provide a range of outcomes and statistical weightings, perhaps with a Monte Carlo analysis to generate thousands of possibilities. An even more sophisticated analysis would take into account the fact that long tail events are almost impossible to predict, yet seem to happen more frequently than "once in a hundred years", and have a greater impact than works with "ignore the 1% outliers." One data point supporting this is that most of the stock returns occur on a small number of days - I can't find the study but here's a CNBC article referencing it saying "missing out on the 10 best-performing days during that 20-year period would have cut your returns in half" (https://www.cnbc.com/2020/02/28/heres-what-can-happen-if-you-flee-the-stock-market-for-cash.html). Modeling this is hard, if not impossible, and would likely take hours or more, so if we use our 30 second approximation, and say the final value is likely between 1/10 and 10x of it, that's probably pretty accurate.

    [^5]: `$58,000=$2,000 ( $29=$1(1.07^50) )`, `$116,000=$4,000 x $29`
    [^6]: Economists call this real return, the one including inflation is called the nominal rate.
    [^7]: You just can't get it until later. This is a basic tenant of finance called present value; it probably would have been much cooler to call it the relativistic time value of money, since the value depends on which point in time you look at it. But finance people don't care about being cool, just working the numbers, so there you have it.
    [^8]:
        These have, I believe, similar values to the US otherwise and so may not be such a difficult transition. There are of course many other countries that (attempt to) take care of their (not wealthiest) citizens.

        Seligman of UPenn's Positive Psychology Center did a review of the literature of wellbeing and world happiness studies. In particular to US, Canada, New Zealand, see these results of various studies: p 31 Figure 8, Page 33 Figure 12. <https://ppc.sas.upenn.edu/sites/default/files/wellbeingpublicpolicy.pdf>
