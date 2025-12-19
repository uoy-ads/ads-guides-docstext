---
authors:
 - name: null
---

# 3 Archiving Texts and Documents

## 3.1 Deciding What to Archive

As mentioned previously, documents largely remain in a single format throughout their creation period with the exception of PDF files which are often created at the end of the process for dissemination purposes. In such cases it is recommended that both the original working document as well as the PDF file are retained. In addition, it is also recommended that embedded content such as images are stored separately to the text document in order that these files can follow a separate relevant preservation path.

Other more general considerations include ensuring that the file that is retained and preserved is the final version of the document. This may simply involve keeping careful track of working drafts but can also include ensuring that functions of certain word processing applications e.g. 'track changes' are turned off and that comments and notes are removed from the final version.

## 3.2 Deciding How to Archive

In deciding which formats are best to store your documents in for the long term it is wise to consider one that both preserves the significant properties of your document while also providing a format which can be readily accessed and, if needs be migrated, by various common applications.

__Significant Properties of Documents__

Generally, the significant properties of documents and texts that need to be preserved are:

* The words and order of the words in the document
* The hierarchical structure of the document (e.g. different levels of headings).
* Formatting within the document (e.g. bold or italicised text).
* The page numbering of a document. This is particularly important where a document is a published or unpublished report or thesis. If users wish to cite and reference the document then retaining the correct text on the correct page is important (particularly so if files go through subsequent migrations).
* Any other non-text content such as images and data tables. Ideally this content is best stored separately.

The properties that are generally not seen as significant are:

* The font type and font size (unless this significantly changes pagination or formatting).
* Track changes functionality.

Significant properties may however change depending on the exact nature of the document being preserved. All files should be assessed on a case-by-case basis in order to determine which of the above are relevant.

__File Formats__

In terms of file formats for preservation and long term stable storage there is a distinct preference to store and preserve documents in one of the now popular standardised XML formats such as Microsoft's OOXML (.docx) or OpenOffice ODF (.odt). A JISC Technology Watch Report, 'XML-based Office Document Standards' [@ditch2007xml], examines and compares these specifications in some detail. The main benefits of both formats are that they are recognised international open standards and are text-based (as opposed to binary files) and thus human readable. Both are mutually accepted by each of their native applications together with a number of third party applications such as Google Docs. Both formats are also similar in that they utilise a zipped archive format to contain the separate components that make up each file.

ODF does, however, make better use of other existing open standards (SVG for example). The available specification for ODF is also far shorter (and potentially more complete) than OOXML which suggests that third party support for this format might become more readily available. Microsoft's OOXML does, however, provide better support for migrations of earlier versions of MS Word (backwards compatibility was one of their major design goals) though format fidelity is not entirely accurate when converting from MS Word to ODF.

In addition to these XML-based formats, PDF/A should also be considered as a potential preservation format though primarily in cases where the original document only exists in a PDF format. Although a binary format, PDF/A is an open standard with a freely available reader and growing third-party support. As extracting or migrating content from PDF documents into other formats is problematic, PDF/A provides an effective means of accurately preserving existing PDF content in a recognised, albeit binary, open standard format.

```{list-table}
:header-rows: 1

* - Preservation Format
  - Requirements
* - .docx
  - Suitable for deposit, dissemination and preservation though embedded content should be stored separately. The final file is essentially a zipped archive and may be best stored in an uncompressed format.
* - .odt
  - Suitable for both deposit and preservation though, in the latter case, the files should be stored in their uncompressed form. Additionally, where the document contains images or other content, these should ideally be stored separately in a suitable preservation format.
* - .pdf/a
  - Suitable for long-term preservation. It is recommended that where files are created from another format (e.g. .doc or .odt) that these are retained and deposited alongside the PDF/A file.
* - .txt / plain text files
  - Suitable for ingest, preservation and dissemination but only for extremely simple files.
* - .sgml
  - Suitable for preservation and dissemination though documents must be valid.
* - .html / .xhtml
  - Suitable for preservation and dissemination though documents must adhere to (and specify) a valid DTD and character encoding. Where used, CSS styles should either be specified within the document or supplied as a separate file. Images and other media should be dealt with as individual objects as per other guides.
* - .xml
  - Suitable for preservation and dissemination though documents must adhere to (and specify) a valid DTD/schema and character encoding.
```


## 3.3 Metadata and Documentation

Although many documents are often self-explanatory, it is recommended that for resource discovery and provenance purposes some basic metadata is recorded for each individual or set of documents. There are a large number of long-standing metadata standards that have arisen from a wide variety of communities (e.g. [MARC](https://www.loc.gov/marc/) within the library sector) and each have their own strengths and weaknesses. Within the context of recording resource discovery and provenance metadata (rather than technical file metadata recorded by formats such as [textMD](https://www.loc.gov/standards/textMD/)) the metadata set described below aims to simply record a bare minimum but do so in a way which maps easily to other existing standards (most notably the fifteen elements of the [Dublin Core Metadata Element Set](https://www.dublincore.org/specifications/dublin-core/dces/)). With documents in particular, there is the tendency that an overlap may exist between project level metadata and that describing documents produced as a result of a project (e.g. reports describing the project).

```{list-table}
:header-rows: 1

* - Element
  - Description
* - Title
  - Title of document.
* - Abstract
  - Short description of document.
* - Date Published
  - Year of publication.
* - Published
  - Where relevant, the full location details of any published versions i.e. series/journal title, issue and volume number. Start and end page numbers or number of pages should also be recorded.
* - Publisher
  - Name of document publisher and location.
* - ISBN
  - [ISBN](https://www.isbn-international.org/) number (where applicable).
* - DOI
  - Digital Object Identifier ([DOI](https://www.doi.org/)) (where applicable).
* - URL
  - URL (where applicable).
* - Related files / resources
  - Details of related files or resources.
* - Language
  - The language (English, Spanish, etc.) used within the document. It is recommended that a controlled vocabulary (e.g. RFC 4646) is used and specified.
* - Author
  - Name of primary author(s).
* - Contributor
  - Names of contributors, should be qualified e.g. Editor, Translator, Contributor.
* - Email
  - Email address for author
```

In addition to the elements outlined above a number of other elements may need to be recorded at the document level. As mentioned previously, most of these elements may apply to a set of documents produced by a project and therefore be covered by project level metadata. They are therefore outlined here as optional elements to be used where documents produced by a project differ in scope.

```{list-table}
:header-rows: 1

* - Element
  - Description
* - Project name
  - Name of associated project.
* - Subject
  - Monument, site type, culture, object, material keywords. Maps to DC Subject
* - Investigation type
  - 
* - Spatial coverage.
  - Single point or series of points defining site extents, minimum and maximum latitude and longitude.
* - Temporal terms
  - Period keywords, start and end dates, C14 dates.
```


## 3.4 Structuring your data

As well as maintaining metadata and documentation on your files, there are a few simple steps that should be taken in order to ensure that your documents and related files remain as accessible as possible. Firstly it is important to ensure that project level metadata is recorded (see the introductory section on [Project Documentation and Metadata](https://doi.org/10.5284/h0p2-5584)) and that suitable file naming conventions are followed when creating your files (see [File Naming Conventions](https://doi.org/10.5284/h0p2-5584)). It is also important to ensure that any embedded objects that have been removed or stored separately to the main document can be related back to this file. Structuring your archive in such a way - e.g. creating a sub-folder for images - provides one route to linking extracted files back to their source as does document level metadata highlighting a relationship between the document and a set of related files/images stored elsewhere.
