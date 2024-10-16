# OpenAIo1ModelsTest

C# Repository that will:
* Use OpenAI o1 reasoning to compare 2 Microsoft 10-K SEC reports
  * 2023:  https://www.sec.gov/Archives/edgar/data/789019/000095017023035122/msft-20230630.htm#item_1a_risk_factors 
  * 2024:  https://www.sec.gov/Archives/edgar/data/789019/000095017024087843/msft-20240630.htm#item_1a_risk_factors 
* Extract the differences, changes in the "Strategic and Competitive Risks" section
* Use OpenAI GPT-4o-2024-08-06 to create a formatted Markdown table of risks
  * File Created: https://github.com/bartczernicki/OpenAIo1ModelsTest/blob/master/OpenAIo1ModelsTest/Output/MicrosoftRiskAnalysis.md  

TODO: Add all risk sections from SEC Report

**Consolidated Important Risk Factor Changes in Microsoft's 2024 10-K Filing**

| No. | Title                                                                                                                                                          | Description of Change                                                                                                                                                                                                                                                       | Impact                                                                                                                                                                                                                                     |
|-----|----------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1   | **Security of our information technology**                                                                                                                     | Added disclosure of a specific cyber incident involving unauthorized access by a nation-state actor, detailing potential impacts on reputation and customer relationships.                                                                                                   | Highlights increased cybersecurity risks and potential reputational damage.                                                                                                                                                                |
| 2   | **Security of our products, services, devices, and customers’ data**                                                                                           | Referenced the specific cyber incident affecting customers, emphasizing that attacks on Microsoft's IT infrastructure have directly impacted customers and may do so in the future.                                                                                          | Underlines direct impact on customers due to security breaches, increasing concerns over product security.                                                                                                                                  |
| 4   | **Disclosure and misuse of personal data could result in liability and harm our reputation**                                                                   | Included risks related to insider threats and misuse of systems, acknowledging potential failure to identify or mitigate insider activities leading to data misuse.                                                                                                          | Recognizes insider threats as a significant risk factor, potentially leading to legal liabilities and reputational harm.                                                                                                                   |
| 8   | **Our products and services, how they are used by customers, and how third-party products and services interact with them, may present security, privacy, and execution risks** | Broadened the scope from IoT to include wider product usage by customers and third parties, introducing risks related to AI products, customer use, and third-party interactions.                                                                                            | Expands risk considerations to include AI and broader product interactions, highlighting new potential vulnerabilities and compliance challenges.                                                                                           |
| 9   | **Issues in the development and use of AI may result in reputational or competitive harm or liability**                                                        | Expanded to include specific regulatory developments and legal risks related to AI, mentioning new legislation and regulations such as the European Union's AI Act and the U.S.'s AI Executive Order.                                                                        | Emphasizes increasing legal and regulatory scrutiny over AI, posing new risks to operations and compliance.                                                                                                                                 |
| 6   | **Business model competition**                                                                                                                                 | Added emphasis on AI competition, noting new market entrants and associated challenges; highlighted significant costs to build AI models and infrastructure to meet customer needs.                                                                                         | Highlights heightened competition in AI, requiring substantial investment and posing risks if the company fails to keep pace.                                                                                                              |
| 8   | **Risks in cloud-based and AI services execution**                                                                                                             | Added focus on AI services and associated execution and competitive risks; emphasized significant costs to build and maintain infrastructure for cloud computing and AI services, which could reduce operating margins.                                                     | Points to financial risks associated with heavy investment in AI and cloud infrastructure, and execution risks in rapidly evolving markets.                                                                                                |
| 9   | **Misuse of AI systems and abusive activities by users**                                                                                                       | Introduced risks of AI systems being misused in unintended or inappropriate ways by users, potentially leading to reputational damage or adverse impacts on business and results of operations.                                                                             | Identifies new risks associated with AI misuse by users, which could harm reputation and operations.                                                                                                                                        |
| 2   | **Risks related to acquisitions, joint ventures, and strategic alliances**                                                                                     | Updated to reflect the completion of the Activision Blizzard acquisition; added risk about limited ability to control or influence third parties; mentioned potential for acquisitions to be challenged post-completion, specifically noting ongoing regulatory challenges. | Acknowledges legal and regulatory risks even after acquisition completion, which could impact business, operations, and financial condition.                                                                                                |



