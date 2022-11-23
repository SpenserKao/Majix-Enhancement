# Majix-Enhancement
Enhancing Majix

__Majix__ is a software tool licensed under Mozilla Public Licence 1.1 and
designed to convert __RTF__ input into __XML__ format. It converts __RTF__ styles and
some document characteristics into a __XML__ file conforming to a __DTD__-based
default template. Out of the default template, the names of the __XML__ tags
may be changed by the user. But an outstanding issue is its functionality of
fully converting bullets and numberings items into expected __XML__ elements:
the latest __Majix__ (version _1.2.2_, released _November 15, 2000_) cannot
recognise bullets and numberings items that are created with compliance of
__RTF__ specifications beyond version _1.3_.

This document proposes a solution that __Majix__ can be enhanced to
support bullets and numberings items that are created compliant with postversion
1.3 __RTF__ specifications.

The core of enhancement is the revision of two of __Majix__’s java classes
with two modified methods and 12 new ones. The test result suggests that
the enhancement meets the expectation of fully converting bullets and
numberings items into expected __XML__ elements.

A tech report file named _tr-2004-152-full.pdf_ gives more explanation.
