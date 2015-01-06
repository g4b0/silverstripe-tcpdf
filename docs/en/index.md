# TCPDF

## Overview

This module provides an action to convert and download a page as a PDF document.

The PDFControllerExtension provides the function PDFLink() that generates a url for the 'Save as pdf' html anchor. The filename of the generated PDF document is based on the page title.

## Usage

1. Load the PDFControllerExtension in your mysite/_confg/config.yml configuration file:

  ```yml
  Page:
    extensions:
      - PDFControllerExtension
  ```

2. Create a layout template called Page_pdf.ss in your theme templates directory:

  /themes/--your-theme-name--/templates/Page_pdf.ss

3. Place a link in your templates to call the 'save to pdf' action:

  ```html
  <a href="$PDFLink" title="Download this page as a PDF document">Save as PDF</a>
  ```
