# 03_Document_Header.md

> **Document ID:** PRE-002-03\
> **Module:** PRE-002 --- Documentation DNA\
> **Version:** 1.0.0\
> **Status:** Canonical Foundation (Draft v1)

------------------------------------------------------------------------

# 1. Purpose

The document header is the standardized entry point for every canonical
AISOS document. It enables a reader---or any AI system---to immediately
understand the document's identity, authority, scope, and lifecycle.

# 2. Header Objectives

-   Establish identity.
-   Communicate document status.
-   Support discoverability.
-   Standardize presentation across the repository.
-   Reduce ambiguity for human and AI collaborators.

# 3. Standard Header Layout

``` text
Document Title

Document ID
Module
Version
Status
Classification
Owner
Last Updated

Purpose
Scope
Audience
```

# 4. Required Header Fields

  Field            Description
  ---------------- -----------------------------------------------
  Document Title   Official title.
  Document ID      Permanent identifier.
  Module           Parent module.
  Version          Semantic version.
  Status           Draft, Review, Approved, Canonical, Archived.
  Owner            Responsible role/team.
  Last Updated     ISO-8601 date.
  Purpose          One concise paragraph.
  Scope            Defines boundaries.

# 5. Canonical Header Example

``` markdown
# PRE-002 — Documentation DNA

**Document ID:** PRE-002-03
**Version:** 1.0.0
**Status:** Canonical
**Owner:** Documentation Team

## Purpose
Defines the standard document header used throughout AISOS.

## Scope
Applies to every canonical Markdown document.
```

# 6. Style Rules

-   Use a single H1 title.
-   Place metadata immediately below the title.
-   Keep the Purpose concise.
-   Avoid decorative formatting in canonical documents.
-   Preserve heading order.

# 7. Review Checklist

-   [ ] H1 title present
-   [ ] Metadata complete
-   [ ] Purpose included
-   [ ] Scope defined
-   [ ] Heading order valid

# Changelog

## v1.0.0

Initial specification for the AISOS document header.
