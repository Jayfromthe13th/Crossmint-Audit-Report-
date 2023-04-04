# Crossmint-Audit-Report-
![Screen Shot 2023-04-04 at 5 19 30 PM](https://user-images.githubusercontent.com/83922342/229943321-9025542e-dd6f-4a2a-ae48-38a65a513f77.png)


**Summary**


This project focuses on creating a Solana-based NFT and DApp that uses CrossMint APIs for credit card and multi-cryptocurrency payment processing. During development, stress tests and other tests were conducted, revealing some issues that need to be addressed to ensure a seamless and secure user experience.

*Key Findings*

* CrossMint API stress test: The API was unable to handle a large number of simultaneous requests, resulting in transaction delays and failures.

* Insufficient rate limiting: The API is vulnerable to denial of service (DoS) attacks due to insufficient rate limiting, which can disrupt the service for legitimate users.

* NFT minting and charging despite sold-out collection: The system allowed NFT minting and credit card charging even when the NFT collection was sold out, posing a risk of overselling and customer dissatisfaction.

*Recommendations*

Optimize CrossMint API performance: Improve the API to handle a higher volume of requests and process transactions efficiently under stress.
Implement rate limiting: Protect the API against DoS attacks by implementing proper rate limiting, ensuring service stability for legitimate users.
Enforce NFT supply limits: Implement safeguards to prevent minting of NFTs and charging credit cards when a collection is sold out, ensuring a consistent and satisfying user experience.


*By addressing these issues, this project aims to provide a secure and reliable platform for users in the growing NFT and blockchain ecosystem.*
