# Policy Repository

Policy documents are maintained in the [OSCAL workspace](https://github.com/sep78674463/OSCAL) alongside their machine-readable OSCAL representations.

## Why are policies in the OSCAL repo?

Keeping policies and OSCAL artifacts in the same repository means:

- Policy Markdown files live next to the OSCAL component-definitions they generate
- The NIST SP 800-53 catalog and SSPs can reference policy components with relative paths
- A single CI pipeline validates both human-readable policies and OSCAL schema compliance
- `generate_policy_components.py` runs in the same context as the catalog it maps controls against

## Where to find policies

| Location | Contents |
|----------|----------|
| [`OSCAL/policies/`](https://github.com/sep78674463/OSCAL/tree/main/policies) | Human-readable Markdown policy documents |
| [`OSCAL/policies/POLICY-TEMPLATE.md`](https://github.com/sep78674463/OSCAL/blob/main/policies/POLICY-TEMPLATE.md) | Reusable NIST CSF policy template |
| [`OSCAL/workspace/component-definitions/policies/`](https://github.com/sep78674463/OSCAL/tree/main/workspace/component-definitions/policies) | Generated OSCAL component-definition |

## Quick links

- [Information Security Policy](https://github.com/sep78674463/OSCAL/blob/main/policies/govern/information-security-policy.md)
- [Access Control Policy](https://github.com/sep78674463/OSCAL/blob/main/policies/protect/access-control-policy.md)
- [Incident Response Policy](https://github.com/sep78674463/OSCAL/blob/main/policies/respond/incident-response-policy.md)
