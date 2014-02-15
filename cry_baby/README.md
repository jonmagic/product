Cry :baby:
========

My sister recently had a baby boy and about six weeks after his birth I asked her what the hardest parts of being a new mother were. She immediately replied the hardest thing for her was not knowing why he was crying and or how to appease him.

The process of appeasing my nephew usually means cycling through several things, is he hungry, does he need his diaper changed, does he just need held, does he need rocked, the list goes on.

## The Idea

Let's start by clearing stating **the problem** in the form of a question: How does a new parent determine why their infant is crying in order to take the action necessary to appease the cry?

An **ideal solution** might be: Shortly before or shortly after the infant starts crying the new parent gets a notification on their phone prompting them to take a specific action to appease the cry.

## Questions

* What inputs do we have that might help us form an algorithm to determine why a baby is crying?
* Can we put sensors in the clothing or diaper of an infant that might tell us whether it is hungry or needs it's diaper changed?
* Could there be a correlation between environmental factors and the cry? Time of day, temperature, humidity?
* Could there be a correlation between the recent history of reasons the baby was crying and the current reason? I.e. An hour ago I fed the infant so now it is more likely their diaper needs changed than they are hungry again.
* Are there different types of crying, differences in pitch, duration, or intensity? Is recording the crying in order to look for correlations a realistic goal?

## First Steps

For a project like this I would want to start by just collecting data. We would essentially need to get a group of parents with infants to volunteer to track cries and what appeased the cries. Maybe a super simple mobile application for logging cries and actions, possibly augmented with a hardware monitor (audio, temperature, moisture).

The metrics I would want to track in this first phase are:

* Time of day.
* Every action taken before the crying stopped.
* Parents emotional state during and after the crying.
* Environmental factors, temperature, humidity, light levels.
* (if possible) Moisture in diaper when crying started.

After a few weeks of tuning data collection and then a few more of consistent collection I would start analyzing the data, seeing if correlations can be drawn. I imagine the minimum group size to be 5-10 families, ideally 20-50.

## Conclusion

This was purely an exercise and not something I'm planning on doing, although I would be happy to become a volunteer when I become a father later this year :sparkles:
