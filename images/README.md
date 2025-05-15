# Images Directory

This folder contains all image and PDF files related to certificates displayed on the website.

## Purpose

The files in this directory are dynamically loaded on the `certificates.html` page using JavaScript. The filenames and descriptions are listed in the `certificates.json` file.

## Structure

- Certificate images (`.png`, `.jpg`, `.jpeg`, etc.)
- Certificate PDFs (`.pdf`)

## Usage

1. Add any new certificate images or PDFs to this folder.
2. Update the `certificates.json` file to include a new entry for each file:
   ```json
   {
     "file": "new_certificate.png",
     "desc": "Description of the new certificate"
   }
