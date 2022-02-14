# Managing Cloud Computing Security & Risk

* Objectives
  * the implucations of cloud on governance, with a focus on contracts and controls.
  * how cloud affects enterprise risk management.
  * some top-level legal areas cloud tends to affect (but not leval advice)
  * managing compliance and audits for cloud deployments
  * tools from the Cloud Security Alliance to help asses and manage risk.

## Governance

1. Governance
   1. Enterprise risk management
      1. Information rick management
         1. information security


### Tools for cloud governance

1. Contracts
   1. The key to for governance.
   2. Contract defines the relationship between provider and customer;
      1. Terms of service
      2. scope
   3. breaches
      1. how to govern with that cloud provider
2. Supplier assessments
3. Compliance reporting

### From governance to risk

1. Governance
2. Risk tolerance
3. Supplier assessment
4. Contracts
5. Shared responsibilities model
6. Risk Management

### Conclusion

1. Governance defines how an organization is managed
2. contracts can extend governance and internal constrols to the cloud provider
3. the contract helps define the roles of the shared responsibilities model
4. supplier assessments and compliance reports help validate that the cloud provider is meeting the expections of the cloud consumer.


## Managing Cloud Security Risk

### Risk Management

* Enterprise risk management
  * rooted in providing value to stakeholders
  * how to measure, manage, and mitigate uncertainty
* Information risk management
  * aligning risk management to the tolerance of the data owner
  * primary means of decision support for IT/security on the CIA (= audit = non-repudiation) of information assets.

### Service model effects, what are the risks in each service cloud model.

* IaaS
  * Closest to traditional data center
  * most existing risk controls/activities will transfer
  * key differences are metastructure/management place and abstractions/orchestration
* PaaS
  * less likely to have fully negotiated contract
  * may be difficult to measure contract compliance (SLAs)
  * much comes down to the details of the PaaS and how to integrate
* SaaS
  * nearly fully reliant on the contract to define governance;risk since you rely on the provider for nearly everything
  * big variation in maturity in the market
  * often limited to what you see in the UI

### Deployment model effects

* public cloud environment
  * reduce ability to govern OPS
  * reduced ability to negotiate contracts
  * shared responsibilities model
* private cloud environment
  * governance/risk issues may be similar to public if third-party managed-hosted
  * provider may not negotiate contracts once terms set; e.g. won't patch in timely manner
  * internal SLAs still used in private
* community/hybrid environment
  * now have to calculate across 2 sets of contracts
  * or are dealing with group-negotiated contract and potential of differing priorities

### tradeoff considerations

* less
  * physical control over assets
  * need to manage risks the provider accepts
* more
  * reliance on SLA and contract
  * requirement to manage the relationship and stay up to date
  * assessment instead of testing

### Cloud Risk Management Tools

* Request documentation
* Review security program
* Review legal, regulatory, industry, contract obligations
* Evaluate service based on context of information assets involved
* Evaluate provider (finances, reputation, insurers, outsources)

### Recommendation about Governance and Risk

* Identify the shared responsibilities of security and risk management based on the chosen cloud deployment and service model
* Develop a cloud governance framework/model as per relevant industry best practices, global standards, and regulations like CSA CCM, COBIT 5, NIST RMF, ISO/IEC 27017, HIPAA, PCI DSS, EU GDPR.
* Understand how a contract impacts your governance framework/model
  * obtain and review contracts (and any referenced documents) before entering into an agreement
  * don't assume that you can effectively negotiate contracts with a cloud provider -but this also shouldn't necessarily stop you from using that provider
  * if a contract can't be effectively negotiated and you perceive an unacceptable risk, consider alternate mechanisms to manage that risk (e.g. monitoring or encryption)
* develop a process for cloud provider assessments. This should include:
  * contract review
  * self-reported compliance review
  * documentation and policies
  * available audits and assessments
  * service reviews adapting to the customer's requirements
  * strong change-management policies to monitor changes in the organization's use of the cloud services
* Cloud provider re-assesments should occur on a scheduled basis and be automated if possible.
* Cloud provider should offer easy access to documentation and reports needed by cloud prospects for assessments
  * for example, he CSA STAR registry
