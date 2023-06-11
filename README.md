# SustainChain

![Application preview](https://github.com/ETHPrague-SustainChain/.github/assets/37782099/7426646f-9555-4de8-8bbd-0c407f898133)
SustainChain is a blockchain solution to trace and verify the sustainability credentials of products from source to consumer, promoting transparent and responsible consumption.

Solidity smart-contracts on Ethereum, React frontend on BOS provided by Near, Assembly script subgraph on The Graph. Build during [ETHPrague Hackathon](https://ethprague.com/)

### Try it out:

https://near.org/let45fc.near/widget/SustainChain

## Problem:

Current supply chain systems often lack transparency and accountability. Consumers don't have clear visibility into the sustainability practices of the products they purchase, such as whether they are made from recycled materials if they cause deforestation, or if fair labor practices are followed in their production.

## Solution:

A blockchain-powered supply chain system can offer complete transparency and traceability. Each product is assigned a unique identifier that can be tracked at every stage of its lifecycle - from the sourcing of raw materials, through the manufacturing process, and all the way to the retail shelf.

![image_2023-06-10_15-20-35](https://github.com/ETHPrague-SustainChain/.github/assets/37782099/bf4a0583-e208-4743-910c-273bcd84d0bb)
![image_2023-06-10_15-20-36 (2)](https://github.com/ETHPrague-SustainChain/.github/assets/37782099/ad6c5847-3a55-4c87-8515-5fc07a9ac410)
![image_2023-06-10_15-20-36](https://github.com/ETHPrague-SustainChain/.github/assets/37782099/c908af3c-66e6-41b0-87f4-386192c8c8ae)

# Pitch deck

https://docs.google.com/presentation/d/1_f9e4ZD3yNEJUkaiDLIt0QgKc9Ad6E3SRtJaOmy8vjM/edit?usp=sharing

# Future vision

<img width="903" alt="изображение" src="https://github.com/ETHPrague-SustainChain/.github/assets/37782099/5d41c219-5a78-4bc3-9eb2-227551a7e1c4">

The business owner can request the smart contract factory to create its own chain by deploying a subcontract.

He can add and remove admins.

He and admins can add packages records in subcontracts. Subcontracts notify the smart contract factory of what is happening in them. The database of records for all subcontracts is common and is located in the smart contract Factory.

The indexer indexes all changes in the SCFactory. This means that any user will be able to get data about any product without even accessing the blockchain.
