# OpenAIo1ModelsTest

C# Repository that will:
* Use OpenAI o1 reasoning to compare 2 Microsoft 10-K SEC reports
  * 2023:  https://www.sec.gov/Archives/edgar/data/789019/000095017023035122/msft-20230630.htm#item_1a_risk_factors 
  * 2024:  https://www.sec.gov/Archives/edgar/data/789019/000095017024087843/msft-20240630.htm#item_1a_risk_factors 
* Extract the differences, changes in the "Strategic and Competitive Risks" section
* Use OpenAI GPT-4o-2024-08-06 to create a formatted Markdown table of risks
  * File Created: https://github.com/bartczernicki/OpenAIo1ModelsTest/blob/master/OpenAIo1ModelsTest/Output/MicrosoftRiskAnalysis.md  

TODO: Add all risk sections from SEC Report

Here is a comparison of the **"Strategic and Competitive Risks"** risk factors from Microsoft's 2023 and 2024 10K filings:

| Row | Title                                                          | 2023 Summary                                                                                                                                                                                                                                                                                                                       | 2024 Summary                                                                                                                                                                                                                                                                                                                                             | Change                                                                                                     |
|-----|----------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| 1   | Competition in the technology sector                           | Competitors of varying sizes compete with us in rapidly evolving markets with low barriers to entry. Our ability to remain competitive depends on our success in creating innovative products, devices, and services that appeal to businesses and consumers.                                                                       | Similar content with added emphasis on the adverse effects if we fail to innovate and provide appealing products, devices, and services, which could negatively impact our business, financial condition, and results of operations.                                                                                 | Minor wording changes; added emphasis on potential adverse impacts if we fail to innovate.                 |
| 2   | Competition among platform-based ecosystems                    | Our business model relies on creating platform-based ecosystems. We face significant competition from firms providing competing platforms, which may affect our ability to establish market scale and maintain attractive margins.                                                                                                 | Content remains similar, emphasizing the importance of establishing significant market scale and the challenges posed by competing platforms in maintaining margins.                                                                                                                                               | Minor wording changes; overall risk factor remains consistent.                                             |
| 3   | Competing vertically-integrated models                         | Competitors using vertically integrated models (controlling software and hardware) have succeeded in consumer products like PCs, tablets, phones, gaming consoles, and wearables. Shifting to this model may increase our cost of revenue and reduce our operating margins.                                                        | Similar content, noting that competitors pursuing vertically integrated models may claim security and performance benefits. Shifting to this model may increase our cost of revenue and reduce operating margins.                                                                                                  | Minor wording changes; device examples updated (e.g., "phones" changed to "smartphones").                  |
| 4   | Competition from alternative operating systems                 | We derive substantial revenue from Windows OS on PCs but face significant competition from platforms developed for smartphones and tablets. Users are increasingly using these devices for functions previously performed by PCs, which may decrease our OS margins and affect developer interest in our platform.                  | Content is similar, acknowledging competition from platforms for smartphones and tablets. The prevalence of these devices may make it harder to attract developers, potentially decreasing OS margins and affecting our platform's competitiveness.                                                                  | Minor wording changes; content remains substantially the same.                                             |
| 5   | Competition in content and application marketplaces            | Competing platforms have large content and application marketplaces, influencing device purchasing decisions. To compete, we must attract developers to create high-quality, secure, and appealing applications for our platform, which may increase our cost of revenue and lower operating margins.                               | Similar content emphasizing the importance of attracting developers and the challenges posed by competitors' content and application marketplaces. Competitors' rules may restrict our ability to distribute products and services according to our objectives.                                                       | Minor wording changes; overall risk factor remains consistent.                                             |
| 6   | Business model competition                                     | Companies compete with us using various business models, including: transitioning to cloud-based services; investing in AI across the company; offering free applications funded by advertising; and distributing open source software at little or no cost, which may mimic our products.                                         | Similar content with additional emphasis on AI competition. Notably, new competitors are entering the AI market, and we must respond to technological changes, potential regulatory developments, and public scrutiny. We bear significant costs to build AI models and infrastructure to meet customer needs.          | Modified risk factor; added emphasis on AI competition, new market entrants, and associated challenges.     |
| 7   | Competitive pressures affecting financial results              | Competitive pressures may cause decreased sales volumes, price reductions, and increased operating costs, potentially leading to lower revenue, gross margins, and operating income.                                                                                                                                                | Similar content noting that competitive pressures may adversely affect our financial condition and results of operations due to decreased sales volumes, price reductions, and increased operating costs like R&D, marketing, and sales incentives.                                                                   | Minor wording changes; updated to reflect potential adverse effects on financial condition and results.    |
| 8   | Risks in cloud-based and AI services execution                 | Our increasing focus on cloud-based services presents execution and competitive risks. We are investing significantly in cloud infrastructure, which may reduce operating margins. Success depends on execution in areas like market adoption, device compatibility, developer engagement, reliability, security, and platform agnosticism. | Heading updated to include AI services. Emphasizes significant costs to build and maintain infrastructure for cloud computing and AI services, which will reduce operating margins. Success depends on execution in similar areas, with added focus on AI experiences and responsiveness to customer needs.             | Modified risk factor; added emphasis on AI services and associated execution and competitive risks.         |
| 9   | Misuse of AI systems and abusive activities by users           | Users may engage in fraudulent or abusive activities through our cloud-based services, such as unauthorized account use, payment fraud, or terms of service violations like cryptocurrency mining or launching cyberattacks. Ineffective detection may lead to adverse revenue impacts or reputational damage.                      | Added concerns about misuse of AI systems, noting that users may use AI tools in unintended or inappropriate ways. While committed to detecting and controlling misuse, efforts may not be effective, potentially leading to reputational damage or adverse impacts on business and results of operations.                 | Modified risk factor; added risk of AI systems being misused and the potential for reputational damage.     |
