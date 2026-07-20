**Encoding in Machine Learning**

**Why Encoding?**

• Machine learning models are designed with mathematical formulas accepting only numericvectors.

• Categorical (non-numeric) data, such as strings or categories, must be converted before modelinput.

**What is Encoding?**

• Encoding is the process of converting categorical columns into numerical or vector representationsto ensure compatibility with ML algorithms.

**Types of Encoding**

**One-Hot Encoding**

• Used for nominal (unordered) categorical data (e.g., gender, country).

• Each unique category becomes a new binary column (N unique values = N-1 columns afterdropping one for redundancy).

• Example: Gender column with values Male/Female becomes gender_male and gender_femalecolumns; one is dropped (alphabetically first) to avoid duplication.

• Can be implemented using Pandas' get_dummies or sklearn's OneHotEncoder .

**Label Encoding**

• Assigns a unique integer to each category.

• Suitable for both nominal and ordinal data, but use with care: only use for ordinal columns withalgorithms that naturally handle ordinal relations.

• More memory-efficient than one-hot encoding, especially for columns with many unique values.

• Implemented via sklearn’s LabelEncoder (for nominal data) or pd.map(for custom ordinal mappings).

**Train-Test Splitting**

**Concept**

• After encoding, data is split into training and testing sets (commonly 70-30 or 80-20 splits).

• Use train_test_split from sklearn's model_selection with specified test size andrandom_state for reproducibility.

• Demonstrated that consistent random state ensures the same split across runs.

• Discussed the importance of stratification to ensure representative samples from the population.

**Best Practices**

• Separate dependent (target) and independent (feature) variables before splitting.

• Use standard variable names ( X_train , X_test , y_train , y_test ) for clarity and consistency.

**Additional Insights and Best Practices**

**APIs in Python ML**

• Explanation of APIs (Application Programming Interfaces) as intermediaries and enablers forpowerful abstractions in Python libraries (e.g., sklearn, pandas, numpy).

• Encourages using official documentation and understanding how to connect with APIs for efficientcode.

**Implementation Tips**

• Prefer three-liner splits using train_test_split(X, y) for simpler, error-free code.

• Order matters in variable unpacking when passing arguments to splitting functions.

• Dropping the correct columns and combining features reduce errors in preprocessing.
