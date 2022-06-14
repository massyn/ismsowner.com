# Measures and Metrics

You've completed your [risk assessment](risk-assessment.md), defined the list of controls you'd like to have.  Now you need to start monitoring those controls.

## What is a control?

A control is an action or process that we put in place in an effort to lower the likelihood or impact of a risk.  That sounds like a mouthful, but it boils down to something you can explain easily, for example : _All users must change their passwords every year._

## What is a measure?

You've defined your control - how do you know if this control is effective?  Is it doing what you designed it to do?  This is where our measure (or metric) comes in.

A measure is a [KPI](https://en.wikipedia.org/wiki/Performance_indicator), a score, a percentage, a number, _something_ that indicates if the control is working correctly.  In our example, if you define that all users must change their passwords every year (and assuming you're using Microsoft Active Directory), you could run a command like this:

```dsquery user * -stale 365 -o upn```

The output of this command will list all the user accounts that have a password older than one year.

## Data Collection

Every dashboard needs data, and the data has to be:

* **Reliable** - the data collection process must be robust and capable of recovering in the event of failure or errors.
* **Timely** - if there is an expectation for the metric to update daily, you need to ensure the data collection runs every day
* **Credible** - it must have trust - the process being used has a high degree of confidence with no false positives.
* **Relevant** - when the data is displayed on a dashboard, the right audience need to see the data relevant to them.

Metrics drive behaviour.  Someone will be looking at the data, and they will be taking an action to resovle the issue.  It is important that the data is accurate so you can continue to encourage your team to continue taking ownership of the metric.

## Percentages - reach for 100%

Once you've run the command, you'll be presented with a list of user accounts with expired passwords.  This is fine for the team who needs to follow up, and perform the remediation activities.  For you as the control owner, it may not add much value.

As a general rule, all metrics should be written in percentages, with 0% being bad, and 100% being the best.  While that may appear obvious, consider that a metric can be written as _Users with expired passwords_ - this could mean the number of users, but it is not obvious.  Instead, it should be written as _Percentage of users with valid passwords_.

So while you have executed the command to find the users with expired passwords, you may also need to run the command to extract all accounts, so you can calculate a percentage.

## Recording

Your metric may need to be executed daily.  If so, you need to record this data in your dashboard.  Your ISMS has a requirement to demonistrate continuous improvement, and having the measures recorded daily (and graphed over a period of time) will generate confidence in your control.

## Review and Improve

Assuming you are recording the number daily, either manually in some tool like Excel, or automatically in a database, you have to be able to prove that you are taking an action on the gaps.  Any issue reported through the metric should have some remediation action in place.  You must be able to demonstrate that an action has been taken, and an improvement plan is implemented.

## How much data to record

Some data sources can generate huge amounts of data.  While ISO27001 doesn't state anything specific, you need to be pragmatic with the amount of data collection.  If you have a huge organization, and extracting your entire Active Directory every day will generate many gigabytes of storage requirements, it may not be practical to go down that route.  At the very least, you may need to store the last data extract to demonstrate your improvement actions.

You should also record the aggregated data (the percentage, total number of objects, total number of valid objects, date & time of data collection).  Since the aggregated data storage requirements are minimal, you may decide to store this for a longer period of time.

## Build your dashboard

With all the data collected, you can build a dashboard.  With so many automation options available today, dashboards can be built to suit your specific organizational needs.  Review the dashboard frequently within your ISMS meetings, celebrate where you measures achieve targets, challenge when they don't, and record the actions to prove you are taking the measures seriously.

### Sample dashboard

|**Measure**|**Jan**|**Feb**|**Mar**|**Apr**|**May**|**Jun**|**Jul**|**Aug**|**Sep**|**Oct**|**Nov**|**Dec**|
|--|--|--|--|--|--|--|--|--|--|--|--|--|
|**A.12.2.1 - Anti-malware agents up to date**|80%|81%|83%|84%|85%|
|**A.12.3.1 - All servers are backed up daily**|100%|100%|98%|97%|100%|












