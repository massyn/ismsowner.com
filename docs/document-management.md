# ISMS Document Management

ISMS Document Management is an important topic in any [Information Security Management System](what-is-an-isms.md). In fact, ISO27001:2022 has an entire section dedicated to this area alone (refer to clause **7.5** Documented information in [ISO27001](isms-iso-standards-summarised-list.md)).

For an ISMS to operate effectively, you need to be able to keep accurate and consistent records of the key issues and decisions that have been taken. After all, you are operating an ISMS to improve the security posture of your organization, and you cannot do that if the mechanism for storing and managing all your related documents are not set up in the right way.

## What is a "document"?

If your first thought is _Microsoft Word documents_, you would only be partially right. A "document" in the strictest definition of the ISMS is **any piece of information** that can be used to drive, or demonstrate the effectiveness of the ISMS.

An ISMS document can include, but is not limited to, the following bits of information:

* ISMS Policy (or ISMS Charter) document
* ISMS Scope document
* [Asset Inventory](inventory-of-assets.md)
* [Risk Assessment](risk-assessment.md)
* Remediation Plans
* Skills and Training plan
* Management Review Meeting minutes
* Communication plan
* Controls and Control Procedures
* Evidence of control execution
* Monitoring dashboards

## Availability

Any ISMS documentation must be available to the relevant stakeholders. Essentially this means that your ISMS team must know how to access the information, and they must have the necessary access to the particular repository. It doesn't matter what the actual technology is that you use (be it a shared drive, Microsoft SharePoint, or a Google Docs repository), as long as the team can get to it when they need to, you're all set.

Be careful with uncontrolled copies. An uncontrolled copy is (for example) a printed version of a document. Any changes to the document will obviously not be reflected in the printed copy. As part of your ISMS, it has to be stated that your ISMS repository is the single source of truth, and that the team will always need to refer to the repository for the latest and most up-to-date information.

## Identification

Having a folder full of files does not instill sufficient confidence that your document management process is under control. Implement a naming convention that helps you quickly identify which documents are key ISMS documents, which are related to risks, controls, etc. It doesn't really matter what the naming convention is, as long as you can find a document quickly.

You also need to ensure that every document contains a title and a description, name of the author, and/or a reference number.

## Data Protection

When defining a document management strategy, you have to consider a number of data protection scenarios, for example:

* Who requires read access to the repository?
* Who will be allowed to make changes?
* How will access be segmented? Some members may be allowed to update some sections, while others will only be allowed to update others.

These scenarios are important to consider to ensure that the Information Security Management System has integrity. When you review the documentation, you need to have confidence that the documents have not been tampered with, that the decisions documented are in fact what has been decided. When too many people have access to modify or write information into the repository, it can deteriorate the integrity of your ISMS.

It goes without saying that your document repository should also feature at some level within your ISMS. The document repository is an information asset just like any other information asset you are trying to protect, so it is important to ensure that your ISMS document repository is only accessible to the key individuals that need it.

What about your backups? Are you satisfied that this repository is protected from accidental or malicious destruction? Make sure that a regular backup is in place. Do not assume that backups are automatically being performed. Treat your ISMS documentation in the same way that you would treat any other important business documents. [CIA](what-is-the-cia-in-the-isms.md) must be appropriately considered.

## Version Control

What changes? Who changed it? Why did they change it? Who approved those changes? These are just some of the questions that you may face, not just in an audit, but possibly when things go wrong. Having a good handle on the history of your ISMS documentation will also help you to track down why things changed.

The creation and modification of some documents will require a validation and approval process. This is something which you will need to define in your ISMS policy document.

Let's demonstrate a few use-cases:

* Your organization has acquired a new business, and this business has to be integrated into your ISMS. The ISMS expansion will require an update to the ISMS Policy and ISMS Scope documents. These changes will need to be formally approved through a Management Review meeting, with meeting minutes captured, and the change to the documents will need to be approved by a senior member of the ISMS (possibly the head of the department) since the changes to the ISMS policy document will also dictate how the rest of the risk assessments and control executions will be performed.
* During a control execution process, the control owner identified that the control was not effective. Upon performing a root cause investigation, the control owner identified a mistake in the procedure for the control and then initiates a remediation task to correct the procedure. The update to the specific procedure would not necessarily require formal approval, however from a version control perspective, the change to the document must be available, as well as previous versions. The information captured within that version control section can then also be referred to in the future to help explain why past control execution results and evidence may be different to current expectations.

## Retention

How long should you keep your documents? Just like asking about the length of a piece of string, it really depends. There are legal requirements in some jurisdictions that require financial records to be kept for at least 7 years (implying you can store more than you require), then there are health and privacy laws that dictate you should only keep information for the shortest duration possible. While we're not necessarily storing that information, you may inadvertently store evidence through your control execution process that could contain sensitive data. Be mindful of what you are storing and ensure that you adhere to any regulatory requirements for your jurisdiction.

What about your ISMS? How long should you keep your documents? ISO27001 does not specify. Keeping in line with version control, the advice would be to keep it as long as it makes sense.

## Review

Not all documents will ever be perfect. Things change all the time, and having a regular document review process in place will go along way to drive improvements within your document management process.

Define how often documents need to be reviewed. You may decide to review your ISMS Policy and ISMS Scope documents once every 6 months. You may decide to have a quarterly review for all control procedures. Whatever decision you make, make sure you track it, know which documents are due for review, and follow through on updating the documents.

## Document format

There will be various types of documents that can be stored in your ISMS. You can store things like :

* Microsoft Office documents
* Log files
* Images (photos or screenshots)
* PDFs
* Text files
* CSV of JSON data dumps

But of course these are just examples. The list of different types of documents is almost limitless. You could even have video evidence showing physical site inspections, if it made sense.

## Tools to use

Hopefully your organization will already have some sort of a document management solution in place, so there shouldn't be a need to purchase anything new.

Would you prefer to use a Wiki, instead of Microsoft Office documents? Why not! Anything really can be used, as long as you can demonstrate that the data is protected, version controlled, etc (as mentioned above) you can use any tool you like.

The most basic document management system is likely a shared folder on a departmental file server. While this does allow for easy access to the documentation, it does lack in version control. Some organizations like to create a new file for every version (eg. **My File – version 1.1.docx**) and create a new file every time a new version gets published. This is a highly ineffective way of working, and will result in multiple copies of different versions of the document to be circulating within your environment. Tools like Microsoft SharePoint do allow workflows to be setup, keeping track of previous versions, as well as folders to be locked down to prevent unauthorized modification or deletion.

## Summary

Hopefully this article has given you a better appreciation for ISMS document management. ISO 27001 allows quite a lot of flexibility in this space, so as long as your solution can meet the limit mandatory requirements, work out a system that works best for your organization.