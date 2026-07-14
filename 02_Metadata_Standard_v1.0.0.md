# 02_Metadata_Standard.md

> **Document ID:** PRE-002-02\
> **Module:** PRE-002 --- Documentation DNA\
> **Version:** 1.0.0\
> **Status:** Canonical Foundation (Draft v1)\
> **Repository:** AISOS

------------------------------------------------------------------------

# 1. Purpose

This document defines the metadata standard for every canonical Markdown
document within AISOS.

Metadata provides a consistent identity, lifecycle, ownership,
discoverability, and relationship model for all repository assets.

------------------------------------------------------------------------

# 2. Design Principles

The metadata system shall be:

1.  Human-readable
2.  AI-readable
3.  Git-friendly
4.  Stable across versions
5.  Extensible without breaking existing documents

------------------------------------------------------------------------

# 3. Required Metadata Fields

  Field          Required   Description
  -------------- ---------- -----------------------------------------------
  Document_ID    Yes        Permanent identifier. Never reused.
  Title          Yes        Official document title.
  Version        Yes        Semantic version (MAJOR.MINOR.PATCH).
  Status         Yes        Draft, Review, Approved, Canonical, Archived.
  Module         Yes        Parent module identifier.
  Owner          Yes        Responsible role/team.
  Last_Updated   Yes        ISO-8601 date.

------------------------------------------------------------------------

# 4. Recommended Metadata

  Field          Purpose
  -------------- ----------------------
  Parent         Parent document
  Children       Child documents
  Dependencies   Required references
  Related        Supporting documents
  Tags           Search and filtering
  Review_Date    Scheduled review

------------------------------------------------------------------------

# 5. Canonical Metadata Template

``` yaml
Document_ID:
Title:
Module:
Version:
Status:
Owner:
Created:
Last_Updated:
Review_Date:
Parent:
Children:
Dependencies:
Related:
Tags:
```

------------------------------------------------------------------------

# 6. Metadata Rules

-   Document_ID never changes.
-   Version follows semantic versioning.
-   Dates use YYYY-MM-DD.
-   Unknown values remain blank; never invent metadata.
-   Metadata appears at the top of every canonical document.

------------------------------------------------------------------------

# 7. Validation Checklist

-   [ ] Required fields completed
-   [ ] Document_ID unique
-   [ ] Version valid
-   [ ] Status valid
-   [ ] Dates formatted correctly
-   [ ] Links verified

------------------------------------------------------------------------

# Changelog

## v1.0.0

Initial canonical metadata specification.
