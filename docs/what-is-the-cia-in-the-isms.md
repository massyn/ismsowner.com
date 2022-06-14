# What is CIA in ISMS

## Overview

C.I.A, a core concept when it comes to Information Security. But what does the C.I.A acronym mean?

Straight to the point, it is referring to the three areas of Confidentiality, Integrity and Availability. If all you are after are those names, then the job of this article done, you can head home now. But if you would like to learn more, keep reading and let's take a slightly deeper dive into the three areas of Confidentiality, Integrity and Availability.

C.I.A is used widely throughout Information Security, so even if you aren't working on an [ISMS](what-is-an-isms.md) it is still critical that you fully understand this concept.

## CIA Triad

Together the three elements of Confidentiality, Integrity and Availability come together to form what is known as the CIA Triad. A bit like the Power Rangers TV show of the 1990s, they come together to make a greater force. The Aristotle quote of "the whole is greater than the sum of its parts" also comes to mind here.

By referring to the CIA triad as part of your [ISMS risk assessment](risk-assessment.md) you are forced to take a more holistic view of the security requirements for an asset, avoiding having a single-minded focus on just one or two of the factors.

Depending on which asset you are assessing, you may determine that one, two or all three of the CIA triad need to be protected. On the other hand, in some cases you might not need to worry about any of them at all.

No one part of CIA Triad is "more important" than another. They must all be considered.

## Confidentiality

Let's kick things off with the "C". Confidentiality.

ISO 27000 defines Confidentiality as the _"property that information is not made available or disclosed to unauthorized individuals, entities, or processes"_.

If there is a negative consequence if your information is seen by anyone and everyone in the whole world, then you have a need to ensure Confidentiality.

### Confidentiality examples

* **Confidentiality example 1 – required** : _"Network diagrams used by your internal network team."_ This information is intended to be used internally only. Information about internal procedures and assets could be used by a malicious actor in scenarios such as a technical cyber attack or in social engineering.

* **Confidentiality example 2 – may not be required**: _"General brand information about your organization which is published on your company website."_ There is no risk presented if anyone reads this information, in fact, it is intended for public consumption on your website. However, note that this is applicable only for the customer-facing brand content that is presented, the back-end is still intended to remain confidential.

## Integrity

Next we will look at the "I". Integrity.

ISO 27000 defines Integrity as the _"property of accuracy and completeness"_.

If there a negative consequence if your information is modified in an unintended way, then you need to ensure integrity.

### Integrity examples

* **Integrity example 1 – required**: _"Content on your public website"_. Integrity is important for even your publicly available information, as your website acts as your public-facing billboard. What if the content of a website owned by a manufacturing company was modified with messages suggesting that they support child labor or a questionable political party.

* **Integrity example 2 – required**: _"An internal finance spreadsheets used for calculating company profits"_. Integrity is absolutely critical for finance applications. If data is modified in any way there is the potential for catastrophic financial and legal consequences.

* **Integrity example 3 – may not be required**: _"Dummy data"_. This is a bit of a tricky one. Even the example of dummy data is questionable. It shouldn't contain any confidential information by definition, so you don't particularly care even if it was published online by a hacker for the world to see. Nobody is likely to be impacted if a dummy customer name is changed from "John Smith" to "Joe Smith". But, what if the dummy data had been structured in a specific way so that it was used as input for test scenarios, one of which was testing that a 4-character first name would be accepted as field input? Change the "John" to "Joe" and suddenly you are testing only 3-character first names, leading to an error not being identified in the Test environment and the bad code being pushed to Production. John Smith then tries to place an order but the system won't accept his name. Maybe the integrity of that dummy data was important after all. In fact, the protection of Test Data is specifically called out within Annex A of ISO 27001.

## Availability

Finally, you guessed it (I hope), we will tackle the "A". Availability.

ISO 27000 defines Availability as the _"property of being accessible and usable on demand by an authorized entity"_.

Put extremely simply; does the asset need to work?

### Availability examples:

* **Availability required example** : _"Solution used for employees to process their travel expenses"_. It would have been easier here to have used the example of a solution used by a business to process sales orders, but even a solution which isn't critical for an organization's core revenue generating activities still has an availability aspect which needs to be considered. Will the company sink if their travel expense solution is unavailable for a few days? Likely not. However, there is an expectation from the organization that the solution will be available when it is needed.

* **Availability may not be required example**: _"Solution used for running internal social club trivia competition"_. There may be paper-based trivia redundancies in place, the organization could proceed almost as normal even if the solution is unavailable, it was only being used by the social club after all. It won't impact the organization's sales. However, also consider here if you are paying for the service, there is a financial impact when something you are paying for is not available. What if you were paying $10,000 month for this trivia solution, if it's not available when you need it then that is money that you are throwing away.

## Conclusion

If you have made it this far in the article you are probably now realizing that the C.I.A concept is pretty straight forward, but there are a few little tricks to watch out for too.

When you are paying money for something, or your organization places any other form of value on an asset, it is almost certain that at least part of the CIA Triad will come into play.

Now that you have this understanding, every time that you need to assess an asset, carefully consider which of these three pillars you need to uphold. It may be one, it may be all three. Going into an [ISMS risk assessment](risk-assessment.md) with knowledge of the CIA triad up your sleeve positions you to better understand the actual risks and consequences that assets present. This ultimately guides you towards an ISMS that is making more informed risk decisions.

Are you confused with some of the terminology used in this article? If so, check out the [ISMS list with definitions](isms-list-of-definitions.md).