* Align risk requirements to the specific assets involved and the risk tolerance for those assets.
* Create a specific risk management and risk acceptance/mitigation methodology to assess the risks of every solution in the space
* Use controls to manage residual risks
  * if residual risks remain, choose to accept or avoid the risks
* use tooling to track approved providers based on asset type (e.g. linked to data classification), cloud usage, and management.

#### More

* Identify the shared responsibilities of security and risk management based on the chosen cloud deployment and service model
* develop a cloud governance framework/model as per relevant industry best practices, global standards, and regulations like CSA CCM, COBIT 5, NIST RMF, ISO/IEC 27017, HIPAA, PCI DSS, EU GDPR, etc.
* Understand how a contract impacts your governance framework/model
  * obtain adn review contracts (and any referenced documents) before entering into an agreement.
  * don't assume that you can effectively negotiate contracts with a cloud provider -but this also shouldn't necessarily stop you from using that provider
  * if a contract can't be effectively negotiated and you perceive an unacceptable risk, consider alternate mechanisms to manage that risk (e.g., monitoring or encryption)


### Conclusion

1. Enterprise risk management includes all-risk management for the entire organization
2. Information risk management focuses on the risk to information, and must still align with the risk tolerance of the data owner
3. The effort in a risk assessment should align with the value of the data. Just because something is moving to the cloud doesn't mean you now need to treat it as being higher-value
4. In terms of risk, like security, IaaS is most closely aligned to traditional infrastructure, while with SaaS there is a greater reliance on the cloud provider
5. Risks in private cloud may be similar to that of public cloud if the private cloud is hosted and/or managed by a third party.

## Compliance

* Obligations arise from multiple sources
  * legislation
  * contracts
  * industry-specific regulation
  * broad-based regulation

* Compliance and audits
  * Compliance validates awareness of and adherence to corporate obligations
  * audits are a key tool for proving (or disproving) compliance

### How cloud chances compliance**

* The cloud customer is always responsible for compliance but may now also rely on the provider
* Cloud customers will rely more on third-party assessments
* The cloud management plane / metastructure may span jurisdictions, while the data/assets don't; this must be integrated into compliance activities
* not all cloud providers are equal with regards to compliance, and not all services from a single provider are always within the same audit / attestation / certification scope.

### Compliance Inheritance

The customer is responsible for the app that is deployed. So compliance inheritance is not true, but there're auditable scopes.

### Recommendations

* Compliance, audit, and assurance should be continuous.
  * they should not be seen as merely point-in-time activities, and many standards and regulations are moving more towards this model. This is especially true in cloud computing, where both the provider & customer tend to be in more constant flux and are rarely ever in a static state
* cloud providers should clearly communicate their audit results, certifications, and attestations, with particular attention to:
  * the scope of assessments
  * which specific features/services are covered in which locations and jurisdictions
  * how customer can deploy compliant applications and services on the cloud
  * any additional customer responsibilities and limitations
* Cloud providers must maintain their certifications/attestations over time and proactively communicate any changes in status
* Cloud providers should engage in continuous compliance initiatives to avoid creating any gaps, and thus exposures, for their customers
* Provide customers commonly needed evidences and artifacts of compliance, such as logs of administrative activity the customer cannot otherwise collect on their own.
* Cloud customers should:
  * understand their full compliance obligations before deploying, migrating to, or developing in the cloud
  * evaluate a provider's 3rd-party attestations and certifications and align those to compliance needs
  * understand the scope of assessments and certifications, including both the controls and the features/services covered.
  * Ensure they understand what artifacts of compliance the provider offers, and effectively collect and manage those artifacts.
  * Create and collect their own artifacts when the provider's artifacts are not sufficient
* Keep a register of cloud providers used, relevant compliance requirements, and current status. The CSA Cloud Controls Matrix can support this activity.

### Conclusion

