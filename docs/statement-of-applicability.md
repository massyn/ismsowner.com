# Statement of Applicability

So what is a Statement of Applicability?  As part of your risk treatment process, 6.1.3 d) states :

> produce a Statement of Applicability that contains the necessary controls (see 6.1.3 b) and c)) and justification for inclusions, whether they are implemented or not, and the justification for exclusions of controls from Annex A

So clearly the standard expects us to build this document, but it's not entirely clear why.  It is important to read section 6.1.3 in its entirety to get a sense of what the authors had in mind.  So let's backtrack a bit...

## What is Annex A?

By now you should be familiar with Annex A.  Annex A is the collection of 114 controls that make up a large portion of the ISO27001 standard.  While the standard is very clear that is not a collection of controls, these controls do make up the majority of the documentation.

These controls are made up of the key controls every security solution _should_ have in place.  As the ISMS Lead, it is your responsibility to review the controls selected during the risk assessment and risk treatment process, and map those risks against the relevant Annex A controls.

## So what is the SOA then?

6.1.3 c) explains that as part of the risk treatment process, you need to review the controls in Annex A to ensure that you haven't omitted any relevant controls. That's where the _applicability_ piece comes in.  You compare your risk against all relevant Annex A controls, and you _justify_ why these controls are required or not required.

The value this brings, is it ensures that the controls selected are in fact driving value towards the risk reduction, by requiring you to review and produce the statement of applicability.

## Completing the SOA

Using the sample template below, record the risk numbers against each Annex A control, and complete a justification as to why the controls are in place.  As a general rule, there should only be a handful of exclusions.  When you see a large number of exclusions, chances are you have a gap in the risk treatment process, and you may need to revisit your risk treatment process.

## Sample SOA

Note that every control on the Annex A must have a justification.  Relate the controls to the relevant risk, and add some justifications as to why the control is either in or out of scope.  I've given some examples below.

