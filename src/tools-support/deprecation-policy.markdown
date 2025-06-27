---
title: API Lifecycle & Deprecation Policy
layout: reference
redirect_from:
  - /tools-support/reference/deprecation-policy.html
---

# API Lifecycle & Deprecation Policy

The API Lifecycle & Deprecation Policy is part of our [API terms and conditions of use](/terms-of-use-2021.html). We may make periodic updates to this policy, at which time we will notify in [Release Notes](/release-notes/).

## API Version Status  

* **Beta:** A version of an API that is not meant for productive use. Beta APIs may be changed or deleted at our discretion.
* **Active:** A version of an API that is meant for productive use.
* **Deprecated:** A version of an API that supports productive use but is destined to be Decommissioned. In cases where an Active version of the API exists, it is advisable to migrate to the Active version, however, an Active version may not exist in all cases. New apps may be denied access to deprecated APIs.
* **Decommissioned:** A version of an API that is no longer meant for productive use and is no longer supported by SAP. APIs in this status may be deleted or have access removed at any time.

## API Lifespan and State Change

* **Minimum Lifespan:** We will provide a minimum lifespan for non-Beta APIs of 24 months in Active or Deprecated states before announcing a Decommissioned state. For example, the minimum API lifespan ‘M’ for an API after it is published in Active version V1 is 24 months, where M is defined as the combined periods in Active and Deprecated states.
*	**Deprecated -> Decommissioned:** Once an API transitions from an active to deprecated status, we will maintain the API in the deprecated state for a minimum of 12 months before transitioning the API to decommissioned state.
*	**Decommissioned:** Decommissioned APIs are no longer supported and documentation may be deleted at our discretion. 
*	**Exceptions:** There may be exceptions where we are not able to satisfy the foregoing minimum lifespan or minimum deprecated state duration. This is including but not limited to:
    * Where required by law or regulatory authority.
    * Where required by a third party licensor.
    * To address a security risk.
    * To address a claim by a third party of intellectual property infringement.
    * Where the associated SAP Concur product has entered end of life.
    * Where the API or the associated application have no adoption and are therefore being deleted.

## API Version Status Table

Beta|Active|Deprecated|Decommissioned
---|---|---|---
**API is live in production but subject to change or deletion at any time.**| **API is live in production.**| **API is live in production.** | API is no longer available in production.
**Documentation:** May not be available or maybe restricted to select clients/partners.| **Documentation:** Posted on day of launch, may be available for review earlier. | **Documentation:** Deprecated status indicated and posted on day of deprecation. | **Documentation:** N/A
**Support:** None.| **Support:** Updated with bug fixes and new features are available. | **Support:** Updated with bug fixes for a minimum of 12 months. | **Support:** None.
**Release Notes:** May or may not be published.| **Release Notes:** Announce availability when in production.| **Release Notes:** Announce when deprecated. Time period is at least 12 months in this status. | **Release Notes:** Notify 30 days prior to decommissioning.
