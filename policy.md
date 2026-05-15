# NCSC Vulnerability Disclosure Policy

## Overview

As part of the NATO procedure for including products in the **NATO Approved
Software List**, the **NATO Cyber Security Centre (NCSC)** conducts penetration
tests on candidate products. When such an assessment identifies security
vulnerabilities, NATO follows the disclosure process described below.

## Process Steps

1. **Vendor Notification** — The NCSC notifies the vendor (via the initial
   email) that vulnerabilities have been identified in their product.
2. **Vendor Response** — The vendor is expected to confirm either:
   - **(A)** agreement, or
   - **(B)** disagreement
   with the proposed course of action.

> **Response deadline:** If no response is received within **two weeks** of the
> notification email, the vendor is assumed to **disagree**, and the internal
> disclosure process (B) will commence.

## A. If the Vendor Agrees

- The vendor issues a formal statement confirming agreement to proceed with the
  responsible disclosure of the identified vulnerabilities.
- The NCSC provides an **unclassified version** of the vulnerabilities report
  to a designated vendor Point of Contact. This report **must not** be
  distributed publicly or to third parties.
- The vendor evaluates the reported vulnerabilities and provides feedback on
  their validity:
  - **If valid:** The vendor proposes a timeline for addressing the issues and the
    NCSC assigns a **CVE number** unless the vendor has their own CNA.
  - **If not valid:** The vendor must provide a detailed explanation for their
    position and engage in further discussion regarding the validity of the
    findings.
- The NCSC reviews and either accepts or rejects the proposed timeline, based
  on its reasonableness.
- The NCSC distributes a detailed report to **NATO member state CERTs** and the
  **NATO Multinational Malware Information Sharing Platform**, outlining the
  vulnerabilities discovered in the product.
- NATO notifies all member states of the vendor's willingness to cooperate with
  NATO's industry-standard full disclosure process.
- Upon expiration of the agreed timeline, the vendor is expected to release a
  new version of the product with **public release notes**, including the
  assigned CVE numbers and credit to the NCIA researchers.

> **IMPORTANT:** If the vendor fails to comply with any of the steps above
> (e.g. assigning a CVE number and publishing the vulnerabilities publicly
> after a fix is ready), the vendor will be considered **untrustworthy** and
> will receive a **negative advice** from the NCSC for any future use of its
> software. This will be communicated within NATO and to NATO member states.
>
> A **warning** will be issued prior to taking action, giving the vendor time
> to react.

## B. If the Vendor Disagrees

- The NCSC distributes a detailed report to **NATO member state CERTs** and the
  **NATO Multinational Malware Information Sharing Platform**, outlining the
  vulnerabilities discovered in the product.
- NATO notifies all member states of the vendor's refusal to cooperate with
  NATO's industry-standard full disclosure process.
- The NCSC recommends **against** including any of the vendor's products in the
  NATO Approved Software List.
- The NCSC will **not** distribute the report to the vendor.

## Guiding Principle

The primary goal of this process is to enhance the security of all products
used by NATO and its member states. **Transparency is crucial**, and NATO
expects the same level of transparency from the vendors whose products it
considers for use.
