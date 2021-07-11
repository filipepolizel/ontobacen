# RWA Module

This module is responsible for the conceptualizations which are necessary for calculating risk-weighted assets
(RWA) of a SFN’s financial institution, playing a central role on *OntoBacen*’s development and use cases, being in turn the
largest (and most complex) of its modules.

The **RWA** module encompasses four underlying ontologies:

- [**BankingRisk**](https://github.com/filipepolizel/ontobacen/tree/master/public/RWA/BankingRisk): encompasses definitions used for calculation of RWA related to exposures from non-trading (banking) portfolio.
- [**CreditRisk**](https://github.com/filipepolizel/ontobacen/tree/master/public/RWA/CreditRisk): encompasses definitions used for calculation of RWA related to credit risk (e.g. unpaid debts).
- [**MarketRisk**](https://github.com/filipepolizel/ontobacen/tree/master/public/RWA/MarketRisk): encompasses definitions used for calculation of RWA related to market risk (e.g. price volatility of securities).
- [**OperationalRisk**](https://github.com/filipepolizel/ontobacen/tree/master/public/RWA/OperationalRisk): encompasses definitions used for calculation of RWA related to operational risk (e.g. human mistakes, fraud).
