# Git Repository Name: inventoryoptimizer
Microsoft Fabric Hackathon

## Team Name
Inventory Optimizer

### Challenge Scenario
Inventory gets counted once a month by hand, while your cash sits frozen. Build 4 AI agents that recount it every day.

Solution

(1) An agent-swarm architecture diagram with four cooperating agents — retrieval, SKU matching, E&O calculation, recommendation — and a documented orchestration and hand-off contract. (2) A Fabric Data Agent grounded on the Lakehouse and exposed over MCP as the retrieval tool. (3) A SKU-matching component reconciling inconsistent descriptions, with a precision/recall scorecard against a labelled sample. (4) A daily E&O position with a reconciliation showing agreement with the monthly legacy calculation. (5) A recommendation output ranking disposition options per SKU with quantified working-capital release and a mandatory human approval step before any action. (6) Governance evidence: an Entra Agent ID per agent, least-privilege scoping and agent-level audit under Agent 365. (7) Role-tailored weekly reports delivered to Teams and a Power BI operations dashboard with Activator alerting on threshold breach.

