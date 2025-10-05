# Invoice Processing Automation

## Description
Automated solution to process PDF invoices using UiPath.  
Implements Dispatcher/Performer model, OCR/Document Understanding, data validation, and error handling.

## Features
- Extract invoice data from PDFs using OCR or Document Understanding.
- Dispatcher/Performer model with Queues & Transactions in Orchestrator.
- Data Validation and Business Rules.
- Exception handling (Business & System Exceptions) and Retry Mechanism.
- Results exported to Excel or Database.
- Email notifications for errors.

## Folder Structure
- Dispatcher/: Reads invoices and adds them to the queue.
- Performer/: Processes queue items.
- Assets/SampleInvoices/: Sample PDFs for testing.
- Config.xlsx: Dynamic configuration values.

## Skills / Technologies
UiPath Studio, REFramework, OCR, Orchestrator, Queues, Dispatcher/Performer, Excel, Email Integration, Exception Handling.