|**Ref**|**Control Title**|**Related Risks**|**Included / Excluded**|**Justification**|
|--|--|--|--|--|
|A.5.1.1|Policies for information security|Risk001,Risk002|Included|Key requirement of the ISMS|
|A.5.1.2|Review of the policies for information security||||
|A.6.1.1|Information security roles and responsibilities||||
|A.6.1.2|Segregation of duties||||
|A.6.1.3|Contact with authorities||||
|A.6.1.4|Contact with special interest groups||||
|A.6.1.5|Information security in project management||||
|A.6.2.1|Mobile device policy||||
|A.6.2.2|Teleworking||Excluded|No remote working is allowed within our organisation, hence the control is out of scope.|
|A.7.1.1|Screening||||
|A.7.1.2|Terms and conditions of employment||||
|A.7.2.1|Management responsibilities||||
|A.7.2.2|Information security awareness, education and training||||
|A.7.2.3|Disciplinary process||||
|A.7.3.1|Termination or change of employment responsibilities||||
|A.8.1.1|Inventory of assets||||
|A.8.1.2|Ownership of assets||||
|A.8.1.3|Acceptable use of assets||||
|A.8.1.4|Return of assets||||
|A.8.2.1|Classification of information||||
|A.8.2.2|Labelling of information||||
|A.8.2.3|Handling of assets||||
|A.8.3.1|Management of removable media||||
|A.8.3.2|Disposal of media||||
|A.8.3.3|Physical media transfer||||
|A.9.1.1|Access control policy||||
|A.9.1.2|Access to networks and network services||||
|A.9.2.1|User registration and de-registration||||
|A.9.2.2|User access provisioning||||
|A.9.2.3|Management of privileged access rights||||
|A.9.2.4|Management of secret authentication information of users||||
|A.9.2.5|Review of user access rights||||
|A.9.2.6|Removal or adjustment of access rights||||
|A.9.3.1|Use of secret authentication information||||
|A.9.4.1|Information access restriction||||
|A.9.4.2|Secure log-on procedures||||
|A.9.4.3|Password management system||||
|A.9.4.4|Use of privileged utility programs||||
|A.9.4.5|Access control to program source code||||
|A.10.1.1|Policy on the use of cryptographic controls||||
|A.10.1.2|Key management||||
|A.11.1.1|Physical security perimeter||||
|A.11.1.2|Physical entry controls||||
|A.11.1.3|Securing offices, rooms and facilities||||
|A.11.1.4|Protecting against external and environmental threats||||
|A.11.1.5|Working in secure areas||||
|A.11.1.6|Delivery and loading areas||||
|A.11.2.1|Equipment siting and protection||||
|A.11.2.2|Supporting utilities||||
|A.11.2.3|Cabling security||||
|A.11.2.4|Equipment maintenance||||
|A.11.2.5|Removal of assets||||
|A.11.2.6|Security of equipment and assets off-premises||||
|A.11.2.7|Secure disposal or reuse of equipment||||
|A.11.2.8|Unattended user equipment||||
|A.11.2.9|Clear desk and clear screen policy||||
|A.12.1.1|Documented operating procedures||||
|A.12.1.2|Change management||||
|A.12.1.3|Capacity management||||
|A.12.1.4|Separation of development, testing and operational environments||||
|A.12.2.1|Controls against malware||||
|A.12.3.1|Information backup||||
|A.12.4.1|Event logging||||
|A.12.4.2|Protection of log information||||
|A.12.4.3|Administrator and operator logs||||
|A.12.4.4|Clock synchronisation||||
|A.12.5.1|Installation of software on operational systems||||
|A.12.6.1|Management of technical vulnerabilities||||
|A.12.6.2|Restrictions on software installation||||
|A.12.7.1|Information systems audit controls||||
|A.13.1.1|Network controls||||
|A.13.1.2|Security of network services||||
|A.13.1.3|Segregation in networks||||
|A.13.2.1|Information transfer policies and procedures||||
|A.13.2.2|Agreements on information transfer||||
|A.13.2.3|Electronic messaging||||
|A.13.2.4|Confidentiality or nondisclosure agreements||||
|A.14.1.1|Information security requirements analysis and specification||||
|A.14.1.2|Securing application services on public networks||||
|A.14.1.3|Protecting application services transactions||||
|A.14.2.1|Secure development policy||||
|A.14.2.2|System change control procedures||||
|A.14.2.3|Technical review of applications after operating platform changes||||
|A.14.2.4|Restrictions on changes to software packages||||
|A.14.2.5|Secure system engineering principles||||
|A.14.2.6|Secure development environment||||
|A.14.2.7|Outsourced development||||
|A.14.2.8|System security testing||||
|A.14.2.9|System acceptance testing||||
|A.14.3.1|Protection of test data||||
|A.15.1.1|Information security policy for supplier relationships||||
|A.15.1.2|Addressing security within supplier agreements||||
|A.15.1.3|Information and communication technology supply chain||||
|A.15.2.1|Monitoring and review of supplier services||||
|A.15.2.2|Managing changes to supplier services||||
|A.16.1.1|Responsibilities and procedures||||
|A.16.1.2|Reporting information security events||||
|A.16.1.3|Reporting information security weaknesses||||
|A.16.1.4|Assessment of and decision on information security events||||
|A.16.1.5|Response to information security incidents||||
|A.16.1.6|Learning from information security incidents||||
|A.16.1.7|Collection of evidence||||
|A.17.1.1|Planning information security continuity||||
|A.17.1.2|Implementing information security continuity||||
|A.17.1.3|Verify, review and evaluate information security continuity||||
|A.17.2.1|Availability of information processing facilities||||
|A.18.1.1|Identification of applicable legislation and contractual requirements||||
|A.18.1.2|Intellectual property rights||||
|A.18.1.3|Protection of records||||
|A.18.1.4|Privacy and protection of personally identifiable information||||
|A.18.1.5|Regulation of cryptographic controls||||
|A.18.2.1|Independent review of information security||||
|A.18.2.2|Compliance with security policies and standards||||

