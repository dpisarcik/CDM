
# nonProfit


## Entities

|Name|Description|
|---|---|
|[Account](Account.cdm.json)|Business that represents a customer or potential customer. The company that is billed in business transactions.  |
|[Address](Address.cdm.json)|Address and shipping information. Used to store additional addresses for an account or contact.  |
|[Award](Award.cdm.json)|An Award represents the total amount of funding that has been agreed to be awarded to an individual or institution.  |
|[AwardVersion](AwardVersion.cdm.json)|An Award Version represents a point in time snapshot of the attributes of an Award.  |
|[Budget](Budget.cdm.json)|A Budget represents the amount of funds that can be awarded for a particular delivery framework (i.e Program, Project, Initiative, Activity) for a defined period of time (i.e. fiscal year).  |
|[Campaign](Campaign.cdm.json)|Container for campaign activities and responses, sales literature, products, and lists to create, plan, execute, and track the results of a specific marketing campaign through its life.  |
|[Contact](Contact.cdm.json)|Person with whom a business unit has a relationship, such as customer, supplier, and colleague.  |
|[CreditPlan](CreditPlan.cdm.json)|Credit Plans control who will be credited with hard or soft credits after a payment clears.  |
|[CreditRecipient](CreditRecipient.cdm.json)|The contact, donor, or constituent who receives "credit" for the hard or soft cleared payment. A credit plan is always tied to a recipient in order to ensure full reconciliation and accounting of donations. All nonprofits have business rules that govern how hard and soft credits are applied, but these rules are notoriously inconsistent from organization to organization. For example, we recently surveyed 12 enterprise nonprofits about how they handle third-party (corporate) giving crediting. Of those organizations, half of them soft credit the corporation and hard credit the individual donors, and the other half hard credit the third-party organization that provides the matching gift payments. (For example, Benevity is a third-party gift-management company.) Still other organizations hard credit the corporations themselves. For example, Jane Smith works at Microsoft and donates $50 through that company. Microsoft matches the gift dollar for dollar, but Benevity collects and distributes the gift to Oxfam International. Where is hard and soft credit applied? Some organizations hard credit Jane Smith $100 ($50 donated plus the $50 match). Other organizations hard credit Jane Smith $50 and Microsoft $50. Some organizations hard credit Microsoft $100. Still more organizations hard credit Benevity some or all of the $100 donation.  |
|[DeliveryFramework](DeliveryFramework.cdm.json)|Delivery Framework represents a management unit of work defined by the organization or entity doing the work. In IATI, the Delivery Framework is an 'Activity.'  |
|[DesignatedCredit](DesignatedCredit.cdm.json)|A segment of a donation payment or in-kind gift that indicates the partial amount that is hard- or soft-credited to a Customer and allocated to one Designation.  |
|[Designation](Designation.cdm.json)|An area to which funds may be allocated, including a GL-relevant accounting code.  Designations are the way a donor instructs an organization about how their donation should be spent or earmarked.  |
|[DesignationPlan](DesignationPlan.cdm.json)|A line item attached to a Pledge, Payment Schedule, or Campaign indicating how associated payments should be designated.  |
|[Disbursement](Disbursement.cdm.json)|A Disbursement represents an Award disbursement to an individual or organizational awardee.  A Disbursement is related to a specific Award and Budget.  |
|[DisbursementDistribution](DisbursementDistribution.cdm.json)|Disbursement Distribution represents the Framework(s) - i.e. Program, Project, Initiative - that contribute to funding an Award Disbursement.  |
|[Docket](Docket.cdm.json)|A Docket is used to group inquiries (LOIs) and/or requests with a specific grant/award cycle or date (usually a review/board meeting).  |
|[DonorCommitment](DonorCommitment.cdm.json)|Donor commitments represent the actual or prospective agreement between a donor and an organization for the donor to make a gift to the organization.  |
|[Education](Education.cdm.json)|Education references biographical information about the educational institutions a contact attended or is attending.  |
|[EmploymentHistory](EmploymentHistory.cdm.json)|Employment History represents historical and/or current information about where a contact works, volunteers or serves in some capacity at an organization.  |
|[Indicator](Indicator.cdm.json)|An Indicator describes what will be measured to track evidence of a Result. Indicators can be qualitative or quantitative and may or may not be aggregable.  |
|[IndicatorValue](IndicatorValue.cdm.json)|An Indicator Value is a quantitative or qualitative value of measurement of an Indicator. Indicator Values may be but are not limited to baseline, target or actual values of measurement.  |
|[Lead](Lead.cdm.json)|Prospect or potential sales opportunity. Leads are converted into accounts, contacts, or opportunities when they are qualified. Otherwise, they are deleted or archived.  |
|[Objective](Objective.cdm.json)|An Objective represents the organization's highest priorities, strategies and/or goals that guide investments (in the case of Requests and Awards) and program delivery.  |
|[OfacMatch](OfacMatch.cdm.json)|OFAC Match is a placeholder entity for tracking Office of Foreign Assets Control (OFAC) Specially Designated Naturals (SDN) searches and results.  |
|[Opportunity](Opportunity.cdm.json)|Potential revenue-generating event, or sale to an account, which needs to be tracked through a sales process to completion.  |
|[PaymentAsset](PaymentAsset.cdm.json)|Payment Asset represents the assets associated with specific types of payments including, but not limited to, in-kind gifts, stocks and securities.  |
|[PaymentMethod](PaymentMethod.cdm.json)|Payment Method is a placeholder entity for customizations that may be supported by an application.  |
|[PaymentProcessor](PaymentProcessor.cdm.json)|This is a placeholder entity referenced by the Payment Method object.  It is intended to be customized with configuration data necessary to connect to a payment processor and authorize payments.  |
|[PaymentSchedule](PaymentSchedule.cdm.json)|A gift transaction can be a one-time payment or a recurring payment (ie, monthly/sustainer giving). In addition, it can be a pledge (ie, promise) of a future payment or a current/received payment.  |
|[PlannedGiving](PlannedGiving.cdm.json)|A planned gift is a gift made during a donor's lifetime or at the time of their death that involves their estate and/or tax planning.  |
|[Preference](Preference.cdm.json)|Preference represents an abundance of constituent or organization information that doesn't live cleanly on an account or contact record, or that can be associated with both an Account and a Contact.  |
|[Recommendation](Recommendation.cdm.json)|This is the mechanism through which Foundations provide recommendations back to a grant applicant.  |
|[Report](Report.cdm.json)|Reports represent information submitted by an awardee to the awarding entity (i.e., a Foundation) or information submitted by an authorized awarding entity individual/entity about an awardee.  |
|[Request](Request.cdm.json)|Requests represent a request from an individual or institution for funding or support. A request is more formal than an inquiry (LOI) and typically happens after an inquiry has already occurred.  |
|[Result](Result.cdm.json)|A Result is a container that represents the changes in the context in which an organization operates.  |
|[Review](Review.cdm.json)|The assessment of a Request made by an internal staff member (or team) or an external third party individual or entity (i.e. Consultant) and all of the relevant information that needs to be tracked.  |
|[Salutation](Salutation.cdm.json)|A Salutation represents the way a constituent wishes to be addressed, depending on the source, purpose and content of a of communication.  Salutations may or may not be auto-created by workflow.  |
|[Transaction](Transaction.cdm.json)|Transactions (also referred to as donations) represent payments from a constituent (i.e. donor, contact, account or organization) to the nonprofit.  |
