## Bounded Context

```mermaid
mindmap
direction TB
classDef defaultStyle fill:#f9f,stroke:#333,stroke-width:2px;
classDef subStyle fill:#bbf,stroke:#f66,stroke-width:2px;
style root defaultStyle

root[(Payment System)]:::defaultStyle
  sub1[(Payment Authorization)]:::subStyle
  sub2[(Transaction Settlement)]:::subStyle
  sub3[(Security Protocols)]:::subStyle
  sub4[(Fraud Prevention)]:::subStyle
  sub5[(Payment Gateway Integration)]:::subStyle
  sub6[(Regulatory Compliance)]:::subStyle
  sub7[(User Interface Design)]:::subStyle
  sub8[(Merchant Analytics)]:::subStyle
  sub9[(Integration Support)]:::subStyle

root --> sub1
root --> sub2
root --> sub3
root --> sub4
root --> sub5
root --> sub6
root --> sub7
root --> sub8
root --> sub9
```