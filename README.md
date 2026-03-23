**Address Cross-Reference & Validation Pipeline**
- This project builds a robust data validation pipeline for cross-referencing and verifying address data (city, state, and ZIP) across multiple datasets. It standardizes and cleans raw inputs, performs fuzzy matching to detect inconsistencies, and leverages geolocation APIs to validate and correct inaccurate records.
    Key features include:
    --  Data normalization & cleaning (ZIP formatting, state standardization, text normalization)
    -- Fuzzy matching using Levenshtein distance for resilient comparisons
      Cross-dataset validation to identify mismatches in city, state, and ZIP fields
      Geolocation verification via Nominatim/OpenCage APIs for real-world accuracy checks
      Error classification & correction suggestions for improved data quality
    Designed for large-scale address validation workflows, this tool helps ensure consistency and accuracy in location-based datasets.
