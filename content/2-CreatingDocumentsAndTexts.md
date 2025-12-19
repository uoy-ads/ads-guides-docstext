---
authors:
 - name: null
---

# 2 Creating Texts and Documents

## 2.1 General Considerations

Text files and documents are generally a component of a larger archive and often themselves document the project planning and requirements of a larger project. While little project planning in itself is required for the creation of a word processed document, there are a few considerations that should be borne in mind when creating these files:

* As previously discussed, ensure that embedded content such as images and spreadsheets are stored separately to the document. In addition to allowing such content to be securely stored in its native or archival format, separately storing such files also allows them to remain in their original size or resolution.
* Avoid including external links or dynamic content in documents as these links may be lost over time.
* If intending to save the final version of a document to PDF, ensure that the original format (e.g. Word .doc, OpenOffice .odt, etc.) is retained separately.
* Additionally, if saving to PDF, ensure that the file conforms to preferably PDF/A or PDF 1.4 standards. This includes making sure that the file is not secured, includes no javascript, video or audio content or compression and that all fonts and images are correctly embedded and that the file is correctly 'tagged'.

A more general consideration would be that creators should ensure, where possible, that the content of a document is complete and self explanatory. 

## 2.2 Formats

In addition to these general considerations, each application and file format (many of which can be created from the same application) offers different benefits. The table below aims to outline some of the common formats used to create text documents along with their associated applications and potential uses for long term preservation.

```{list-table}
:header-rows: 1

* - Format
  - Properties/Technologies
  - Description
  - Recommendations
* - .doc
  - A proprietary binary format from Microsoft Word.
  - A popular format and the default file format for all versions of MS Word from 1.0 through to 6.0, 95, and 97-2003. In addition to use within Word, the files can also be read in OpenOffice and can easily be converted to .pdf. Although backwards compatibility has been fairly good across versions of Word, the recent addition of service pack 3 to Microsoft Office Word 2003 has stopped support for versions 2.0 and earlier. From 2008 the specifications for a number of Microsoft binary file formats were made available from the Microsoft website as well as the British Library.
  - Though not suitable for archival preservation or dissemination it is popular format and thus convenient for archival deposit.
* - .docx
  - Part of the Office Open XML (OOXML) format created by Microsoft. An ECMA (ECMA-376 [2]) and ISO ([ISO/IEC 29500-1:2008](https://www.iso.org/standard/51463.html)) standard.
  - A relatively new format from Microsoft, released with Office 2007. They chose to develop their own specification (OOXML) rather than use the existing ODF international standard ([ISO/IEC 26300:2006](https://www.iso.org/standard/43485.html), see ODT below) in order to provide better backwards compatibility with earlier MS Word file formats. The format consists of human readable XML files packed with other content within a single zipped file.
  - Suitable for deposit, dissemination and preservation though embedded content should be stored separately. The final file is essentially a zipped archive and may be best stored in an uncompressed format.
* - .rtf
  - RTF (Rich Text Format) is a tagged textual format developed by Microsoft.
  - Although a largely human readable plain text format, and therefore suitable for both presentation and preservation, there are compatibility issues regarding formatting (e.g. textboxes and tables) when opening files in different word processing packages. In addition, file size of an .rtf file is generally much larger than the equivalent .doc, .pdf or .odt file.
  - Although suitable for deposit and preservation, newer formats such as .docx and .odt provide a more compact and compatible format and should be used in preference to .rtf.
* - .odt
  - Open Document Text is part of the OpenDocument Format, an ISO standard ([ISO/IEC 26300:2006](https://www.iso.org/standard/43485.html)) for XML-based office document formats.
  - As with the .docx format, the .odt file is essentially a compressed zip file containing separate style, text (as XML) and embedded content (e.g. images) files.
  - As an open XML-based format, ODT is suitable for both deposit and preservation though, in the latter case, the files should be stored in their uncompressed form. Additionally, where the document contains images or other content, these should ideally be stored separately in a suitable preservation format.  
* - .sxw
  - Part of the OpenOffice.org XML format used by OpenOffice/StarOffice from version 1.0 to version 2.0. Superceeded by the OpenDocument Format.
  - Although this format has been superceeded by ODF, it is structured similarly (i.e. zipped XML files) to ODF and can still be read by OpenOffice.org 2.0.
  - Suitable for preservation but ODT should be used where possible.
* - .pdf
  - PDF (Portable Document Format), created by Adobe, is primarily an open standard exchange format. The format has evolved many times since its creation and has a number of variations, most notably PDF/A.
  - PDF is a format aimed at cross-platform document exchange. Although it is a proprietary binary format It is a highly suitable dissemination format as it is designed to retain the formatting of a document and the reader is both free and widely available. In addition to standard text, PDF documents are also capable of storing a range of other embedded or linked media including raster and vector images, javascript and even 3D data. In addition PDF files may be secured in order to limit further editing or printing.
  - Although an open standard, the PDF format is a proprietary binary format and is not ideal either for deposit or preservation. A report, 'Preserving the Data Explosion: Using PDF' [@fanning2008preserving], produced by the DPC highlights many of the issues involved in using PDF for preservation. In most cases a PDF file will be created from another format (e.g. .doc) and it is preferable to deposit and migrate from this original source. Where this is not possible then a migration path to PDF/A is often the best route though files should be checked to ensure that any embedded elements or security allow such a migration.
* - .pdf/a
  - Based on the PDF format and created by Adobe, the PDF/A format is aimed at providing an open standard for long term archiving.
  - Based on PDF version 1.4, PDF/A is aimed at providing a robust open-standard format for long-term archiving and is a published ISO standard ([ISO 19005-1:2005](https://www.iso.org/standard/38920.html)). In order to archive long-term reliability, the PDF/A format requires that certain document elements (fonts and colourspaces) are specified or embedded into the file while other (javascript, audio and video, encryption) are forbidden. The PDF/A format also has two levels of compliance, the basic level (PDF/A1-b) ensures that a document can be reliably visually reproduced while PDF/A1-a builds on this by including tagging/document structure. A useful overview of the PDF/A format has been written by the [Bentley Historical Library](https://deepblue.lib.umich.edu/items/99f40e2b-e7f2-4f34-8cc1-814d06ea1699) at the University of Michigan.
  - PDF/A has been widely accepted as a viable format for long-term preservation (e.g. [Library of Congress](https://www.loc.gov/preservation/digital/formats/fdd/fdd000125.shtml)) and has been widely reviewed by the digital preservation community (e.g. Fanning 2008). However, as with standard PDF files, it is recommended that where files are created from another format (e.g. .doc or .odt) that these are retained and deposited alongside the PDF/A file.
* - .wpd
  - A binary and proprietary format from WordPerfect.
  - The popularity of WordPerfect has declined significantly since its initial release in the early 1980s in response to the rise of its main competitor Microsoft Word. Although .wpd (also .wp or .wp5 etc. for earlier versions) is the main format, more recent versions of the software support a wide range of import and export options
  - Not recommended for preservation or dissemination. Although native to WordPerfect, .wpd files can also be read in Microsoft Office Word and OpenOffice. Current versions of WordPerfect Office also support the export (and import) of both ODF and OOXML files, it is therefore recommended that the latter XML-based open-standards are used.
* - .txt / plain text files
  - A simple plain text document. Plain text also forms the basis for marked-up texts (discussed below).
  - Plain text files are the "lowest common denominator encoding for textual information" [@wynne2005plain] and are widely compatible with a number of platforms and software. However, as a result, they support little in the way of formatting and can only be useful for the very simplest of documents. For all plain text files, an encoding (commonly US-ASCII or UNICODE) should be specified. Plain text files are covered in more detail in the AHDS Preservation Manual on Plain Text [@wynne2005plain].
  - Suitable for ingest, preservation and dissemination but only for extremely simple files.
```

