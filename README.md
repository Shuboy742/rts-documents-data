# RTS Documents Data

This repository contains the Pune Municipal Corporation's Right to Service (RTS) document requirements for various services.

## Data Structure

The JSON file contains information about documents required for different municipal services organized by:

- **Department Name**: The municipal department (Drainage, Fire Brigade, Health, etc.)
- **Service Name**: Specific service offered by the department
- **Documents**: Array of required documents for each service

## Departments Available

1. **Drainage** - Sewage Connection services
2. **ENCROACHMENT** - Various encroachment permits
3. **Fire Brigade** - Fire safety NOCs and licenses
4. **Health** - Health-related licenses and registrations
5. **PTAX** - Property tax services
6. **Skysign** - Advertising and signage licenses
7. **Tree** - Tree cutting and maintenance
8. **Water** - Water connection services

## Usage

This data can be accessed via HTTP requests for automation workflows (n8n, etc.).

### Raw JSON URL
Once uploaded, the JSON file will be available at:
`https://raw.githubusercontent.com/Shuboy742/rts-documents-data/main/RTS_Service_Wise_Doc_List.json`

## Example Query
"What documents are required for sewage connection?"

**Answer**: 7 documents including maps, certificates, and permits.

## Data Source
Official Pune Municipal Corporation RTS (Right to Service) document list. 