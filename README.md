# ELEVATE-LABS-tasks

Loaded the Netflix dataset using pandas.
Handled missing values:
Filled director and cast with 'Unknown'.
Filled country and rating with the most frequent value (mode).
Converted date_added to datetime and filled missing dates with a default value (01-01-2000).
Filled duration with 'Unknown'.
Removed duplicate rows using .drop_duplicates().
Standardized text values like country names using string cleaning.
Converted date formats (date_added) to datetime type.
Renamed column headers to lowercase and replaced spaces with underscores.
Checked and fixed data types, ensuring release_year is numeric.