__Marked up text formats__

Marked-up texts are dealt with in detail elsewhere in the AHDS Guide 'Creating and Documenting Electronic Texts: A Guide to Good Practice' [@morrison2001creating] and in the 'AHDS Preservation Handbook: Marked-up Textual Data' [@morrison2005ahds]. Although not commonly created for report-style documents (HTML is more commonly used for web-pages and XML for data exchange), a number of common marked-up text formats are outlined briefly below.

```{list-table}
:header-rows: 1

* - Format
  - Properties/Technologies
  - Description
  - Recommendations
* - .sgml
  - Standardised Generalised Markup Language (SGML). A certified ISO standard ([ISO 8879:1986 SGML](https://www.iso.org/standard/16387.html)) metalanguage.
  - SGML is a metalanguage used to define other markup languages such as HTML and XML
  - Suitable for preservation and dissemination though documents must be valid.
* - .html / .xhtml
  - Hypertext Markup Language (HTML) is a plain text based markup language developed as a subset of SGML and maintained by the W3C.
  - HTML is a markup language commonly used to create webpages. Aside from the plain text content of the HTML file (including either inline or linked stylesheets), websites generally consist of a wide range of linked media (images, video, audio, documents, etc.) which should be dealt with as separate objects.
  - Suitable for preservation and dissemination though documents must adhere to (and specify) a valid DTD and character encoding. Where used, CSS styles should either be specified within the document or supplied as a separate file. Images and other media should be dealt with as individual objects as per other guides.
* - .xml
  - Extensible Markup Language (XML) is a plain text based open standard produced by the W3C.
  - XML was developed as a subset of SGML and is generally used on the web and in exchanging data between systems (e.g. databases)
  - Suitable for preservation and dissemination though documents must adhere to (and specify) a valid DTD/schema and character encoding.
```

In terms of lifecycles, for the most part text files remain in the same format while they are being created. An exception to this would be the PDF format in that few documents are created originally in PDF, the vast majority coming from a word processed file (e.g. from Word or OpenOffice) which is then saved into PDF format for dissemination at the end of the authoring process.