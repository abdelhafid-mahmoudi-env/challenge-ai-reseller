# Challenge: Building an AI to Filter Emails and Extract Data  

## Objective  
We’re creating an AI solution to process incoming emails, classify them into predefined types, and extract relevant information.  

## Requirements  
1. **Email Classification**  
   - Identify predefined types of emails (e.g., "price request").  

2. **Data Extraction**  
   - Extract specific fields from the email body, such as:  
     - **Reference**  
     - **Description**  
     - **Quantity**  
     - **Unit**  
     - **Customer specifications** (e.g., budget).  

3. **Attachment Analysis**  
   - Analyze attached documents (e.g., PDFs, Excel files) to extract the same required data if it is not present in the email body.  

## Challenges  
- Handling unstructured or messy email content.  
- Processing various document types and formats (scanned PDFs, complex Excel tables, etc.).  
- Ensuring high accuracy in classification and data extraction.  

## Tools and Techniques  
- **Email Parsing**: Extracting content and attachments from emails.  
- **NLP Models**: Using pre-trained models or custom-trained models for classification and data extraction.  
- **Document Processing**: Libraries for reading and extracting structured data from PDFs and Excel files.  

## What We’ve Tried  
- Python libraries like `email`, `mail-parser`, `PyPDF2`, and `pandas`.  
- OpenAI GPT for email body classification and data extraction.  
- Basic regular expressions for structured data extraction.  

## Goal  
To build a robust system that can handle noisy, semi-structured, or unstructured data from both email bodies and attachments, ensuring accuracy and reliability.  
