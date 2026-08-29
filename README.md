<p align="center">
  <img src="assets/hero.png" alt="Operational control planes system illustration" width="100%" />
</p>

# Operational control planes

The admin side of a product is where ambiguity becomes expensive. Operators need to see state, understand why it changed, take controlled action, and leave enough evidence for the next person.

[Discuss a similar system](mailto:ju@jomena.group?subject=Discuss%20Operational%20control%20planes) | [Book a technical call](mailto:ju@jomena.group?subject=Book%20a%20technical%20call%20about%20Operational%20control%20planes)

## The engineering problem

These systems joined several generations of dashboards and services around changing products. The work included making state consistent, reducing hidden manual steps, and designing safer controls.

## What the system covers

- Administrative and support workflows
- Account, product, and transaction views
- Role-aware actions and approvals
- Backend aggregation and integration
- Audit history and operational reporting

## System shape

```mermaid
flowchart LR
    n0["Product services"]
    n1["Admin backend"]
    n2["Role checks"]
    n3["Operator interface"]
    n4["Action workflow"]
    n5["Audit history"]
    n0 --> n1
    n1 --> n2
    n2 --> n3
    n3 --> n4
    n4 --> n5
```

## Build notes

- Show operators the source and age of important state.
- Separate observation from action.
- Put confirmation and evidence around consequential controls.

<sub>Built under the Aryze umbrella. The underlying source and company IP remain private and owned by Aryze. Delivery involved people across engineering, product, operations, compliance, and design. Open-source foundations retain their original attribution and licences.</sub>

## Talk through a similar problem

If you are trying to build, untangle, or ship a system in this area, [send me a note](mailto:ju@jomena.group?subject=I%20need%20help%20with%20Operational%20control%20planes). If the problem needs a deeper technical conversation, [book a call by email](mailto:ju@jomena.group?subject=Book%20a%20technical%20call%20about%20Operational%20control%20planes).
