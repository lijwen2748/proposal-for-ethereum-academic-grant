
# An extensible and efficient verification framework for Solidity smart contracts 

## Project Abstract

Our project aims to verify the correctness of smart contracts on the Ethereum blockchain by leveraging the technique of model checking in formal verification. Specifically, we will use the ACT tool to generate formal specifications of smart contracts and use the BTOR2 format to represent these Solidity smart contracts as word-level transition systems. We will then employ the latest model-checking algorithms to verify the correctness of the input contracts, considering that BTOR2 is the generic input format for most modern word-level model checkers. Compared to previous works, the novelties of this project are as follows:

1. An automatic and complete methodology is presented to formally verify Solidity smart contracts;
2. An easily extensible framework is established to leverage most of the modern word-level model-checking engines;
3. The dedicated model-checking technique for solidity smart contracts can be fully explored based on our 10+ years of experience in model-checking-performance research. 

## Objectives

Our goal is to provide a reliable and efficient method for verifying smart contracts on the Ethereum blockchain. We will measure the success of this project by the percentage of verified smart contracts and the accuracy and efficiency of our model-checking algorithm.

## Outcomes

Our project will benefit the Ethereum ecosystem by providing a reliable and efficient method for verifying smart contracts. By ensuring the correctness of smart contracts, we can reduce the risk of security vulnerabilities and protect users' assets on the blockchain.

## Grant Scope

Our research will focus on developing and applying model-checking algorithms to verify smart contracts on the Ethereum blockchain. We will also investigate the effectiveness of the BTOR2 format in representing complex Boolean formulas and compare it with other representation formats.

## Project Team

Our project team consists of four members:

- Jianwen Li, Project Manager, Algorithm Researcher (30 hours per month)
- Yinrong Su, Smart Contract Developer (50 hours per month)
- Xudong Wang, Formal Verification Engineer (50 hours per month)

## **Background**

We will introduce our background from three aspects: limitations of prior research、advantages of BTOR2 format and our research background:

1. Prior research projects on smart contract formal verification have utilized either BMC or theorem proving, but these methods have limitations such as incompleteness or requiring significant human involvement. Therefore, it is necessary for us to develop an automated verification tool to eliminate these limitations by providing a complete and automatic verification framework for verifying the correctness of Solidity smart contracts on the Ethereum blockchain.
2. BTOR2 is an extensible input format in modern word-level model-checking tools, which can be easily combined with the latest model-checking algorithms.
3. Our team has more than ten years of verification experience, and we have a fruitful achievement in this topic. For example, we presented a new model-checking algorithm named Complementary Approximate Reachability (CAR) which is state-of-the-art. Also, SimpleCAR serves as a reference implementation for evaluating Complementary Approximate Reachability (CAR), which is particularly suited for unsafety checking, or *bug-finding.*
4. 

The paper links of CAR are as follows:

- **Safety model checking with complementary approximations**: [https://ieeexplore.ieee.org/abstract/document/8203765/](https://ieeexplore.ieee.org/abstract/document/8203765/)
- **SimpleCAR: An Efficient Bug-Finding Tool Based on Approximate Reachability:** [https://link.springer.com/chapter/10.1007/978-3-319-96142-2_5](https://link.springer.com/chapter/10.1007/978-3-319-96142-2_5)
    - **SimpleCAR tool website**: [GitHub - lijwen2748/simplecar](https://github.com/lijwen2748/simplecar)
- **Intersection and Rotation of Assumption Literals Boosts Bug-Finding:**   [https://link.springer.com/chapter/10.1007/978-3-030-41600-3_12](https://link.springer.com/chapter/10.1007/978-3-030-41600-3_12)
- **Combining BMC and Complementary Approximate Reachability to Accelerate Bug-Finding**: [https://dl.acm.org/doi/abs/10.1145/3508352.3549393](https://dl.acm.org/doi/abs/10.1145/3508352.3549393)
- **Accelerate Safety Model Checking Based on Complementary Approximate Reachability**:  [https://ieeexplore.ieee.org/document/10015642](https://ieeexplore.ieee.org/document/10015642)

## Methodology

- In the first step, we will formalize ACT and present its operational semantics, based on which we then present the transition rules from ACT to BTOR2;
- In the second step,  we will extend SimpleCAR to support BTOR2 inputs for the word-level model-checking purpose. Also, we will establish a portfolio including other state-the-art model-checking algorithms;
- In the third step, we will explore efficiently applying the proposed framework to real case studies on Solidity smart contracts.
    
    

## Timeline

Our project will be completed in 12 months, with the following milestones:

- Month 1-2: Research and development of the model-checking algorithm
- Month 3-4: Integration of BTOR2 format into the model-checking algorithm
- Month 5-6: Verification of smart contracts using the model-checking algorithm
- Month 7-8: Performance optimization of the model-checking algorithm
- Month 9-10: Comparison of the effectiveness of the BTOR2 format with other representation formats
- Month 11-12: Final testing and documentation of the project

## Budget

We are requesting a grant of $58,000, which will be used as follows:

- Principle Researchers Costs: $8,000
- Other Staff Costs: $10,000
- Hardware Costs: $10,000
- Software Costs: $10,000
- Data Collection Costs: $10,000
- Indirect Costs: $10,000

Our budget proposal includes salaries for project team members, hardware and software expenses, and other indirect costs associated with the project.
