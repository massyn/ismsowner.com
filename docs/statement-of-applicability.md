# Statement of Applicability

So what is a Statement of Applicability? As part of your risk treatment process, 6.1.3 d) states:

> produce a Statement of Applicability that contains the necessary controls (see 6.1.3 b) and c)) and justification for inclusions, whether they are implemented or not, and the justification for exclusions of controls from Annex A

So clearly the standard expects us to build this document, but it's not entirely clear why. It is important to read section 6.1.3 in its entirety to get a sense of what the authors had in mind. So let's backtrack a bit...

## What is Annex A?

By now you should be familiar with Annex A. Annex A is the collection of 93 controls that make up a large portion of the ISO27001:2022 standard. While the standard is very clear that it is not a collection of controls, these controls do make up the majority of the documentation.

These controls are made up of the key controls every security solution _should_ have in place. As the ISMS Lead, it is your responsibility to review the controls selected during the risk assessment and risk treatment process and map those risks against the relevant Annex A controls.

## So what is the SOA then?

6.1.3 c) explains that as part of the risk treatment process, you need to review the controls in Annex A to ensure that you haven't omitted any relevant controls. That's where the _applicability_ piece comes in. You compare your risk against all relevant Annex A controls and _justify_ why these controls are required or not required.

The value this brings is that it ensures the controls selected are in fact driving value toward risk reduction by requiring you to review and produce the statement of applicability.

## Completing the SOA

Using the sample template below, record the risk numbers against each Annex A control and complete a justification as to why the controls are in place. As a general rule, there should only be a handful of exclusions. When you see a large number of exclusions, chances are you have a gap in the risk treatment process, and you may need to revisit your risk treatment process.

## Sample SOA

Note that every control in Annex A must have a justification. Relate the controls to the relevant risk and add some justifications as to why the control is either in or out of scope. I've given some examples below.

**Note:** This example shows the ISO27001:2022 structure with 4 control categories (Organizational, People, Physical, Technical) and 93 total controls, compared to the previous 14 categories and 114 controls in ISO27001:2013.

|**Ref**|**Control Title**|**Related Risks**|**Included / Excluded**|**Justification**|
|--|--|--|--|--|
|**A.5 - Organizational Controls**|||||
|A.5.1|Policies for information security|Risk001,Risk002|Included|Key requirement of the ISMS|
|A.5.2|Information security roles and responsibilities||||
|A.5.3|Segregation of duties||||
|A.5.7|Threat intelligence||||
|A.5.23|Information security for use of cloud services||||
|**A.6 - People Controls**|||||
|A.6.1|Screening||||
|A.6.2|Terms and conditions of employment||||
|A.6.3|Information security awareness, education and training||||
|A.6.4|Disciplinary process||||
|A.6.5|Responsibilities after termination or change of employment||||
|A.6.6|Confidentiality or non-disclosure agreements||||
|A.6.7|Remote working||Excluded|No remote working is allowed within our organisation, hence the control is out of scope.|
|A.6.8|Information security event reporting||||
|**A.7 - Physical Controls**|||||
|A.7.1|Physical security perimeters||||
|A.7.2|Physical entry||||
|A.7.3|Protection against environmental threats||||
|A.7.4|Equipment siting and protection||||
|A.7.5|Secure disposal or reuse of equipment||||
|A.7.6|Clear desk and clear screen||||
|A.7.7|Secure storage||||
|A.7.8|Equipment maintenance||||
|A.7.9|Removal of assets||||
|A.7.10|Storage media||||
|A.7.11|Supporting utilities||||
|A.7.12|Cabling security||||
|A.7.13|Equipment servicing||||
|A.7.14|Secure disposal or reuse of equipment||||
|**A.8 - Technical Controls**|||||
|A.8.1|User endpoint devices||||
|A.8.2|Privileged access rights||||
|A.8.3|Information access restriction||||
|A.8.4|Access to source code||||
|A.8.5|Secure authentication||||
|A.8.6|Capacity management||||
|A.8.7|Protection against malware||||
|A.8.8|Management of technical vulnerabilities||||
|A.8.9|Configuration management||||
|A.8.10|Information deletion||||
|A.8.11|Data masking||||
|A.8.12|Data leakage prevention||||
|A.8.13|Information backup||||
|A.8.14|Redundancy of information processing facilities||||
|A.8.15|Logging||||
|A.8.16|Monitoring activities||||
|A.8.17|Clock synchronisation||||
|A.8.18|Use of privileged utility programs||||
|A.8.19|Installation of software on operational systems||||
|A.8.20|Networks security||||
|A.8.21|Security of network services||||
|A.8.22|Segregation of networks||||
|A.8.23|Web filtering||||
|A.8.24|Use of cryptography||||
|A.8.25|Secure system engineering life cycle||||
|A.8.26|Application security requirements||||
|A.8.27|Secure system architecture and engineering principles||||
|A.8.28|Secure coding||||
|A.8.29|Security testing in development and acceptance||||
|A.8.30|Outsourced development||||
|A.8.31|Separation of development, testing and operational environments||||
|A.8.32|Change management||||
|A.8.33|Test information||||
|A.8.34|Protection of information systems during audit testing||||

**Important Note:** The above table shows a representative sample of the new ISO27001:2022 structure. Organizations should refer to the complete ISO27001:2022 Annex A for all 93 controls when creating their actual Statement of Applicability.

