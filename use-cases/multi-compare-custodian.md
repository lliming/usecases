---
layout: default
title: NIH Compare across DCCs
nav_order: 2
parent: Use Cases
has_children: false
---

# Use Case UC0002 Explore data availability to build policy

**Persona:** [Program Officer](../personas/program-officer).

**Objective:** [Multiple DCC Comparison](../objectives/multi-dcc-comparison)

### Summary

Jon is a leader at the Common Fund, and wants to build summary tables of
Common Fund assets for use in both tracking progress and for finding gaps that
should be filled by future initiatives. They would like to use the CFDE interface
to download simple tables or graphs that show what assets exist, and where.

Using a web browser, Jon uses a point and click interface to get a matrix of
Uberon tissue terms by DCC. With a few more clicks, they gets similar tables showing
Species, and Assay Types by Program.

Since these are simple binary matrices, Jon can plot the data in almost any
piece of plotting software. Since they would like to see what terms are most broadly
and most infrequently found in the Common Fund, they opt for using UpSet, which
will automatically render her data in a type of multidimensional venn diagram.

### User Tasks

-   [T0001 Access CFDE interface](#access-cfde-interface)
-   [T0011 Search/filter CF Programs by anatomic terms](#searchfilter-common-fund-programs-by-anatomic-terms)
-   [T0012 Search/filter CF Programs by type terms](#search-filter-common-fund-programs-by-type-terms)
-   [T0010 Visualize a table of all projects that match query](#visualize-a-table-of-all-projects-that-match-query)
-   [T0003 Export a file of results](#export-a-file-of-results)

### Requirements

#### T0001 Access CFDE interface

-   [R00001 The interface will support GUI web access to end users](../requirements/r00001-the-interface-will-support-gui-web-access-to-end-users.md)
-   [R00002 The interface will support user authentication](../requirements/r00002-the-interface-will-support-user-authentication.md)

#### T0011 Search/filter Common Fund Programs by anatomic terms

-   [R00003 The interface will support the selection of an Uberon term of interest](../requirements/r00003-the-interface-will-support-the-selection-of-an-uberon-term-of-interest.md)
-   [R00004 The C2M2 model will support information relating Uberon terms to CF programs](../requirements/r00004-the-c2m2-model-will-support-information-relating-uberon-terms-to-cf-programs.md)
-   [R00005 The catalog will store information relating Uberon terms to CF programs](../requirements/r00005-the-catalog-will-store-information-relating-uberon-terms-to-cf-programs.md)
-   [R00015 The interface will support the selection of a species term of interest](../requirements/r00015-the-interface-will-support-the-selection-of-a-species-term-of-interest.md)
-   [R00016 The C2M2 model will support information relating species terms to CF programs](../requirements/r00016-the-c2m2-model-will-support-information-relating-species-terms-to-cf-programs.md)
-   [R00017 The catalog will store information relating species terms to CF programs](../requirements/r00017-the-catalog-will-store-information-relating-species-terms-to-cf-programs.md)


#### T0012 Search/filter Common Fund Programs by type terms

-   [R00006 The interface will support the selection of an assay type term of interest](../requirements/r00006-the-interface-will-support-the-selection-of-an-assay-type-term-of-interest.md)
-   [R00007 The C2M2 model will support information relating assay types to CF programs](../requirements/r00007-the-c2m2-model-will-support-information-relating-assay-types-to-cf-programs.md)
-   [R00008 The catalog will store information relating assay types to CF programs](../requirements/r00008-the-catalog-will-store-information-relating-assay-types-to-cf-programs.md)

#### T0010 Visualize a table of all projects that match query

-   [R00012 The interface will render tables and plots to display filtered data](../requirements/r00012-the-interface-will-render-tables-and-plots-to-display-filtered-data.md)

#### T0003 Export a file of results

-   [R00014 The interface will support end user download of tables and figures in common formats](../requirements/r00014-the-interface-will-support-end-user-download-of-tables-and-figures-in-common-formats.md)
