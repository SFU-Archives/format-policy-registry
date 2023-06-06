###### [FPR Home](../README.md) `|` [Preferred and acceptable formats](../fpr/00-fpr.md) `|` Guidelines
###### [Overview](00-guidelines.md) `|` [File Formats](01-file-formats.md) `|` [Format Obsolescence](02-format-obsolescence.md) `|` Preservation Strategies `|` [Key to FPR Terms](04-key-to-fpr-terms.md)

# Preservation Strategies
Archivists are charged with permanently preserving and providing access to records of historic value. How can we ensure the continuing accessibility of digital records that were created using software that is now obsolete?

There are three main strategies:
1. [Software refresh](#1-software-refresh.md): continuously update the file to the current version of the same format.
2. [Normalization (format migration)](#2-normalization-format-migration.md): make a copy / convert file to a different format.
3. [Emulation](#3-emulation.md): rely on new software that mimics (emulates) the original hardware/OS/software environment of the original file.

SFU Archives mainly follows the second route (normalization). However, **we will always retain the digital object in its original format** alongside any normalized copies. This ensures that we will have it available for these other strategies in the future or, for that matter, for altogether new strategies that may later emerge.

## 1. Software refresh
This approach tries to ensure the ongoing accessibility of files by continually converting them to the latest version of the software that is supported in contemporary computing environments. For example, Microsoft Word documents with the older `doc` extension can be opened and saved with the newer `docx` extension.

There are two main problems with this. (i) Some significant properties of the original file may be lost on conversion to the newer format; this must be evaluated case-by-case. And (ii) with the Archives' current tools, software refresh is a manual, labour-intensive process; until it can be automated, it is not feasible on a large scale.

In general, this approach is better suited to records producers managing their digital records **prior to transfer to Archives**. Producers need to ensure that their current records are accessible in the formats they need for current business. Typically the time-span is relatively short and the number of format generations that need to be refreshed are small.

## 2. Normalization (format migration)
In this approach, the Archives designates a file format for long-term preservation and converts to it files of a similar type in other formats. For example, `bmp`, `pct`, `psd`, `tiff`, `tga` are all **raster image** file formats. By normalizing these to an uncompressed `tiff` file as a preservation format, we go from many formats to one, and need worry about only this one format for long-term management.

The format that users will see in our access system ([SFU AtoM](https://atom.archives.sfu.ca)) is not always the preservation format but rather a smaller, more transmittable format – an **access format**. In the case of photographs, the preservation format is `tiff` and the access format is `jpg`.

See the section on [Key terms](04-key-to-fpr-terms.md) for the characteristics SFU Archives looks for when selecting [preservation and access formats](04-key-to-fpr-terms.md#designated-formats) respectively.

Any format conversion will result in some loss of some feature(s) of the original. In selecting preservation and access formats, the Archives must be cognizant of the **significant properties** of the original that must be captured in the normalized versions. Losses that may be acceptable for the access copy may not be acceptable for the more demanding requirements for the preservation copy. Possible feature loss during normalization is another reason for always retaining files in their original formats as a hedge alongside any normalized copies.

Another difficulty for normalization as a strategy is that many proprietary formats require propriety software to bulk convert files to open preservation and access formats. For example, Microsoft Word files (proprietary closed format) can be converted in bulk to `pdf` (open format) using Adobe Acrobat proprietary software. But the Archives' preservation system ([Archivematica](https://www.archivematica.org/en/)) is an open-source software. As such, it cannot incorporate proprietary tools into its workflows. This means that we lack tools to reliably automate the conversion of Word documents to pdf. Archivematica can use an open-source application like LibreOffice to convert Word (`docx`) to OpenDocument (`odt`), then OpenDocument to `pdf`. But significant formatting losses or distortions may result from this process; these are fine for the **access copy** but not acceptable in a **preservation copy.**

For most proprietary formats, SFU Archives has **not yet** developed workflows for manual normalization outside Archivematica. Many of these files are for now simply retained in their original formats. In the [FPR](../fpr/00-fpr.md), many proprietary formats accordingly have [Watch](04-key-to-fpr-terms.md#watch) as their [Level of preservation support](04-key-to-fpr-terms.md#level-of-support). Normalization of proprietary formats remains a problem that the Archives must tackle case-by-case.

## 3. Emulation
This approach relies on developing special software that works in contemporary computing OS/hardware environments to mimic (emulate) older environments. This allows them to run now-obsolete software to open and read / render files in their original formats. The advantage here is that no format migration / normalization is required, and the user is able to interact with file contents in the same way users did in the original environment, with no loss of significant properties.

Emulation was initially pursued mainly for video games and digital works of art, where the reproduction of the original user experience is central to preservation. As a general strategy, its main disadvantages are that the emulator software itself can become obsolete and requires ongoing maintenance and investment to ensure it works with current computing environments; it presupposes ongoing access to a library of obsolete software programs that most institutions do not have; the user interface for obsolete programs is no longer familiar and may present steep learning curves to contemporary users; and it is difficult to acquire rights to discontinued proprietary software.

Given the nature of our holdings, SFU Archives has not to date pursued emulation as a strategy. A recent project led by Yale University, [Emulation as a Service Infrastructure (EAASI)](https://www.softwarepreservationnetwork.org/emulation-as-a-service-infrastructure/), has begun trying to address some of the general difficulties, and emulation may become a more feasible strategy. For some proprietary formats, it may offer a solution to the problem of having to manually normalize files. SFU Archives will be following these developments. The fact that we have retained files in their original formats along with any normalized copies means that we will be able to pursue emulation if / when it becomes viable for us.

###### Last updated: May 3, 2021
