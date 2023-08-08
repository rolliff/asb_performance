# Azure Service Bus Performance Test

This repository is to test the throughput for a given configuration of host machine and service bus.

## Test 1

| Property                | Value                     |
|-------------------------|---------------------------|
| ASB Pricing tier        | Premium                   |
| ASB Zone Redundancy     | Enabled                   |
| ASB Messaging units     | 4                         |
| ASB Topic Max Size      | 80GB                      |
| ASB Message Max Size    | 1024KB                    |
| ASB Duplicate Detection | 7 Days                    |
| Host OS                 | Linux (ubuntu 20.04)      |   
| Host Size               | 8 vcpus, 32 GiB (D8ds v5) |
| Message Size            | 1024 Bytes                |
| Result                  | 3500/s                    |