1. Compliance is a tool to ensure organizations are meeting corporate obligations
2. Audits are how we validate compliance, and they can be performed internally or externally using third parties
3. Cloud changes compliance because it now becomes a shared responsibility between the cloud consumer and the provider
4. Compliance inheritance is the principle that if a cloud provider's service is compliant with a regulation / standard, then cloud consumers can build compliant services / applications using that service. But it does not guarantee compliance since the cloud consumer can still build a non-compliant application on top of a compliant service.

## Legal Considerations for Cloud

Is the applicable law where your business resides, where the data resides, or where the customer resides?

### APAC - Australia

* Privacy Act of 1988
  * 13 Australian Privacy Principles (APPs)
  * Applies to private, not-for-profits with 3+ million AUD, private healthcare providers
* Australian Consumer Law (ACL)
* Entities must provide notification when breaches occur
* ACL protects against false/misleading contracts and failed breach notification
* Privacy Act applies to Australian customers even if CSP is based elsewhere

### APAC - China

* 2017 Cyber Security Law governs network operators
  * Data localization requires certain data is stored in the country
* Privacy landscape still in transition

### APAC - Japan

* Act on Protection of Personal Information (APPI) requires private sector to protect personal information
* Prior consent required for data transferred to 3rd party outside the country
* Consent is not required if certain standards are met as outlined by the Personal Information Protection Commission

### APAC - Russia

* Russian data protection laws require consent for most data processing
* Companies are required to store personal data of Russian citizens within Russia

### EMEA - European Union & European Economic Area

* 2018 General Data Protection Regulation (GDPR)
  * member states can supplement the GDPR
* 2002 Directive on Privacy and Electronic Communications (new E-Privacy Regulation to replace it)
* Network Information Security Directive (NIS Directive)
  * Protects critical Infrastructure and essential services

### General Data Protection Regulation (GDPR)
* Applicability
  * Applies to data controllers / processors in the EU/EEA, or activities within and ouside the EU/EEA
  * Applies to controllers/processors outside the EU/EEA if monitoring or processing data owned by an individual in the EU/EEA
* Accountability Obligations
  * Entities must keep records of data processing activities
  * Must develop and operate according to "privacy by design" and "privacy by default" principles
* Data Subjects' Rights
  * subjects have a right to know what info an entity has about them
  * right to object to how personal data is used
  * right to data erasure/corrections
  * right to be forgotten
* Cross-border data transfer restrictions
  * personal data cannot transfer across borders unless a country has similar data and privacy rights
  * entities outside of the EU/EEA must show an adequate level of protections
* Breaches of security
  * Entities must report a security breach to the Supervisory Authority or Authorities and data subjects when the breach meets certain thresholds
* Sanctions
  * Violators are subject to sanctions, up to 4% of global gross income, or up to EUR 20 million.

### Network Information Security Directive (NIS)

* Requires that EU/EEA member states' laws govern network and information security requirements for digital and essential services: i.e., e-commerce, search engines, cloud computing.
* Providers outside the EU offering services inside the EU are accountable
* Providers must notify agencies if an incident substantially impacts the provision of a service

### EMEA - Countries outside EU/EEA

* Countries with similar protection laws such as GDPR or 1995 EU Data Protection Directive: Dubai, Israel, Morocco, Senegal, South America, Qatar.

### AMERICAS - Central & South

* Argentina, Chile, Colombia, Mexico, Peru, and Uruguay have laws inspired mainly by the European directive 95/46/EC
* Many laws refer to the APEC Privacy Framework

### AMERICAS - Canada

* Personal Information Protection and Electronic Document Act (PIPEDA)
* Applies to entities subject to federal jurisdiction and all provincial jurisdictions

### AMERICAS - US

* No single national law for data protection and regulation
* US Federal Laws
  * Among other, Gramm-Leach-Billey Act (GLBA), Accountability Act of 1996 (HIPAA), Children's Online Privacy Protection Act of 1998 (COPPA) all regulate privacy and information security
  * Companies must adopt reasonable security measures around personal data
  * organizations are responsible for subcontractors' actions
* US State Laws
  * State laws around data security apply to any entity that collects/processes data of an individual living in that state, regardless of where data is stored.
  * most state laws that address information security require a written contract between the entity and the service provider mandating use of reasonable security measures.
