# Findings

## Data Representation Analysis

During analysis, a numeric byte array was identified within the application code.

Example:
[116, 99, 112, 58, 47, 47, ...]

### Interpretation
- These values correspond to ASCII characters
- Example mapping:
  - 116 → t
  - 99 → c
  - 112 → p

### Result
The sequence translates into a readable string format:
tcp://<ip>:<port>

## Observation
- Application data may contain embedded strings in encoded or numeric form
- Such data can be interpreted through static analysis

## Security Perspective
- Hardcoded or embedded values can expose internal logic
- Understanding encoding helps in analyzing application behavior

## Conclusion
This exercise demonstrated how static analysis can reveal meaningful information from compiled application data.