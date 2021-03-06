# Guide for Contributing to Open Source Software (Draft)

The [Directive on Management of Information Technology](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=15249), Appendix C provides mandatory procedures for enterprise architecture assessment that will be used by departmental Architecture Review Boards (ARB) and the Government of Canada Enterprise ARB as an assessment framework to review digital initiatives to ensure the GC acts as a single enterprise and to ensure departmental alignment with the GC digital direction.

These align with the [Digital Standards](https://www.canada.ca/en/government/publicservice/modernizing/government-canada-digital-standards.html) and the [Procedures for Application Architecture](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=15249#claC.2.3.8) that, all source code must be released under an appropriate open source software license when appropriate.

> **All source code modifications made to open source software, whether in-house by GC or through procurement contracts, must be shared back with the open source software community.**
> **The GC must be an active contributor to open source software it's using or where there is benefit to Canadians, by sharing code, but also by creating bug reports and feature requests as well as helping with testing and influencing the development roadmap.**

The steps to GC employees contributing to open source software communities are:

1. [Verify Open Source Software Licence](#verify-open-source-software-licence)
1. [Verify Contributing Process and Policies](#verify-contributing-process-and-policies)
1. [Seek Approvals](#seek-approvals)
1. [Contribute](#contribute)
1. [Other Notes](#other-notes)

## Verify Open Source Software Licence

GC can contribute to all software licensed under an [Open Source Initiative approved license](https://opensource.org/licenses) or a [Free Software Foundation free software licence](https://www.gnu.org/licenses/license-list.html).

## Verify Contributing Process and Policies

Certain projects may have specific policies for code contribution (Contributor Licence Agreement, Developer's Certificate of Origin) as well as processes (templates, platform, etc.).

Before going forward with submitting a contribution, employees should properly understand the project contribution processes and policies. 
Employees should then ensure that the delegated approvals meet those requirements.

## Additional Approvals

If for some reason the departmental delegated approvals are not meeting the 3rd party contribution's requirements, employees should contact their supervisor and see how they can obtain the additional authorizations required.

By default, departments should put clear scenarios where employees are authorized to contribute to 3rd party projects and when additional authorizations are necessary.

As an example, a blanket approval could be provided for a department's employees highlighting the criteria that would not necessitate authorization for contribution.

### Time

Some departments may request employees to get their manager's approval to spend time contributing to open source software.
Note that this should only be for a matter of managing operational needs as the default should be to encourage contribution to 3rd party OSS projects used in the GC.

### Department

Similar to open data or information covered by the [Directive on Open Government](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=28108), the publication of source code under an open source software licence, requires appropriate department or agency approvals.
Because of the required assignment of rights by an open source software licence, the Assistant Deputy Minister (ADM), or any other person named by the ADM is responsible for approving the releases of open source code.

As mentioned previously, delegation should be encouraged to be done to the lowest level possible to encourage contribution to 3rd party OSS projects.

## Contribute to the project

### Identify as an employee of the Government of Canada

Employees must use their full name and Government of Canada email address for all code contributions to public repositories while acting within the scope of their duties or employment.

**Note**: this is related to the [Public Servant Invention Act](https://laws-lois.justice.gc.ca/eng/acts/P-32/FullText.html#h-3), section 3. Additional clarification as to the means of identifying as an employee of the GC without necessarily requiring the email address in commits will need to be sought to ease the process.

### Submit changes

To make changes in open source software, engage with the community and submit your changes upstream to ensure that your modifications are supported by future updates.

Contributing to a 3rd party should be done in accordance to the project governance model, if such a model is present.

**note:** More than code (Bug reports, feature requests, direction, security assessments, ..)

## Contribute through professional services

If professional services are used to contribute to third party projects, see [Guide for publishing Open Source Code](publishing-open-source-code.md#obtain-rights-to-custom-code-in-contracts)

## Other Notes

* Licence delegation authority (IP+licence)
  * Recommended that delegation of authority to contribute on a 3rd party OSS project be granted de facto given key requirements:
    * No CLA is required (would need the organisation to sign it, not the individual - to be confirmed)
    * IP still belongs to the Crown
* Type of contribution allowed (_code_, bugs, issues, etc.)
* Security
  * Contributing employee follows Policy on Acceptable Network and Device Use, just like any other external services.
    * 2FA is recommended
* Basic commits guidelines (use your name, prof email address., message, etc.)
* Grants and contributions: bug bounties via GCDevExchange?
