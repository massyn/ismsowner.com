# Introduction to ISMS Risk Assessments

At the heart of the Information Security Management System, is your risk assessment. When done right, the ISMS risk assessment will provide you with a valuable source of information to help you with prioritization and decision making. When there's way too much going on, and you as an organization are overwhelmed with issues, your risk assessment will help to guide where you need to focus your effort.

If you're interested to learn more about risk management in general, take a look into ISO 31000. In this article we'll give you a practical breakdown on how you can perform an ISMS risk assessment.

## How will an ISMS risk assessment work?

The most effective way to run an ISMS risk assessment is to facilitate a risk management workshop within your organization. Depending on the size and complexity of your organization, you could perform this over one, or several, days. Book a meeting room, organize lunch, invite your stakeholders, get plenty of Post-It notes and pens. An ISMS risk workshop should be interactive.

In a COVID scenario, where it isn't possible to meet in person, you could opt to do it online, using your favorite video sharing platform such as Zoom, Cisco Webex or Microsoft Teams, to achieve similar results.

## What is your ISMS risk assessment scope?

By the time you start thinking about doing an ISMS risk assessment, you should already have thought about your scope. An ISMS by it's very nature must have a scope that defines the boundaries of where you will focus your efforts. If for example your ISMS is focused on your call center operations, then there is no point in performing a risk assessment against your accounting department.

When in doubt – ask. Involve your senior stakeholders (CEO, CFO, CIO, CISO) and clarify what the boundaries of your ISMS and your risk assessment should be. In many cases this should be obvious within the scope of the operation you are delivering.

In the example of the call center operations, the ISMS scope may be limited to a single call center building, with 100 employees and the solutions that they use and rely upon.

## Who is involved in an ISMS risk assessment?

Identify the key stakeholders you need involved in the ISMS risk assessment. Who are they? Since the Information Security Management System may primarily be operated by the IT team, you'd assume the IT team should be involved. You'd be right, but only partly.

While the IT department may be the key executors of the IT operations, they are not the ultimate owners of the risk. ISMS risks are inherently owned by the business, since it is their systems that may potentially be impacted.

While the IT team may be looking at the technical side of a solution, they don't always see or appreciate the impact a particular solution can have on the risk assessment.

How well placed is an IT team to fully understand the impact if a taxation solution is unavailable for 2 days? An IT team may know that the Finance team will be unable to lodge taxation information to the government, as that is what the taxation solution is used for, but what does that really mean? Are there financial penalties for the business if that deadline is missed? Most IT team members would have no clue, it's not their area of expertise. But you can be sure that your Finance and Legal teams would be able to provide some input on this topic.

Be sure to involve the necessary stakeholders that can provide input on the consequences of a particular risk occurring.

## Performing an ISMS risk assessment workshop

The big day has arrived. Your stakeholders are seated around an oversized meeting room table. A neat stack of brightly colored Post-it notes and a pen sits in front of each attendee. A pot of freshly brewed coffee sits off to the side (only a strong suggestion, coffee is not mandated by ISO 27001... yet).

You kick off your ISMS risk assessment workshop, give an introduction, and get everyone on the same page. You explain what the expected outcome of the workshop is and strongly encourage their participation, as all stakeholders bring different inputs and viewpoints to risk.

### ISMS Risk Identification

Using the post-it notes, ask the participants to start writing down what they think could go wrong. On the post-it they should capture the following information :

*   Their name (in case you need to clarify what they wrote down)
*   What could go wrong?
*   What would be the consequence?

Encourage each person to write between 3 to 6 post-its.  There is no hard rule on this and stress to your stakeholders that there are no wrong answers either. If you get more or less that's OK. The important takeaway is to start identifying what kind of issues might occur within your organization.

*   There is no such thing as an incorrect answer when it comes to risk. If there is the slightest chance of something occurring, write it down.
*   Don't say "That will never happen to us" – it just hasn't happened yet!  Write that risk down.

### ISMS Risk Analysis

With the post-its completed, start pinning them on a board. Very soon you'll notice similarly themed risks appearing. Start grouping them together. For example, you may have a risk of malware infections appearing on servers, and you also have a risk of malware on your printers. From a risk point of view they will be the same risk, impacting multiple assets – group them together.

When grouping the risks together, keep an eye out for control failures. Let's assume you are running a backup solution for your server environment. The team is identifying a risk that should the backup solution fail, they would be unable to perform a restore. On face value this looks like a valid risk, but in reality, it is not. The risk in this scenario is the loss of data due to hardware failure, and a backup is the control. The fact that a backup stopped working and couldn't be restored is not a risk per se, but rather a control failure. As the risk facilitator, it will be your job to coach the participants in understanding the difference between a risk, and a control failure.

