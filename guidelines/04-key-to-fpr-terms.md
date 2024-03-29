###### [FPR Home](../README.md) `|` [Preferred and acceptable formats](../fpr/00-fpr.md) `|` Guidelines
###### [Overview](00-guidelines.md) `|` [File Formats](01-file-formats.md) `|` [Format Obsolescence](02-format-obsolescence.md) `|` [Preservation Strategies](03-preservation-strategies.md) `|` Key to FPR Terms

# Key to FPR Terms
This pages provide a fuller explanation terms used in the [list of preferred and acceptable file formats](../fpr/00-fpr.md) section of the FPR.
- [Designated formats](#designated-formats)
  - [Preservation formats](#preservation-formats)
  - [Access formats](#access-formats)
- [Transfer status](#transfer-status)
  - [Preferred formats](#preferred-formats)
  - [Acceptable formats](#acceptable-formats)
  - [Do not transfer](#do-not-transfer)
  - [Other formats](#other-formats)
- [Levels of support](levels-of-support)
  - [Bit-level](#bit-level)
  - [Watch](#watch)
  - [Normalize](#normalize)
  - [Full](#full)
  - [Comparison of levels of support](#comparison-of-levels-of-support)

## Designated formats
Designated formats are those into which other files of a similar type are normalized for preservation and access purposes. When evaluating formats, the Archives looks for certain characteristics which are different for the two types.

### Preservation formats
**Preservation formats** must be able to capture the significant properties of the original files with no or minimal loss. Other important aspects are:
- Uncompressed or lossless compression: this protects against the dangers of [bit rot](https://en.wikipedia.org/wiki/Data_degradation); with lossy compression, the loss of even a few bits can make the file unrecoverable.
- Stability: the format does not frequently change or changes are backwards-compatible.
- Support: the format is widely adopted by users, with readily available software tools and viewers.
- Openness: a technical specification is freely available, not a propriety, commercial secret.

### Access formats
**Access formats** are intended for easy delivery to users; lesser file quality and greater loss of features may be acceptable for access purposes, given that a preservation copy is also typically available to users who need a higher-quality copy. Important features are:
- Compact: file sizes support easy transmission over the internet.
- Support: the format is widely adopted by consumers, with readily available software tools to render / view files.

## Transfer status
**Transfer status** indicates how SFU Archives views a particular file format. There are three options: [preferred](#preferred-formats), [acceptable](#acceptable-formats), and [do not transfer](#do-not-transfer).

### Preferred formats
These are the formats in which SFU Archives would like to receive file from producers (university departments and private donors). Ideally, producers will themselves convert other files to these formats before transferring the materials to Archives. **Preferred formats** are typically themselves already [preservation formats](#preservation-formats) or ones that may be easily normalized to [preservation formats](#preservation-formats) with minimal loss.

### Acceptable formats
These are formats SFU Archives will accept from producers who are not able to provide the records in the preferred formats. We recognize that it is not always feasible for producers to make file conversions themselves. **Acceptable formats** are ones for which the Archives has a preservation plan or they may be widely used [watched formats](#watch) which the Archives will monitor as it develops a plan.

### Do not transfer
These are formats SFU Archives **will not accept** from producers because we have no means of preserving them and are unlikely to develop such a means in the future. The main examples here are pointer files: files that merely provide a link to the actual files that are themselves the objects for long-term preservation. [Google Document Link Files](https://www.nationalarchives.gov.uk/PRONOM/fmt/1073) (`gdoc`, `gdraw`, `gform`, `gmap`, `gsheet`, `gsite`, `gslides`) are examples and the only formats we currently explicitly designat for rejection. These files link to documents that reside somewhere on Google Drive and the links will not work if the documents are removed. The Archives and its users, moreover, typically do not have access to the producers' Google Drive; producers wishing to transfer these should first export them from Google Drive, then transfer those files to the Archives. When shown in the FPR, pointer files will usually have their [Level of support](#level-of-support) set as "Cannot be preserved".  

### Other formats
**Formats not appearing the FPR can still be transferred to Archives.** But typically if they do not appear on the FPR, it is because the Archives does not currently have a full preservation plan for that format to ensure they will continue to be accessible in the future. Usually this means we can provide only [watch](#watch) or [bit-level](#bit-level) preservation support. The Archives does in fact have many file formats in its holdings that do not appear on the FPR. Over time we will develop preservation plan for many of these; they will be added to the FPR as that happens.

## Levels of support
**Level of support** refers to the Archives' current capacity to preserve (i.e. render accessible in the future) files of a particular format.

### Bit-level
The Archives will preserve the file in its original format, but does not normalize it to a designated preservation format. This means that we preserve the string of 0s and 1s (bits) that make up the file, storing it on our own secure servers and monitoring its integrity to ensure that it does not suffer corruption (inadvertent changes to or loss of individual bits). The original file will always be available, but if the file format is uncommon or proprietary (or both) and has become obsolete, we may not be able to render it accessible in the future.

### Watch
When a format is on our **watch list** it means that the format may be proprietary, but its prevalence indicates a high likelihood of industry support in developing the ability to preserve it. There may also be development due to an industry need, such as with the CAD drawings used by architects and designers that often need to be retained for very long periods of time (e.g. life a building). The Archives may also develop its own tools and / or workflows to normalize watched formats to designated preservation and access formats.

### Normalize
These formats will be routinely migrated to (i.e. copies made in) different formats that have been designated for preservation and / or access. When a format is listed in the FPR for **normalization**, it typically means that the Archives' preservation system (Archivematica) has the tools to automate the conversion, with no manual intervention by an archivist required.

### Full
When a format is itself a designated [preservation format](#preservation-format), we say that its preservation is **fully supported**. Preservation formats will themselves change over time (but hopefully infrequently) and require migration by future archivists. But this will be a controlled process and the new formats chosen will themselves have to preserve the significant properties of the originals.

### Comparison of levels of support
| Action performed | Bit-level | Watch  | Normalize | Full  |
| :---             |   :---:   | :---:  |   :---:   | :---: |
| Generate metadata to support preservation, access, authenticity, and provenance | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Regularly refresh/replace storage media | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Make available on SFU Atom as restrictions allow | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Secure encryption of digital records (AIPs) and their associated metadata | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Regularly perform fixity checks on AIPs | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Watch the format for evolving ability to preserve	| | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Perform normalization as necessary |  |  | :heavy_check_mark: | :heavy_check_mark: |
| Offer long-term storage in a preservation format |  |  |  | :heavy_check_mark: |
| Plan to migrate format upon obsolescence |  |  |  | :heavy_check_mark: |

###### Last updated: May 3, 2021
