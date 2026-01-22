## **Overview**

A radio services company manages sponsorship of weather and traffic broadcasts for local radio stations. Currently, staff manually prepare sponsorship schedules in Excel, rebuild the same data in **Lotus 1-2-3** on an aging machine, and then use a legacy program to generate affidavit PDFs for each sponsor. This process is slow, repetitive, error-prone, and dependent on obsolete software.

This project aims to **fully modernize and automate** the workflow through a web-based application delivered in two phases.

## Deliverables

* **Web application** with simple user management and security controls. As well as a secure upload tool.
* **Backend automation** that parses the Excel file and generates machine-readable schedule data.
* **Automated affidavit PDF generation**, one PDF per sponsor, listing:
  * Broadcast time
  * Date
  * Station
* **Download portal** for users to retrieve generated PDFs. See the example affiliate PDF file.

## Technologies

* Python 3.12+
* Django 6.0+ - Server side rendered application
* HTMX for UI interactivity where needed (no React or Vue or similar frameworks)
* TailwindCSS
* PostgreSQL

