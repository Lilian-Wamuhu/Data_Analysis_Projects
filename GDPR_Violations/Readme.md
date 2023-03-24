# GDPR VIOLATIONS ( TACKLING PRIVACY IN THE NEW INFORMATION AGE)

<img src="https://www.cookielawinfo.com/wp-content/uploads/2019/12/GDPR-Fines-Biggest-GDPR-Violation-Examples.jpeg">

Given the rise in the use of data and the proliferation of companies such as Google whose business models are hinged on the value of user data, regulatory bodies have been forced to implement data protection and privacy regulations across the globe, for instance the GDPR, EU based. Locally in Kenya we have the Data Protection Act, which is based on the aforementioned.

This analysis seeks to explore GDPR violations by country and article, companies with the highest violations, and fines levied per article.

# Data Sources

The dataset used in this analysis was sourced from Tidy Tuesday and contains information on GDPR violations across European countries.

# Methodology

The analysis was conducted using Python, specifically the pandas and plotly libraries for data manipulation and visualization respectively.

# Data Exploration

## Data Protection and Privacy regulations locally and globally.

The dataset provided contains personal data of customers who made purchases from an e-commerce store. Data protection and privacy regulations are important for protecting individuals' personal information and ensuring that it is collected, processed, stored, and used in a responsible and lawful manner. 

Globally, the most well-known data protection regulation is the European Union's General Data Protection Regulation (GDPR), which came into effect in May 2018. The GDPR applies to all EU member states and regulates the collection, processing, and storage of personal data. It also gives individuals certain rights, such as the right to access their data, the right to have their data deleted, and the right to object to the processing of their data.

Other notable data protection regulations include the California Consumer Privacy Act (CCPA) in the United States, which came into effect in January 2020 and applies to businesses that collect personal information from California residents. The CCPA gives individuals the right to know what personal information is being collected about them, the right to have their personal information deleted, and the right to opt-out of the sale of their personal information.

Locally, each country or region may have its own data protection and privacy regulations. For example, in Canada, the Personal Information Protection and Electronic Documents Act (PIPEDA) sets out rules for the collection, use, and disclosure of personal information by businesses and organizations. In Australia, the Privacy Act 1988 (Cth) regulates the handling of personal information by Australian government agencies and businesses.

It is important for individuals and businesses to understand the data protection and privacy regulations that apply to them and to ensure that they comply with these regulations to avoid legal consequences and protect individuals' personal information.

## The implications of non-compliance and the core principles of the Data Protection Act

The implications of non-compliance with data protection regulations can be significant, including fines, legal action, and damage to a business's reputation. In some cases, non-compliance may also result in criminal charges, particularly in cases where there has been a serious breach of personal data.

The core principles of data protection, which are typically included in data protection laws and regulations, include:

- Lawfulness, fairness, and transparency: Personal data should be processed lawfully, fairly, and in a transparent manner. Individuals should be informed about how their data will be used and have the right to access their data.

- Purpose limitation: Personal data should only be collected and processed for specific, legitimate purposes and not used for any other purpose without the individual's consent.

- _Data minimization:_ Personal data should be limited to what is necessary for the specific purposes for which it is processed.

- _Accuracy:_ Personal data should be accurate and kept up to date.

- _Storage limitation:_ Personal data should not be stored for longer than necessary.

- _Integrity and confidentiality:_ Personal data should be kept secure and protected against unauthorized access, disclosure, or loss.

- _Accountability:_ Data controllers should be responsible for complying with data protection regulations and should be able to demonstrate their compliance.

Non-compliance with these principles can result in legal and financial consequences, as well as damage to an organization's reputation. It is therefore important for businesses and organizations to understand their obligations under data protection regulations and to take appropriate steps to ensure compliance.

**Document your understanding of challenges (Prepare a slide providing context to your potential audience) faced in Kenya when it comes to effective implementation of the DPA.**

## What businesses need to do to achieve compliance.

To achieve compliance with data protection regulations, businesses should take the following steps:

- _Understand the regulations:_ Businesses should familiarize themselves with the data protection regulations that apply to them, such as the GDPR, CCPA, PIPEDA, or Privacy Act. They should understand the obligations and requirements of these regulations and how they apply to their business.

- _Conduct a data audit:_ Businesses should conduct a thorough audit of the personal data they hold, how it is collected, processed, and stored. This will help identify any areas where compliance may be lacking.

- _Implement appropriate data protection policies:_ Businesses should develop and implement appropriate data protection policies and procedures to ensure that personal data is processed lawfully and in compliance with applicable regulations. This may include policies for data retention, data access, and data breach response.

- _Appoint a data protection officer:_ Some regulations, such as the GDPR, require businesses to appoint a Data Protection Officer (DPO) to oversee data protection and ensure compliance. Even if not required, appointing a DPO can be beneficial to ensure that data protection is taken seriously within the organization.

