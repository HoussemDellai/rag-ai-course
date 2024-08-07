---
title: Azure OpenAI Autogen quota
titleSuffix: Azure OpenAI Service
description: Azure OpenAI model quota
manager: nitinme
ms.service: azure-ai-openai
ms.topic: include
ms.date: 07/24/2024
---


| Region             | GPT-4   | GPT-4-32K   | GPT-4-Turbo   | GPT-4-Turbo-V   | gpt-4o      | gpt-4o - GlobalStandard   | gpt-4o-mini   | gpt-4o-mini - GlobalStandard   | GPT-35-Turbo   | GPT-35-Turbo-Instruct   | Text-Embedding-Ada-002   | text-embedding-3-small   | text-embedding-3-large   | Babbage-002   | Babbage-002 - finetune   | Davinci-002   | Davinci-002 - finetune   | GPT-35-Turbo - finetune   | GPT-35-Turbo-1106 - finetune   | GPT-4 - finetune   | GPT-35-Turbo-0125 - finetune   |
|:-------------------|:-------:|:-----------:|:-------------:|:---------------:|:-----------:|:-------------------------:|:-------------:|:------------------------------:|:--------------:|:-----------------------:|:------------------------:|:------------------------:|:------------------------:|:-------------:|:------------------------:|:-------------:|:------------------------:|:-------------------------:|:------------------------------:|:------------------:|:-------------------------------|
| australiaeast      | 40 K    | 80 K        | 80 K          | 30 K            | -           | 450 K <br> 30 M              | -             | -                              | 300 K          | -                       | 350 K                    | -                        | -                        | -             | -                        | -             | -                        | -                         | -                              | -                  | -                              |
| brazilsouth        | -       | -           | -             | -               | -           | 450 K <br> 30 M              | -             | -                              | -              | -                       | 350 K                    | -                        | -                        | -             | -                        | -             | -                        | -                         | -                              | -                  | -                              |
| canadaeast         | 40 K    | 80 K        | 80 K          | -               | -           | 450 K <br> 30 M              | -             | -                              | 300 K          | -                       | 350 K                    | 350 K                    | 350 K                    | -             | -                        | -             | -                        | -                         | -                              | -                  | -                              |
| eastus             | -       | -           | 80 K          | -               | 150 K <br> 1 M | 450 K <br> 30 M              | 450 K <br> 2 M   | 2 M <br> 50 M                     | 240 K          | 240 K                   | 240 K                    | 350 K                    | 350 K                    | -             | -                        | -             | -                        | -                         | -                              | -                  | -                              |
| eastus2            | -       | -           | 80 K          | -               | 150 K <br> 1 M | 450 K <br> 30 M              | -             | -                              | 300 K          | -                       | 350 K                    | 350 K                    | 350 K                    | -             | -                        | -             | -                        | 250 K                     | 250 K                          | -                  | 250 K                          |
| francecentral      | 20 K    | 60 K        | 80 K          | -               | -           | 450 K <br> 30 M              | -             | -                              | 240 K          | -                       | 240 K                    | -                        | 350 K                    | -             | -                        | -             | -                        | -                         | -                              | -                  | -                              |
| germanywestcentral | -       | -           | -             | -               | -           | 450 K <br> 30 M              | -             | -                              | -              | -                       | -                        | -                        | -                        | -             | -                        | -             | -                        | -                         | -                              | -                  | -                              |
| japaneast          | -       | -           | -             | 30 K            | -           | 450 K <br> 30 M              | -             | -                              | 300 K          | -                       | 350 K                    | -                        | 350 K                    | -             | -                        | -             | -                        | -                         | -                              | -                  | -                              |
| koreacentral       | -       | -           | -             | -               | -           | 450 K <br> 30 M              | -             | -                              | -              | -                       | -                        | -                        | -                        | -             | -                        | -             | -                        | -                         | -                              | -                  | -                              |
| northcentralus     | -       | -           | 80 K          | -               | 150 K <br> 1 M | 450 K <br> 30 M              | -             | -                              | 300 K          | -                       | 350 K                    | -                        | -                        | 240 K         | 250 K                    | 240 K         | 250 K                    | 250 K                     | 250 K                          | 100 K              | 250 K                          |
| norwayeast         | -       | -           | 150 K         | -               | -           | 450 K <br> 30 M              | -             | -                              | -              | -                       | 350 K                    | -                        | -                        | -             | -                        | -             | -                        | -                         | -                              | -                  | -                              |
| polandcentral      | -       | -           | -             | -               | -           | 450 K <br> 30 M              | -             | -                              | -              | -                       | -                        | -                        | -                        | -             | -                        | -             | -                        | -                         | -                              | -                  | -                              |
| southafricanorth   | -       | -           | -             | -               | -           | 450 K <br> 30 M              | -             | -                              | -              | -                       | 350 K                    | -                        | -                        | -             | -                        | -             | -                        | -                         | -                              | -                  | -                              |
| southcentralus     | -       | -           | 80 K          | -               | 150 K <br> 1 M | 450 K <br> 30 M              | -             | -                              | 240 K          | -                       | 240 K                    | -                        | -                        | -             | -                        | -             | -                        | -                         | -                              | -                  | -                              |
| southindia         | -       | -           | 150 K         | -               | -           | 450 K <br> 30 M              | -             | -                              | 300 K          | -                       | 350 K                    | -                        | 350 K                    | -             | -                        | -             | -                        | -                         | -                              | -                  | -                              |
| swedencentral      | 40 K    | 80 K        | 150 K         | 30 K            | 150 K <br> 1 M | 450 K <br> 30 M              | -             | -                              | 300 K          | 240 K                   | 350 K                    | -                        | 350 K                    | 240 K         | 250 K                    | 240 K         | 250 K                    | 250 K                     | 250 K                          | 100 K              | 250 K                          |
| switzerlandnorth   | 40 K    | 80 K        | -             | 30 K            | -           | 450 K <br> 30 M              | -             | -                              | 300 K          | -                       | 350 K                    | -                        | -                        | -             | -                        | -             | -                        | -                         | -                              | -                  | -                              |
| switzerlandwest    | -       | -           | -             | -               | -           | -                         | -             | -                              | -              | -                       | -                        | -                        | -                        | -             | 250 K                    | -             | 250 K                    | 250 K                     | 250 K                          | -                  | 250 K                          |
| uksouth            | -       | -           | 80 K          | -               | -           | 450 K <br> 30 M              | -             | -                              | 240 K          | -                       | 350 K                    | -                        | 350 K                    | -             | -                        | -             | -                        | -                         | -                              | -                  | -                              |
| westeurope         | -       | -           | -             | -               | -           | 450 K <br> 30 M              | -             | -                              | 240 K          | -                       | 240 K                    | -                        | -                        | -             | -                        | -             | -                        | -                         | -                              | -                  | -                              |
| westus             | -       | -           | 80 K          | 30 K            | 150 K <br> 1 M | 450 K <br> 30 M              | -             | -                              | 300 K          | -                       | 350 K                    | -                        | -                        | -             | -                        | -             | -                        | -                         | -                              | -                  | -                              |
| westus3            | -       | -           | 80 K          | -               | 150 K <br> 1 M | 450 K <br> 30 M              | -             | -                              | -              | -                       | 350 K                    | -                        | 350 K                    | -             | -                        | -             | -                        | -                         | -                              | -                  | -                              |
