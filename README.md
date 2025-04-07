 Key Steps in Data Cleaning**
1. **Handling Missing Values**:
   - Identified 24 missing values in `Income` and filled them with "unknown" .
2. **Removing Duplicate Rows**
   - removed duplicate rows exist in dataset

3. **Data Standardization**:
   - Converted `Dt_Customer` to datetime format.
   - Formatted categorical columns (`Education`, `Marital_Status`) to title case.

4. **Feature Engineering**:
   - Added `Age`: Calculated as `current_year - Year_Birth`.
   - Added `Customer_since_days`: Years since customer enrollment.
