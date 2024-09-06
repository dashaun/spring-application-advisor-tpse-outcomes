# Outcomes

In general there a three outcomes of continous migrations with Tanzu Spring:
- Performance improvements that lead reduced infrastructure spend and better customer experience
- Security and compliance
- Developer productivity and satisfaction

---

## Infrastructure Savings

Application with 20gb memory reserve per container, down to 2gb memory reserve per container, hundreds of instances worldwide (Software/SaaS)
- Original startup time was 20s, new startup time was 27s, but the savings from memory was more valuable
- Yes, it was a slower startup.  They were trying to get a faster startup, but the improved memory usage became the winner.

Cloud Foundry Diego Cells (Retail)
- By upgrading to newer versions of Java and Spring Boot, organization was able to reduce the number of Diego Cells (Virtual Machines) needed across all foundations
- A Diego Cell in Cloud Foundry is conceptually similar to a worker node in Kubernetes (GKE)

**Outcomes**:
- Reduced Image Size -> Reduced Ingress/Egress costs, Reduced Storage costs
- Reduced Memory Footprint -> Reduced compute costs

---

## Compliance

Replacing unsupported Frameworks (Auto)
- They needed to replace an outdated and unsupported framework across the entire portfolio of applications.
- Although we didn't have the exact recipes they were looking for, the recipes that we provided helped them move forward faster
- The workshop that was delivered, enabled them to begin developing their own custom recipes

Prevented Upgrade Bottlenecks (Insurance)
- The DevOps team was unable to upgrade "shared services" because it would break a large portion of the applications that were dependent
- Helped the application teams, at scale, upgrade to required versions, which allowed the "shared services" to continue upgrade

Timelines (Finance)
- Helped team meet upgrade deadlines at scale, for regulatory/compliance
- Continuing to use "continuous migration"
- Seeing organic growth in adoption

Governance Starter (FIPS/PCI)
- Developed based on customer feedback
- Allows move from manual, spreadsheet based attestation to automated validation, via actuator endpoints

**Outcomes**:
- Reduced cost of compliance project implementations
- Decreased time to delivery of patches, and reduced effort
- Automation reducing exposure, continously

---

## Delivery

Faster, more frequent releases (FinTech / Telecom)
- By incorporating "migration automation" the organization was able to deliver patches to their customers, faster
- Flagship product

Improved application density for "edge" workloads (Oil & Gas)
- The infrastructure used in this usecase was unable to be upgraded, due to budget
- By upgrading the software, the need for upgrade was pushed further into the future

Developer Enablement and Excitement (Finance)
- Empowered the new engineering leadership
- Increased developer satisfaction
- Improved engineering recruitment

**Outcomes**:
- Improved revenue per developer
- Ability to recruit world class engineering talent
