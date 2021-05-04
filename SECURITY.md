# Security Policies and Procedures

This document outlines security procedures and policies for all non-forked repositories we own on GitHub, and all services we operate online.

## Bug Reporting

We take all security bugs related to our code and our infrastructure very seriously. Thank you for improving the security of our projects and services. We appreciate your efforts and responsible disclosure, and will make every effort to acknowledge your contributions.

Report any security bugs by emailing the services administrator at [jonah@triplebit.net](mailto:jonah@triplebit.net).

The administrative team will acknowledge your message within 48 hours, and will provide a detailed response within 72 hours detailing the next steps for handling your report. After our initial reply we will make every effort to keep you informed of the progress towards a fix and announcement, and we may ask for additional information or guidance.

Please report any security bugs in third-party projects to the person or team developing that project. Examples of third-party projects include [Synapse](https://github.com/matrix-org/synapse) or [Element](https://github.com/vector-im/element-web), as we do not actively assist in developing those projects.

The following are out of scope and should **not** be attacked/performed:

* Excessive Automated Scans
* Denial of Service Attacks
* Social Engineering Attacks
* Reports against infrastructure outside our control
* Accessing user or admin accounts not owned by the tester

## Disclosure Policy

When we receive a security report, we will coordinate the fix, release, and announcement process, involving the following steps:

1. Confirm the problem and determine affected services.
2. Audit infrastructure and/or code to find any potential similar problems.
3. Prepare fixes for all releases currently in production, which will be implemented as quickly as possible.

Additionally, if user data was directly affected or compromised, we will inform affected users to the best of our ability via email and/or a website notification with more information about the incident.

## Comments on this Policy

Please open a [Pull Request](https://github.com/privacyguides/.github/pulls) or [Issue](https://github.com/privacyguides/.github/issues) if you would like to discuss any changes to this policy.