You should end up with a list of risks driven by the input from the post-it notes.

### ISMS Risk Evaluation

Now that you have a board full of post-it notes (and half of them are slowly starting to peel off and fall on the ground, as post-it notes always seem to for some reason), you should have a good sense of where the issues are. The next step is to start evaluating how bad things are, their criticality. We start by expanding the risks to consider the **consequence**. The consequence is the impact the risk would have if it were to occur. When thinking about consequences, keep in mind the CIA Triad (confidentiality, integrity, availability).

Without any controls, if this risk were to occur, how bad would it be?  Using a simplistic consequence scale, decide if the impact would be 1 (Insignificant), 2 (Moderate) or 3 (Catastrophic). Feel free to expand the scale if you believe 3 levels are not enough.

* **Insignificant **– The risk would have such a low impact that it could potentially be tolerated by the organization.
* **Moderate **– The risk would have some impact to the organization, either financially or operationally.
* **Catastrophic **– A catastrophic impact that would cause significant damage to the organization, large financial losses, loss of human life, extended downtime of systems or a risk that could severely affect the reputation of the organization.

Once you start having all your risks documented, with their consequences listed, now would be a good time to perform a calibration. Calibration allows the team to look at all the risks holistically, and determine if one catastrophic risk is really as important as another. It allows different team members to challenge each other respectfully and ensure the right consequence has been picked for each of the risks. A risk resulting in a single solution being unavailable suddenly doesn't look so catastrophic when it sits next to a risk resulting in the loss of life of an employee.

Once we are done with the consequences, we move on to likelihood. Consider everything we know, all the controls we have in place to manage those risks, how likely is it that the risk will occur?

Remember at this point that some risks just don't have highly effective controls that can be put in place to significantly lower the likelihood. Just because you identify that the likelihood of an event is "3 (Likely)", doesn't mean that your organization are failing.

*   1 (Unlikely) – Where you believe your controls are highly effective and sufficient to reduce the risk so that it will likely not occur.
*   2 (Probable) – Where you believe your controls may need some improvement, or they are not entirely effective in reducing the risk to the level where it is unlikely to occur.
*   3 (Likely) – Where you believe your controls are not effective at all, and that the realization of the risk may be imminent.

In order to truly understand your organization's risks, it is important to be brutally honest when assigning these ratings.

Again – feel free to expand the scale if you believe 3 is not sufficient.

### ISMS Risk Register and heat map

Using the attached free ISMS [Risk Register](Risk-Register.xlsx) template (or you can create your own), you can start building your ISMS risk register. Once it is complete, you will be able to see a risk heat map. The risk heat map is a representation of the number of risks falling into each category.

||**Insignificant**|**Moderate**|**Catastrophic**|
|--|--|--|--|
|**Likely**|Medium|High|Critical|
|**Probable**|Low|High|High|
|**Unlikely**|Low|Low|Medium|

## Who will own the ISMS risk?

The ISMS risk owner is the person who will decide on the ISMS risk treatment. They are ultimately responsible for the risk. If you're unable to decide on who the risk owner should be, ask yourself who would be the individual that would be called into the CEO's office if this risk were to occur – that's the name you pick.

Now before you simply choose the Head of IT as the risk owner for all risks, do consider that the Head of IT may not be responsible for the execution of the controls (for example the backups of any of the servers). The IT Head has most likely delegated that responsibility to one of the server administrators. Similarly, there are individuals throughout the organization that have different responsibilities, and as a result would also end up being risk owners for different risks within the Information Security Management System.

## ISMS risk decision

Some risks may be so insignificant that as an organization you may decide to simply "Accept" the risk. Accepting the risk effectively means that you will not implement any controls to reduce the likelihood of the risk to occur. Your organization are accepting that they will just deal with the consequences if the risk eventuates.

Where a control will be implemented to reduce the likelihood of a risk eventuating, you would choose to "Mitigate" the risk.

## ISMS risk treatment

Now that your ISMS risk register is complete, and you know where your different risks are, what are you going to do about managing them?

In most cases, you would already be doing something about it – almost all organizations already have some types of controls running, even though you may not yet have formally labelled them as "controls". In other cases, you may have to do something extra about it to reduce the risk.

Stuck for ideas on what to control? Have a look at Annex A of the ISO 27001 Standard, which provides a list of high level control objectives and controls.

Once you've decided on what controls you'd like to implement, you start by actually implementing them. Do not forget to update your [Statement of Applicability](statement-of-applicability.md) when you've decided on your risk treatment plans.