- _Educate employees:_ Businesses should ensure that all employees are aware of the importance of data protection and their responsibilities for compliance. This may involve training on data protection policies and procedures.

- _Implement appropriate technical and organizational measures:_ Businesses should implement appropriate technical and organizational measures to ensure the security of personal data, such as encryption, access controls, and regular backups.

- _Maintain compliance:_ Compliance with data protection regulations is an ongoing process. Businesses should regularly review their data protection policies and procedures and update them as necessary to ensure ongoing compliance.

By taking these steps, businesses can achieve compliance with data protection regulations, protect individuals' personal data, and avoid legal and financial consequences.

## Document global trends in data protection.

There are several global trends in data protection that are worth noting:

- _Strengthening of data protection laws:_ Many countries and regions are strengthening their data protection laws, with a particular focus on enhancing individuals' rights and increasing penalties for non-compliance. For example, the European Union's GDPR introduced significant changes to data protection law, and other countries have followed suit, such as Brazil with its General Data Protection Law (LGPD), and India with its Personal Data Protection Bill.

- _Increased focus on data security:_ As data breaches become more frequent and serious, there is an increased focus on data security measures. Many regulations now require businesses to implement appropriate technical and organizational measures to protect personal data, such as encryption, access controls, and regular backups.

- _Global harmonization of data protection laws:_ There is a growing trend towards global harmonization of data protection laws to facilitate international data flows while ensuring that individuals' rights are protected. The GDPR, for example, applies to all EU member states and has influenced data protection laws in other regions.

- _Emergence of privacy-enhancing technologies:_Privacy-enhancing technologies, such as blockchain and differential privacy, are being developed to enable data sharing while maintaining individuals' privacy rights. These technologies are becoming increasingly important as more data is collected and processed in the digital age.

- _Increased scrutiny of tech companies:_ Tech companies are facing increased scrutiny over their handling of personal data, with regulators and consumers demanding greater transparency and accountability. This has led to increased fines for non-compliance and reputational damage for companies that fail to protect personal data adequately.

Overall, data protection is becoming increasingly important globally, with governments and consumers alike demanding greater protection for personal data. This trend is likely to continue, with more countries strengthening their data protection laws and implementing more stringent measures to protect personal data.

## More insight.

The analysis resulted in the following insights:

**_Time breakdown of the total violations in the EU_**

>The total number of GDPR violations in the EU increased from 2018 to 2019, with the highest number of violations being recorded in Germany and the UK.

<img src="https://github.com/Lilian-Wamuhu/Data_Analysis_Projects/blob/main/GDPR_Violations/Plot/Time_Breakdown.png?raw=true">


**_Most expensive violation by country, listing the specific violation type e.g failure to comply with processing regulation._**


<img src="https://github.com/Lilian-Wamuhu/Data_Analysis_Projects/blob/main/GDPR_Violations/Plot/Most%20expensive%20violation.png?raw=true">

**_Companies with the highest violations._**

>The companies with the highest number of GDPR violations were Google, followed by a telecommunications company, a bank, and a social media company.

<img src="https://github.com/Lilian-Wamuhu/Data_Analysis_Projects/blob/main/GDPR_Violations/Plot/Companies%20with%20the%20highest%20violations.png?raw=true">

**_GDPR violations by country_**

>The highest number of GDPR violations were recorded in Germany, followed by Spain and Italy.

<img src="https://github.com/Lilian-Wamuhu/Data_Analysis_Projects/blob/main/GDPR_Violations/Plot/GDPR_violations.png?raw=true">

**_Top 10 most violated articles_**

>The most violated GDPR article was Article 32, which deals with security of processing, with a total of 40 violations.
>The top 10 most violated articles were related to data processing, data subject rights, and data breaches.

| Most Violated Articles   | no.of Violation |
| ------------- | ------------- |
| Art. 32 GDPR |  40  |
| Art. 6 GDPR  |  33 |
| Art. 5 GDPR Art. 6, GDPR  | 20  |
| Art. 15 GDPR  | 10  |
| Art. 5 GDPR  | 10 |
| Art. 5 (1) f) GDPR, Art. 32 GDPR   | 10 |
| Art. 5 (1) f), GDPR  | 7  |
| Art. 13 GDPR  | 7  |
| Art. 5 (1) a) GDPR, Art. 6 GDPR  | 6  |
| Art. 5 (1) c) GDPR  | 6  |


**_Article with the highest associated fine_**

>The most expensive GDPR violation in terms of the associated fine was related to Article 32 - Security of processing.

# Conclusion

The rise in data usage and the need for companies to protect users' privacy has necessitated the implementation of data protection and privacy regulations. This analysis has highlighted the need for companies to ensure compliance with GDPR regulations to avoid hefty fines and maintain their reputation.
