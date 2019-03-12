# sap_mm

------------------------

### SAP Functional Intro

* SAP Solutions
  1. SAP Business Suite  
     - allows companies to manage their entire value chain and the most critical business process.
  2. SAP ERP  
     - provides functions for both corporate headquarters and small subsidiaries.
  3. SAP Business All-in-One  
     - for vertical( industry-specific or country-specific) solutions that are based on the technology of SAP Business Suite.
  4. SAP Business by Design  
     - most complete and adpatable on-demand business solution designed to liberate mid-size companies.
  5. SAP Business One  
     - comprehensive integrated ERP application with an interface that is similar to Windows
 
 * SAP GUI
 
 1. SAP Logon  
  *things to note*
    - saplogon.ini
      - This file is normally preconfigured centrally and made available to end users.   
    - Screen Structure
      - **Status Bar**
      - **Command Field**
      - Menu Bar
      - Standard Toolbar
      - Application Toolbar
 2. SAP Financials  
   SAP ERP Financials, which is part of the SAP ERP application, combines core accounting and financial reporting capabilities with 
   financial supply chain management, treasury management, performance management, and compliance management functions in a single, 
   integrated solution
   
* SAP terms
  - Customer Relationship Management (CRM)
    * concept of making the customer the focus and its business processes  
  - Production
    * SAP supports development and execution of efficient production plans 
   
   
* Procurement Cycle
  1. demand determination
  2. source determination
  3. supplier/vendor selection
  4. purchase order processing
  5. order monitoring
  6. goods receipt
  7. invoice verification
  8. payment processing 
  
  
* Important TCODES  
   - MEK1 - used for creating price condition
   - MK05 - Block Vendor
   - XK05 - surprise mrrfrr
   - ME9F - Purchase Order Message Output
   - ME9A - RFQ Messages

* Afternoon 110319
  - NACE -> Purchase Order -> Output type: ZNEU -> def vaule: dispatch time= send with application own transaction  
    * Go to condition records 
    * maintain for message output(?)
    
    
    
* NOTES
  - field selection = mandatory fields
  - number assignments e.g. 6 for contract, 4 for POs, 5 for mats etc.
  - item category
    - requires a mareial number
    - account assignment
    - is to be placed in stock
    - blank = standard
    - Standard | Limit | Consignment
  - RFQ Tcodes
    - ME41 creating RFQ
    - ME47 creating quotation
    - ME49 price comparison

* Consumable Materials
  - material that is subject to procurement and whose value is settled using the cost element  
    accounts or the asset accounts. Therefore, consumable material is procured  
    directly for an account assignment object.  
  - must manually enter a short desc, group & purchase order unit because no master data
  - Non-valuated Material (mat type UNBW)
    - is subject to inventory management on a quantity basis, but not on a value basis.
  - Non-stock material (NLAG)
    - use ofthis material type enables you to store the information required to create purchasing documents (
  
* Account Assignment Category
  - If you want to procure a material as a consumable, you must specify an account
assignment category and other account assignment data in the document item
of the purchase requisition or purchasing document.  
