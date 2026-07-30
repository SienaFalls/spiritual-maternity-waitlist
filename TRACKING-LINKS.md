# Tracking links for the Spiritual Maternity waitlist

Use these instead of the plain URL anywhere you post or send the page. The tags
at the end are invisible to the reader and tell Analytics where the visit came
from. Without them, Instagram and email traffic both land in a bucket called
"direct" and you cannot tell them apart.

The page itself works identically with or without the tags.

## The links

**Instagram bio link**

```
https://sienafallsmedia.com/domusaurea/spiritual-maternity-waitlist/?utm_source=instagram&utm_medium=social&utm_campaign=spiritual_maternity&utm_content=bio_link
```

**Instagram story / link sticker**

```
https://sienafallsmedia.com/domusaurea/spiritual-maternity-waitlist/?utm_source=instagram&utm_medium=social&utm_campaign=spiritual_maternity&utm_content=story
```

**Instagram feed post**

```
https://sienafallsmedia.com/domusaurea/spiritual-maternity-waitlist/?utm_source=instagram&utm_medium=social&utm_campaign=spiritual_maternity&utm_content=feed_post
```

**Facebook post**

```
https://sienafallsmedia.com/domusaurea/spiritual-maternity-waitlist/?utm_source=facebook&utm_medium=social&utm_campaign=spiritual_maternity&utm_content=page_post
```

**Personal emails to friends**

```
https://sienafallsmedia.com/domusaurea/spiritual-maternity-waitlist/?utm_source=email&utm_medium=email&utm_campaign=spiritual_maternity&utm_content=friends_outreach
```

**My Secret is Mine newsletter**

```
https://sienafallsmedia.com/domusaurea/spiritual-maternity-waitlist/?utm_source=substack&utm_medium=newsletter&utm_campaign=spiritual_maternity&utm_content=msim
```

**Domus Aurea newsletter**

```
https://sienafallsmedia.com/domusaurea/spiritual-maternity-waitlist/?utm_source=substack&utm_medium=newsletter&utm_campaign=spiritual_maternity&utm_content=domusaurea
```

**Edith Stein novena emails**

```
https://sienafallsmedia.com/domusaurea/spiritual-maternity-waitlist/?utm_source=substack&utm_medium=newsletter&utm_campaign=spiritual_maternity&utm_content=novena
```

## Making more

Keep `utm_campaign=spiritual_maternity` the same on every link, always. That is
what groups them together in Analytics. Change only the last part,
`utm_content`, to describe the specific placement. Lowercase, underscores, no
spaces.

## Where to look in Analytics

Reports → Acquisition → Traffic acquisition, then set the dimension to
**Session source / medium**. Add **Session manual ad content** as a secondary
dimension to see the `utm_content` detail.

Give it 24 to 48 hours before judging anything. Analytics is slow to populate
and the first day always looks wrong.

## Worth knowing

- The novena runs August 1 through 9 and ends on Edith Stein's feast. Tagging
  those nine emails separately tells you whether novena readers convert to the
  waitlist, which is the single most useful number you will get this month.
- Kit already reports click rates per email. Analytics tells you what happened
  after the click. The two answer different questions.
- Instagram strips link previews in some placements but the tags survive.