* Laws, agencies and litigation
  * breaches of security
    * private or gov't entities must notify individuals of security breaches
  * privacy laws
    * california consumer privacy act (CCPA) protects data for individuals, families and devices. In effect Jan. 2020 - significant implications.
  * Federal and State Agencies
    * Federal Trade Commission (FTC) and State attorneys general also enforce accountability in entities around privacy and security practices. These decrees give guidance around protection of personal information.
  * Litigation and E-Discovery
    * Litigation in the US differs from other countries
    * each party can obtain documents through "discovery"
    * discovery is complex when documents are hosted in the cloud due data dispersion
    * cloud will become the repository of most electronically stored information
    * providers and their clients must plan how to identify all documents

### industry standards

* create by private organizations, industry standards are not laws
* many industry standards related to the cloud are produced by these organizations: OASIS, ETSI, IEEE, ISO, IEC, ITU, NIST.

### Contracts

* before entering negotiations
  * due diligence of your own entity
  * due diligence of other party
    * does the service allow your company to meet its objectives and still be in compliance?   
* contract terms
  * pricing
  * allocation of risk/responsibility
  * termination
  * representation and warranties
  * data/ip ownership
  * data location
  * service level agreement (SLA)
  * privacy/privacy level agreement (PLA)
* during performance
  * monitoring
  * preparing for termination and transition
  * unintended contract
  * closing

### Conclusion

Due to the nature of the cloud, it has become easy to transfer data across the globe. However, the ease of movement of the data makes it susceptible to be caught under numerous legal systems. It is therefore important to appreciate the wide variety - as well as the amazing similarities - between the laws that govern cloud services.

Global trends
* protection of privacy and allowing individuals to have some control over the collection and use of their personal data
* there is a concern for the security of personal data nad company data. A significant number of laws require the adoption of formal security policies.
* Countries ans states are recognizing that security breach occurs, for a variety of reasons - state actors, hackers, disgruntled employees, negligence or inadvertent error. These breaches should be notified to be affected parties. Numerous new laws require prompt disclosures to individuals and government agencies.
* There is a concern that data laws many not be equivalent from state to state and countries are establishing barriers to prevent the transfer of data to those that do not offer "adequate protection"
* finally like for any other relationship, thins are better recorded in writing. Contracts are important. Cloud contact can be tricky because too easy to sign when they are just posted on a website for the customer to click on "I agree". Make sure you read them carefully to understand the terms.

## Audit

* Different types of audit / assessment / attestation have different focuses and vary across providers
* Attestations are legal statements and providers may be required by the auditor to have an NDA with the customer before releasing
* Customers will likely be limited in their ability to assess (and vulnerability assess) providers. These could be a security risk to the provider
* Cloud providers should have a rigorous portfolio of compliance attestations to support their customers

### Previous audit results (3 rd-party attestations)

Be aware of when the audit was performed, the scope of the audit, and the audit results;

* Be careful relying on provider's previous audits
  * audits are based on standards and best practices (ISO 27017/27001, CCM, FISMA, FEDRAMP, C5, MTCS)
  * audits are great tools, but depending on the scope, might not be relevant to you
  * don't assume a given standard is included in a statement of applicability - controls are limited
  * details of compliance audits are not available to you the customer
  * audits are done at a given point in time - don't assume same security controls are current

### artifacts of compliance

* policy and procedure documentation
* audit logs
* activity reporting
* system configuration details


* in cloud, assessing risk is collecting all audit evidence and can be challenging
* understand requirements for logging and what kinds of data to collect
* change in management logs are common artifacts you need
* map what you need to your cloud provider
* collect admin activity to have logs of changes
* store artifacts in a central repository. Build architecture to store centrally
* Key places to focus on:
  * management place
  * configuration pieces
  * adding more logging in applications
  * system logs need to be pushed to a different location, ex: object storage on cloud provider

### Core of audit considerations
* make sure you know what you need to collect to meet compliance obligations
* evaluate what you can get from your cloud provider and how to get it
* store in a central location
* build in extra logging to compensate for places where you lose visibility

### Assessment frequency

