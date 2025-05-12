
Step 1: Identify & Handle Missing Values
- Use Filters to highlight blank cells.
- Fill missing values with defaults (e.g., “Unknown” for categorical fields, or median values for numerical fields).
- Use Conditional Formatting to visually spot gaps.

Step 2: Remove Duplicates
- Go to Data → Remove Duplicates.
- Select relevant columns to check for duplicates.
- Review removed rows before finalizing changes.

Step 3: Standardize Text Values
- Use Find & Replace to fix inconsistent spelling (e.g., “Male” vs. “M”).
- Apply PROPER(), UPPER(), or LOWER() functions to standardize text formatting.

Step 4: Convert Date Formats
- Check date formats using Format Cells → Date.
- If formats vary, use TEXT() or Power Query for consistency (e.g., dd-mm-yyyy).

Step 5: Rename Columns for Consistency
- Ensure uniform naming (e.g., “Customer ID” → “customer_id”).
- Avoid spaces and special characters.
- Use Data → Power Query → Transform Data to rename in bulk.

Step 6: Check & Fix Data Types
- Identify inconsistencies using Data → Data Validation.
- Convert numbers stored as text using TEXT TO COLUMNS or VALUE().
- Ensure age is numerical and dates are in datetime format.

