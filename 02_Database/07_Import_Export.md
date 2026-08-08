# Import Export

Repositories

https://github.com/pandas-dev/pandas

https://github.com/ericgazoni/openpyxl

Study

Excel import

CSV import

Bulk import

Bulk update

Excel export

CSV export

PDF export

# Verified Import and Export Standards

Claude should provide safe and reliable data import and export functions.

## Supported Formats

Where appropriate, applications may support:

- CSV
- XLSX
- XLS
- JSON
- PDF
- TXT

The supported formats should depend on the purpose of the application.

## Import Process

A typical import process should be:

Select File
      ↓
Detect Format
      ↓
Read Data
      ↓
Validate Data
      ↓
Preview Records
      ↓
Confirm Import
      ↓
Save to Database
      ↓
Show Import Summary

## Import Preview

Before saving imported records, show the user:

- Number of records found
- Valid records
- Invalid records
- Duplicate records
- Missing required fields
- Data type errors

Users should be able to review problems before confirming the import.

## Validation

Imported data must be validated before it reaches the database.

Check:

- Required fields
- Data types
- Dates
- Numbers
- Email addresses
- Duplicate records
- Foreign-key relationships
- Allowed values

Invalid records should not silently enter the database.

## Import Error Report

After an import, provide a clear summary.

Example:

Records found: 500
Imported: 472
Duplicates: 18
Invalid: 10

The user should be able to view the records that failed and the reason for each failure.

## Export Process

A typical export process should be:

Select Data
      ↓
Apply Filters
      ↓
Select Format
      ↓
Preview
      ↓
Export
      ↓
Save File

## Export Formats

Where appropriate, support:

- CSV
- XLSX
- JSON
- PDF

## Export Filters

Users should be able to export:

- All records
- Selected records
- Filtered records
- Records within a date range
- Records belonging to a selected category

## Large Exports

Large exports should not freeze the user interface.

Use a background worker where the operation may take significant time.

Show progress where appropriate.

## File Safety

Before importing a file:

- Confirm that the file exists.
- Check the file type.
- Handle corrupt files.
- Handle unsupported formats.
- Avoid importing executable files.
- Prevent unsafe file paths.

## Database Transactions

Database imports involving multiple records should use transactions where appropriate.

If a critical operation fails, the application should roll back affected changes rather than leaving incomplete data.

## Duplicate Handling

The application should define how duplicates are handled.

Possible options include:

- Skip duplicates
- Update existing records
- Create new records
- Ask the user

The chosen behaviour should be clear before the import is completed.

## Import and Export History

For important applications, record:

- User
- File name
- Operation
- Date
- Time
- Number of records
- Successful records
- Failed records
- Status

## Import and Export Checklist

☐ CSV import tested
☐ XLSX import tested
☐ JSON import tested where required
☐ Data validation tested
☐ Duplicate handling tested
☐ Invalid records reported
☐ Import preview implemented
☐ CSV export tested
☐ XLSX export tested
☐ PDF export tested where required
☐ Large exports tested
☐ Database transaction tested
☐ Import history tested
☐ File errors handled
