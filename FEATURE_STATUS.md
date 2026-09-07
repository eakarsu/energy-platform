# Feature status — Energy assets, grid & utilities

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 469 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 1 | 0 | Native records/view |
| Work items & projects | records | 1 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 2 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 1 | 0 | Native records/view |
| Reports & analytics | report | 20 | 0 | Native records/view |
| Activity & audit trail | audit | 22 | 0 | Native records/view |
| Provider connections | integration | 4 | 0 | Provider request records only |
| Tolling agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Battery asset registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Capacity commitment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dispatch instruction ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Telemetry validation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| State-of-charge reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Round-trip efficiency | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Availability calculation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Energy throughput calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Market revenue allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Performance penalty audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Settlement statement matching | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Counterparty dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash reconciliation | records | 6 | 0 | AI question-and-answer workspace; records available as context |
| Asset market analytics | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Utility Bill Ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Facility, Account & Meter Registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tariff & Rate-Schedule Library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Deterministic Bill Recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Billing Error Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Interval-Usage Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Demand-Charge Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tariff Optimization Engine | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Power-Factor & Reactive-Charge Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit & Incentive Eligibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Utility Dispute Package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Utility Response Management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Utility Recovery Ledger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Preventive Billing Alerts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Portfolio Outcome Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Program tariff library | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Project subscriber registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Subscription allocation control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Meter production ingestion | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Utility allocation file | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bill credit calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Low-income adder | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Subscription fee calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Subscriber move handling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unallocated production | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Utility statement matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Subscriber invoice reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Utility dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Project subscriber analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Site asset registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Enrollment capacity commitment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Interval meter ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Baseline calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Event notification tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Performance calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Availability payment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Capacity payment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Penalty validation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Aggregator fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dispute correction workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payment reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Site program analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Electricity demand data center load planner work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Partner roaming agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Station EVSE registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Charging-session ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Metered energy validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tariff time-of-use calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Session fee calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Roaming markup audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax currency treatment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Failed partial session control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refund adjustment control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Partner settlement reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Network fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dispute workflow | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Station partner economics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Queue Portfolio | records | 1 | 0 | Native records/view |
| Studies | records | 1 | 0 | Native records/view |
| Costs & Milestones | records | 1 | 0 | Native records/view |
| GIA & Risk | records | 1 | 0 | Native records/view |
| Cluster Window | records | 1 | 0 | Native records/view |
| Site Control | records | 1 | 0 | Native records/view |
| Deposit | records | 1 | 0 | Native records/view |
| Cluster Study | records | 1 | 0 | Native records/view |
| Network Upgrade | records | 1 | 0 | Native records/view |
| Cost Allocation | records | 1 | 0 | Native records/view |
| Milestone | records | 1 | 0 | Native records/view |
| Modification Request | records | 1 | 0 | Native records/view |
| GIA Control | records | 1 | 0 | Native records/view |
| Withdrawal Scenario | records | 1 | 0 | Native records/view |
| Affected System Study | records | 1 | 0 | Native records/view |
| Draft: Queue Readiness Reviewer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Upgrade Cost Allocator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Withdrawal Risk Modeler | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supply contract library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Site tank meter registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product purity specification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Volume meter ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Index price calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Take-or-pay validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Delivery fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tank rental validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Emergency delivery audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Energy surcharge audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Minimum volume calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Site product analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Midstream contract library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Meter statement ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Volume balancing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gas quality adjustment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fuel use calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shrink calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Processing fee validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| NGL yield calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| NGL price validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Residue gas settlement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gathering fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Netback reconstruction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Midstream dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| System plant analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Franchise agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Territory boundary mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Service address matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer class mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gross receipt ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Excluded revenue validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rate tier calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bad debt treatment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Affiliate revenue review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Return period reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Underpayment calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Utility audit request | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assessment notice workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash collection tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Territory utility analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pipeline tariff library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract point registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Nomination ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scheduled quantity tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Meter allocation ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Balancing agreement control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Daily imbalance calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash-out price validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fuel loss calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transport fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Storage fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pipeline statement reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Point pipeline analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Operator and property registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| JOA and COPAS term library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Division-of-interest validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| JIB statement ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AFE authority and budget control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Working-interest recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Overhead-rate validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Direct-charge allowability | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Material transfer pricing audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Affiliate and related-party review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Field-ticket evidence matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate and prior-period detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Operator exception package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audit deadline and response tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recovery and operator analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Master service agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Well job registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Work order ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Field ticket capture | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Crew hour validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Equipment hour validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Material quantity matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rate sheet calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Standby time audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mobilization mileage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fuel surcharge control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice ticket matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Well vendor analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| REC contract library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Asset eligibility registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Certificate issuance matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vintage validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product class mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Delivery schedule control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Market price calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transfer confirmation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retirement evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shortfall penalty calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice settlement matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Registry dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| PPA and amendment library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Asset and meter registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Interval generation ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ISO settlement ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract price recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Basis and loss-factor validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Curtailment event reconstruction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Deemed-generation calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Liquidated-damages recovery | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| REC delivery reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Availability guarantee tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice and settlement matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Offtaker dispute package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Receivable and credit tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Revenue and curtailment analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| O&M warranty agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Site equipment registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Weather irradiance ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Meter inverter telemetry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Expected generation model | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Excluded event validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Curtailment separation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Performance ratio calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Response repair SLA | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Liquidated damages | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Warranty claim linkage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provider claim package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Site vendor analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tank Site | records | 1 | 0 | Native records/view |
| Storage Tank | records | 1 | 0 | Native records/view |
| Tank Component | records | 1 | 0 | Native records/view |
| Leak Test | records | 1 | 0 | Native records/view |
| Walkthrough | records | 1 | 0 | Native records/view |
| Tank Repair | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Inventory Reading | records | 1 | 0 | Native records/view |
| Operator Training | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Incident Notice | records | 1 | 0 | Native records/view |
| Operational Task | records | 1 | 0 | Native records/view |
| Rule Version | records | 1 | 0 | Native records/view |
| Document Requirement | records | 1 | 0 | Native records/view |
| Inspection report extraction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Leak test record comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Component maintenance brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Inventory variance explanation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Operator evidence checklist | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Incident chronology draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Evidence completeness review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Operations handoff draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pole inventory registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Attacher agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Attachment survey ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Authorized attachment matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unauthorized attachment detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rate formula calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Space factor validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrying charge calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Joint-use offset | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Make-ready cost recovery | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Back-rent calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Attacher invoice generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Territory attacher analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Water balance registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Production meter ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| District meter ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer consumption ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Authorized unbilled use | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Meter under-registration | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Data handling error detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unauthorized consumption | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Real loss calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Leak event prioritization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pressure management analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Meter replacement economics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Billing correction workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recovered revenue tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| District loss analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Battery Packs | records | 1 | 0 | Native records/view |
| Cells | records | 1 | 0 | Native records/view |
| Modules | records | 1 | 0 | Native records/view |
| Chargers | records | 1 | 0 | Native records/view |
| Sites | records | 1 | 0 | Native records/view |
| Leases | records | 1 | 0 | Native records/view |
| Certifications | records | 1 | 0 | Native records/view |
| Telemetry | records | 1 | 0 | Native records/view |
| Dispatch Schedules | records | 1 | 0 | Native records/view |
| Alarms | records | 1 | 0 | Native records/view |
| Maintenance Logs | records | 2 | 0 | Native records/view |
| Warranty Claims | records | 1 | 0 | Native records/view |
| SoH Reports | records | 1 | 0 | Native records/view |
| Degradation Curves | records | 1 | 0 | Native records/view |
| Second-Life Units | records | 1 | 0 | Native records/view |
| Recycling Orders | records | 1 | 0 | Native records/view |
| AI · Degradation Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · SoH Trend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Capacity Fade Explain | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Replacement Timeline | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · PPA Revenue Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Thermal Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Cell Balance Suggest | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Anomaly Cluster | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Dispatch Optimize | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Second-Life Route | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Recycling Quote | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Executive Brief | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI · Fleet Health | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI · Customer SoH Report | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Vendor Quality Score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Warranty Draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pack quarantine review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| End of life classify | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Second life suitability | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Thermal anomaly detect | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recycling stream route | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Soc predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Custody events | records | 1 | 0 | Native records/view |
| Coa records | records | 1 | 0 | Native records/view |
| Ppa schedules | records | 1 | 0 | Native records/view |
| Battery passports | records | 1 | 0 | Native records/view |
| Compliance records | records | 1 | 0 | Native records/view |
| Lca entries | records | 1 | 0 | Native records/view |
| Escalation rules | records | 1 | 0 | Native records/view |
| Warranty workflow | records | 1 | 0 | Native records/view |
| Marketplace listings | records | 1 | 0 | Native records/view |
| Webhooks | integration | 2 | 0 | Provider request records only |
| Load Forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Renewable Sources | records | 1 | 0 | Native records/view |
| Demand Response | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Fault Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Energy Storage | records | 1 | 0 | Native records/view |
| Power Flow | records | 1 | 0 | Native records/view |
| Carbon Emissions | records | 1 | 0 | Native records/view |
| Smart Meters | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Voltage Regulation | records | 1 | 0 | Native records/view |
| Outage Management | records | 1 | 0 | Native records/view |
| Energy Trading | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Weather Impact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Maintenance Scheduling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Feeder Capacity Queue | records | 1 | 0 | Native records/view |
| Regulatory Compliance | records | 1 | 0 | Native records/view |
| Grid Topology | records | 1 | 0 | Native records/view |
| Missing features | records | 1 | 0 | Native records/view |
| Production readiness | records | 1 | 0 | Native records/view |
| Wellhead Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reservoir Simulation | records | 1 | 0 | Native records/view |
| Production Decline Curves | records | 1 | 0 | Native records/view |
| Equipment Failure Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Environmental Compliance | records | 1 | 0 | Native records/view |
| Production Forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Well Performance Monitoring | records | 1 | 0 | Native records/view |
| Drilling Operations | records | 1 | 0 | Native records/view |
| Cost Analysis & Economics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pipeline Monitoring | records | 1 | 0 | Native records/view |
| Water Management | records | 1 | 0 | Native records/view |
| Safety Incident Tracking | records | 2 | 0 | Native records/view |
| Gas Lift Optimization | records | 1 | 0 | Native records/view |
| Production Anomaly | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pipeline Rupture Predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Optimal Maintenance Window | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Near-Miss Severity Predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Asset Lifecycle Tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Multi-Well Portfolio | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sensor Anomaly Batch | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unit converter | records | 1 | 0 | Native records/view |
| Alerts | records | 1 | 0 | Native records/view |
| Field notes | records | 1 | 0 | Native records/view |
| Production history | records | 1 | 0 | Native records/view |
| History | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Alert rules | records | 1 | 0 | Native records/view |
| Predictive | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Advanced | records | 1 | 0 | Native records/view |
| Operations hub | records | 1 | 0 | Native records/view |
| agentic well optimization | records | 1 | 0 | Native records/view |
| decline curve ensemble modeling | records | 1 | 0 | Native records/view |
| sensor anomaly streaming | records | 1 | 0 | Native records/view |
| environmental compliance assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| cross operator benchmarking | records | 1 | 0 | Native records/view |
| production history logged but no production | records | 1 | 0 | Native records/view |
| pipeline monitoring without pipeline | records | 1 | 0 | Native records/view |
| safety incidents without near | records | 1 | 0 | Native records/view |
| equipment maintenance without optimal | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| real | records | 1 | 0 | Native records/view |
| asset lifecycle tracking equipment purchase ins | records | 1 | 0 | Native records/view |
| preventive maintenance scheduling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| limited multi | records | 1 | 0 | Native records/view |
| integration with geological petrophysical datab | integration | 1 | 0 | Provider request records only |
| webhooks for alert delivery pagerduty slack | integration | 1 | 0 | Provider request records only |
| mobile field | records | 1 | 0 | Native records/view |
| rbac beyond auth | records | 1 | 0 | Native records/view |
| Energy Consumption | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Solar Panels | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Battery Management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Utility Rates | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| EV Charging | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carbon Tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Thermostats | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Appliance Efficiency | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Consumption Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Equipment Scheduling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Solar Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rate Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Battery Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Device Management | records | 1 | 0 | Native records/view |
| Maintenance | records | 1 | 0 | Native records/view |
| Energy Goals | records | 1 | 0 | Native records/view |
| Usage Reports | records | 1 | 0 | Native records/view |
| Bill Simulator | records | 1 | 0 | Native records/view |
| Energy Timeline | records | 1 | 0 | Native records/view |
| Carbon Footprint | records | 1 | 0 | Native records/view |
| load shifting optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| renewable battery coordination | records | 1 | 0 | Native records/view |
| demand response automation | records | 1 | 0 | Native records/view |
| appliance lifetime optimization | records | 1 | 0 | Native records/view |
| wholehome energy resilience | records | 1 | 0 | Native records/view |
| behavioral energy coaching | records | 1 | 0 | Native records/view |
| consumptionforecast predict energy use | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| equipmentscheduling runwhencheap | records | 1 | 0 | Native records/view |
| rateoptimization load shifting for tou | records | 1 | 0 | Native records/view |
| solarforecast generation prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| batterymanagementoptimization | records | 1 | 0 | Native records/view |
| demandresponseautomation | records | 1 | 0 | Native records/view |
| smart device api integration nest tesla e | integration | 1 | 0 | Provider request records only |
| realtime monitoring dashboard backend | records | 1 | 0 | Native records/view |
| utilitynetmetering api integration | integration | 1 | 0 | Provider request records only |
| live solar monitoring enphase solaredge | records | 1 | 0 | Native records/view |
| home automation triggers scenes | records | 1 | 0 | Native records/view |
| public webhooks for grid signals | integration | 1 | 0 | Provider request records only |
| Turbines | records | 1 | 0 | Native records/view |
| Inverters | records | 1 | 0 | Native records/view |
| Panels | records | 1 | 0 | Native records/view |
| Transformers | records | 1 | 0 | Native records/view |
| Met Masts | records | 1 | 0 | Native records/view |
| Work Orders | records | 1 | 0 | Native records/view |
| Sensor Streams | records | 1 | 0 | Native records/view |
| Energy Meters | records | 1 | 0 | Native records/view |
| Weather Forecasts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Faults | records | 1 | 0 | Native records/view |
| Curtailment Events | records | 1 | 0 | Native records/view |
| PPA Contracts | records | 1 | 0 | Native records/view |
| Technicians | records | 1 | 0 | Native records/view |
| Spare Parts | records | 1 | 0 | Native records/view |
| Performance KPIs | records | 1 | 0 | Native records/view |
| AI · Forecast Generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Weather Window | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Curtailment Optimize | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Ramp-Rate Strategy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Fault Prognostic | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Schedule Maintenance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Blade Inspection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Draft Work Order | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Root Cause Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Turbine Availability | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Inverter Clipping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Asset Deg Trend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · PPA Settlement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Vendor Warranty Claim | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Intraday forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ticket prioritizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ppa shortfall narrator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Soiling icing detect | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hybrid storage co opt | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Drone blade inspection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dispatch confidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scada events | records | 1 | 0 | Native records/view |
| Work order fsm | records | 1 | 0 | Native records/view |
| Iso bids | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 469 feature pages were visited in the browser; 467 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 326 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

326 original AI entries are now grouped into **7 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
