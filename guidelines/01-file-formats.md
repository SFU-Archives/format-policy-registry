###### [FPR Home](../README.md) `|` [Preferred and acceptable formats](../fpr/00-fpr.md) `|` Guidelines
###### [Overview](00-guidelines.md) `|` File Formats `|` [Format Obsolescence](02-format-obsolesence.md) `|` [Preservation Strategies](03-preservation-strategies.md) `|` [Key to FPR Terms](04-key-to-fpr-terms.md)

# File Formats
**File format** refers to the way information is encoded in a digital file. Different formats require different software to open and read / render the file so that users can view or interact with its contents.

A file format can be identified by the **extension** that comes after the name of a document, like so:
- `Letter to the president.doc` (extension = "doc" = Microsoft Word document).
- `Budget2017.xlsx` (extension = "xlsx" = Microsoft Excel spreadsheet).

Extensions, however, are not always reliable markers of format. Users can manually change them to an incorrect value. The same extension may be shared by historically different software programs. And the same extension can cover a large number of incompatible versions of the same format.

Programs and file format identification tools typically rely not on the file's extension but instead on its **file format signature**, a string of code in the document's **file header** section (hidden from visual display) that identifies the file's format.

Formats may be **proprietary** (owned by a person or corporation and protected by license or patent) or **open-source** (freely available under a less restrictive license). Formats are typically associated with a **specification** that documents how the code works and can be rendered by software. Specifications can be **open** (freely available) or **closed** (commercial trade secrets). It is possible to have a proprietary format with an openly published specification.

There are thousands of different file formats, past and present, and new ones will continue to be created. Most formats, moreover, evolve over time and are associated with multiple versions. [PRONOM](https://www.nationalarchives.gov.uk/PRONOM/) is an online database maintained by the [UK National Archives](https://www.nationalarchives.gov.uk) that acts as a register of formats and their signatures. PRONOM assigns unqiue identifiers (puids) to each format version, and as of May 2021 had about 1900 entries.  PRONOM IDs are widely used by digital preservation software, including file characterization tools such as DROID, FITS, and Siegfried.

###### Last updated: May 3, 2021
