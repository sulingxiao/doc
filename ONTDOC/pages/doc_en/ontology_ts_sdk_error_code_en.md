---
title: 
keywords: sample homepage
sidebar: ont_doc_en
permalink: ontology_ts_sdk_error_code_en.html
folder: doc_en
---

English / [中文](./ontology_ts_sdk_error_code_zh.html)


<h1 align="center">Error Code </h1>
<p align="center" class="version">Version 0.7.0 </p>

| Return Code | Description                   | Explaination                                     |
| :----       | ----------------------------- | -----------------                                |
| 0           | SUCCESS                       | Success                                          |
| 41001       | SESSION_EXPIRED               | Invalid session or timeout (need to login again) |
| 41002       | SERVICE_CEILING               | Reach the service limit                          |
| 41003       | ILLEGAL_DATAFORMAT            | Illegal data format                              |
| 42001       | INVALID_METHOD                | Invalid method                                   |
| 42002       | INVALID_PARAMS                | Invalid parameters                               |
| 42003       | INVALID_TOKEN                 | Invalid token                                    |
| 43001       | INVALID_TRANSACTION           | invalid transaction                              |
| 43002       | INVALID_ASSET                 | invalid asset                                    |
| 43003       | INVALID_BLOCK                 | invalid block                                    |
| 44001       | UNKNOWN_TRANSACTION           | Transaction not find                             |
| 44002       | UNKNOWN_ASSET                 | Asset not find                                   |
| 44003       | UNKNOWN_BLOCK                 | Block not find                                   |
| 45001       | INVALID_VERSION               | Invalid protocal version                         |
| 45002       | INTERNAL_ERROR                | Internal error                                   |
| 60000       | NETWORK_ERROR                 | Network error                                    |
| 60001       | DB_OP_ERROR                   | Database operation error                         |
| 60002       | NO_BALANCE                    | Not enough balance                               |
| 60003       | Decrypto_ERROR                | Decryption error                                 |
| 60004       | Encrypto_ERROR                | Encryption error                                 |
| 60005       | Deserialize_BLOCK_ERROR       | Block deserialization error                      |
| 60006       | Deserialize_TRANSACTION_ERROR | Transaction deserialization error                |
| 60007       | ComposeIssTransaction_ERROR   | Compose transaction Iss error             |
| 60008       | ComposeTrfTransaction_ERROR   | Compose Transaction Trf error     |
| 60009       | Signature_INCOMPLETE          | Signature incomplete                             |
| 60011       | IllegalArgument               | Illegal argument                                 |
| 60012       | IllegalAddress                | Illegal address                                  |
| 60013       | IllegalAssetId                | Illegal assert id                                |
| 60014       | IllegalAmount                 | Illegal Amount                                   |
| 60015       | IllegalTxid                   | Illegal Transaction ID                           |