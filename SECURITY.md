# Security Policy

## Report a vulnerability

We sincerely request you to keep the vulnerability information confidential and responsibly disclose the vulnerabilities.

To report a vulnerability, please contact the Security Team: [kmesh-security-vulnerability@googlegroups.com](mailto:kmesh-security-vulnerability@googlegroups.com). You can email the Security Team with the security details and the details expected for [Kmesh vulnerability reports](./comms-templates/vulnerability-report-template.md).

The information of the Security Team members is described in [here](security-groups.md).

### E-mail Response

The team will help diagnose the severity of the issue and determine how to address the issue. The reporter(s) can expect a response within 2 business day acknowledging the issue was received. If a response is not received within 2 business day, please reach out to any Security Team member directly to confirm receipt of the issue. We’ll try to keep you informed about our progress throughout the process.

### When Should I Report a Vulnerability?

- You think you discovered a potential security vulnerability in Kmesh
- You are unsure how a vulnerability affects Kmesh

### When Should I NOT Report a Vulnerability?

- You need help tuning Kmesh components for security
- You need help applying security related updates
- Your issue is not security related

If you think you discovered a vulnerability in another project that Kmesh depends on, and that project has their own vulnerability reporting and disclosure process, please report it directly there.

## Security release process

The Kmesh community will strictly handle the reporting vulnerability according to this [procedure](security-release-process.md). The following flowchart shows the vulnerability handling process.

<img src="./images/vulnerability-handling-process.PNG">

## Relative Mailing lists

- [kmesh-security-vulnerability@googlegroups.com](mailto:kmesh-security-vulnerability@googlegroups.com), is for reporting security concerns to the Kmesh Security Team, who uses the list to privately discuss security issues and fixes prior to disclosure.

- [kmesh-security-vulnerability@googlegroups.com](mailto:kmesh-security-vulnerability@googlegroups.com), is for advance private information and vulnerability disclosure.

More details of group membership is managed [here](security-groups.md).

See the [private-distributors-list](private-distributors-list.md) for information on how Kmesh distributors or vendors can apply to join this list.

## Supported versions

Kmesh versions are expressed as x.y.z, where x is the major version, y is the minor version, and z is the patch version, following [Semantic Versioning](https://semver.org/) terminology.

The Kmesh project maintains release branches for the most recent three minor releases. Applicable fixes, including security fixes, may be backported to those three release branches, depending on severity and feasibility.

Our typical patch release cadence is every 3 months. Critical bug fixes may cause a more immediate release outside of the normal cadence. We also aim to not make releases during major holiday periods.

See the [Kmesh releases page](https://github.com/kmesh-net/kmesh/releases) for information on supported versions of Kmesh.