## ISMS control monitoring

Having a control is one thing, but how do you know if the control is actually effective?

Let's take our earlier backup failure example; Within your backup software, you should have the ability to extract a report that shows if all your servers are being backed up correctly. Download a copy of this report, save it somewhere, and keep it as evidence that you have checked the backups. Similarly, you can download (or generate) reports to prove that a specific check has been performed.

Be sure to document how often you will perform this activity.  If you committed to doing this once a month, you need to execute this control once a month, and document evidence that you've done it, and took actions on any gaps that were identified.

## 3rd party security controls

It is important to call out 3rd party security controls.  Let's take, for example, physical security access controls to your office building.  A.11.1 is all about physical security, the controls to your building, and how your staff gain access to your building.  What if you don't have a choice in the matter?  Some building leasing companies offer the physical security controls as part of the lease agreement, so while you're a tenant of the building, you inadvertently inherit the security controls that the building services bring you.

Now this adds a bit of confusion to your ISMS.  On the one hand, you _could_ argue that the physical security is _out of your scope_, but, you'd be wrong.  The protection of the physical environment is very much a key tenant of the defence in depth strategy, and as the ISMS Owner, you have an obligation to ensure that these security controls are operating correctly.

So what's the plan?  How do you then treat this particular risk?

You are partially right though.  In this scenario, the operation of the security control is outsourced to a 3rd party.  In this case, the building owner has taken the responsibility to operate the physical security controls on your behalf.  As the ISMS Owner, it is your job to ensure that these controls are working as expected.

Your lease contract may stipulate who can access the building, and when, and any other conditions that may exist.  As the tenant of the building, you will have a say in who can enter your part of the building.  All of this is laid out in the contract.  As part of your ISMS, this very first step should make up part of your control.  Physical access is managed by the 3rd party (building owner).  As the ISMS Owner, you can requests access logs of who has accessed the building at what times, and any anomality can trigger a follow up.

* What if someone accessed the building at 1am?  Is that normal behaviour?
* What if a terminated employee was able to access the building after they were terminated.  Is that normal?
* What if the turnstiles did not work, and simply allowed anyone to access the building.  Is that normal?

These are just some scenarios, but important ones that can be used to design controls _on your side_ of the equation.  While your team may not be the ones that physically allow individuals in the door, it is your team that needs to review the logs, and the access lists, and ensure that those basic controls are still being maintained.  As part of your regular service review with the landlord, you will also have an opportunity to review their reports, and raise any concerns with non-adherence to the required security controls.

## What if the control fails?

Things won't always work the way you want.  Sometimes the backup may fail. Then what? The key point to remember is that while a control failure is not a good thing, the ISMS will expect you to take action, and improve it.

Use the opportunity to perform a root cause investigation, identify why the failure occurred, and implement any improvement opportunities to prevent the control from failing again in future. Be sure to record the improvement actions, so that you can demonstrate that you have done something to make things better.

By continuing to monitor the control, you should see an improvement in your metrics. If the metrics do not improve, perform another root cause investigation.

## Types of risk to consider

Stuck for ideas on what could go wrong?  Here's a sample of some risks to get you started.

* Defacement of websites could lead to loss of reputation
* Customer data breach due to credential compromise
* System outage due to hardware failure
* Legal risks due to insufficient data privacy consideration
* Use of Shadow IT solutions can lead to increased risk of data disclosure
* Users acting on phishing emails can lead to compromised credentials

## Tips for a successful ISMS risk assessment workshop

* Start the workshop with an introduction from a senior management leader. Having senior management buy-in will help to ensure enthusiasm and commitment from team participants.
* Encourage participation from everyone – you need everyone's voice heard, everyone has different skill sets and experience. That brand new manager who was recently hired; they may have seen some things at their previous organization that are applicable here.
* Some leaders may have a tendency to bulldoze their way through a meeting – where possible, do not allow senior leaders to force their view on the team. They can certainly have an input in the process, but should not be dictating the outcome of the risk assessment.
* Nominate someone to be the scribe. Their role will be to document the risks and the outcome of the risk assessment (you will need it as evidence for your ISO27001 audit).
* A risk assessment is a continual activity. Schedule a revisit of your risk assessment at least once every 12 months, or when there are significant changes in your organization.

## In conclusion

The ISMS Risk Assessment is a core component of every Information Security Management System, without an effective risk assessment you can't have an effective ISMS.

Now armed with the core knowledge required to run a risk assessment, dedicate the time to do it effectively so that you can add true value to the rest of your ISMS.

