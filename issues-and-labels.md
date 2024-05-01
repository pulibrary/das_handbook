---
layout: default
title: Issues and Labels
---
# Issues and Labels

## Issues

We use Github Issues to keep track of the work we do.  An issue can
represent a bug we need to fix, a feature to build, a maintenance task,
a piece of non-technical work, etc.

## Labels

One way that we organize our issues is by adding labels.  Here are some labels
we use:

| Label | Meaning |
|---|---|
|accessibility-A|A violation of a WCAG-A success criterion.  These are critical accessibility issues.|
|accessibility-AA|A violation of a WCAG-AA success criterion.|
|accessibility-AAA|A violation of a WCAG-AAA success criterion.|
|accessibility-awaiting-triage|An accessibility issue, but we're not yet sure which level it is.|
|accessibility-general|An issue related to accessibility, but not a specific violation.  For example, adding a new accessibility checker to a form field in one of our apps.|
|investigate|These issues mean you should look into a particular topic and share your findings, but you are not expected to open a PR to resolve it.|
|maintenance|Maintenance tasks or issues.  They will typically be addressed during a maintenance work cycle.|
|performance|Performance issues.|

### A note about accessibility labels
The [WCAG standard](https://www.w3.org/TR/WCAG22)
is divided into "success criteria", each of which is labeled with a conformance level:
A (most impactful), AA, and AAA (least impactful).  Our goal is to address all Level A and AA issues. When adding an accessibility
label to an issue, if you are not sure which success criterion is relevant or what its
conformance level is, you can:

* ask or pair with a colleague who is more familiar with the WCAG success criteria, or
* apply the `accessibility-awaiting-triage` label.
