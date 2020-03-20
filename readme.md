# Google Spreadsheet to JSON API service.

## Install

- Run `npm install`
- Run `node app`

## Usage

```
http://localhost/api?id=SPREADSHEET_ID&sheet=SHEET_NUMBER
```

### Parameters

**id (required):** The ID of your document.

**sheet (optional):** Your first sheet is 1, your second sheet is 2, etc. If no sheet is entered then 1 is the default.

**q (optional):** A simple query string.

**integers (optional - default: true)**: Setting 'integers' to false will return numbers as a string.

**rows (optional - default: true)**: Setting 'rows' to false will return only column data.

**columns (optional - default: true)**: Setting 'columns' to false will return only row data.