* due to the evolving nature of a cloud service, more frequent assessment is required
* Consider STAR / CAIQ / CCM / and others CSA tools and programs

### Conclusion

* different types of audits and assessments have different focuses, and even when the same name is used can have different focus and scope across cloud providers
* cloud providers often limit the kinds of assessments their customers can use since some of these, like vulnerability assessments, can't be distinguished from real attacks without being constrained
* ensure you know the scope, results, and timing (date) of previous audits. Not all audits on a provider's website are necessarily up to date or cover the service under consideration
* cloud consumers are responsible for maintaining their own artifacts of compliance for their own audits, such as log files

## CSA Tools

### CCM Cloud Control Matrix

It is a controls framework for organizations to operate securely when cloud services are utilized.

* Intended for cloud providers, SaaS providers, other end-user services in the cloud
* Designed by SMEs across industries
* Providers security principles to providers to define and apply best practices
* Assists customers to assess cloud providers
* Standardized guidance on control objectives in cloud-based IT systems
* based on CSA Security Guidance, research artifacts, mobile WG
* Addresses intra- and inter-org challenges by delineating control ownership
* Normalizes security expectations, cloud taxonomy, and security measures implemented in cloud supply chain
* guides security efforts in vetting cloud providers, building proposal requests and operational risk assessment
* Aids in internal and external assessments and audits, and can submit to CSA Star registry

### CAIQ Consensus Assessments Initiative Questionnaire

It assess the security postures of a cloud service provider

* originated in the CSA Consensus Assessments initiative WG
* CAIQ is a simplified distillation of issues and control specs associated with cloud security
* simple tool to standardize approach of validation of a cloud providers security postures
* companion to CSA security guidance and CCM
* helps cloud SP's assess security postures, provides single location for details about their information security program
* streamlines compliance assessments and improves communication between cloud SPs, business partners, and customers
* allows customers and auditors to ask the right questions of cloud provider about their security posture
* consumers can use completed CAIQs to assess provider control and risk models
* helps organizations build assessment processes prior and during to engagement with cloud provider

### STAR Security, Trust And Assurance Registry

It promotes security governance, assurance, and compliance in the cloud

* based on CSA OCF, CCM, and CAIQ WGs
* 3rd party resources that encompasses key principles of transparency, auditing and standards harmonization
* initially launched in 2010, STAR addresses lack of transparency in a burgeoning market
* supports cloud customers in evaluation and selection process, and helps cloud SPs to easily communicate security posture to their customers
* offers self-assessment, 3rd-party certification, and continuous auditing
* increases security by requesting adherence to best practices by implement CCM
* details security postures of security providers, offers assurance by indicating level of compliance of CSA best practices
* offers layered approach to cloud assurance: self-assessment, 3rs-party certification and attestation, and continuous auditing
* customer can access security documentation for cloud providers from a single trusted repository
* 

### STARWatch

It is an SaaS application to help cloud providers manage compliance with CSA Star requirements

* STARWatch grew out of CSA's desires to manage CAIQ responses more effectively
* facilities adoption and implementation of CCM and CAIQ and streamlines provider and consumer compliance efforts
* allows users to create, edit, import, and export CAIQs
* intended for users of cloud services, cloud SPs, IT auditors, security solution providers and consultants
* provides multi-user access to CCM and CAIQ in database format
* incorporates a maturity model to measure the evolution of security posture of the org
* assistance in mapping security requirements to those of CSA
* relevant mapping to relevant standards / regs

### Conclusion

* the cloud controls matrix is a list of cloud security controls mapped by domain and aligned to various regulatory frameworks
* the ccm is an excellent tool for evaluating your cloud security controls and is useful to both cloud providers and consumers
* the consensus assessment initiative questionnaire is a standard set of security questions for cloud providers. It allows cloud consumers to directly compare providers, and allows providers to reduce the need to respond to non-standard RFPs
* the cloud security alliance guidance (which this training is based on) tells you how to implement your controls, while the CCM tells you which controls to implement
* the star registry and StarWatch tool serve as central repositories for cloud provider security documentation, including the CAIQ