# PosgreSQL as database

| Decision Identifier | ADR_012                                                                         |
|---------------------|---------------------------------------------------------------------------------|
| Reason | PostgreSQL database is easily available and skills are available in the company |
| Status | DECIDED                                                                         |
| Date | 2024-10-03                                                                      |

## Decider

| Name     | Email address          | Role in the project | Role in decision |
|----------|------------------------|---------------------|-----------------|
| John Doe | john.doe@rentabike.com | Architect | Presenter |
| Jane Doe | john.doe@rentabike.com | Architect | Decider |
| Tom Smith | tom.smith@rentabike.com | Product Owner | Listener |

## Alternative 1: PostgreSQL as database

| Advantages and Chances | Disadvantages and Risk                                 |
|------------------------|--------------------------------------------------------|
| Easy to use            | Depending on cloud provider if it is provided directly |
| Skills available in the company | |
| For our size acceptable costs | |


| Assumptions and Quantities | Compromises                                  |
|--------------------------|----------------------------------------------|
| PostgreSQL is available  | Cloud native database might be more reliable |

## Alternative 2: Cloud native database

| Advantages and Chances | Disadvantages and Risk |
|------------------------|------------------------|
| Easy to setup          | No skills in the company |
| | Tight coupling of the product to the cloud provider


| Assumptions and Quantities             | Compromises                                       |
|----------------------------------------|---------------------------------------------------|
| A PostgreSQL interface is not provided | Low costs - but cloud provider is not decided yet |


