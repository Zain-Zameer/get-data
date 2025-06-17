# 📄 README.md

## 🔍 Sample Regex Expressions for Natural Language Command Extraction

This file contains 40 regex expressions for extracting command arguments from user input in NLP-based applications.
--- 

# 1. Load file
pattern = r'load\s*"([^"]+)"'

# 2. Save file
pattern = r'save\s*"([^"]+)"'

# 3. Ask question
pattern = r'ask\s+"([^"\n]+)'

# 4. AI request
pattern = r'@ai\s+"\s*([^"]*?)\s*"'

# 5. Explain command
pattern = r'@explain\s+"([^"]+)"'

# 6. Filter condition
pattern = r'filter\s+"([^"\n]+)'

# 7. Visualize chart
pattern = r'visualize\s+"([^"\n]+)'

# 8. Plot graph
pattern = r'plot\s+"([^"]+)"'

# 9. Read file path
pattern = r'read\s+"([^"]+)"'

# 10. Export CSV
pattern = r'export\s+to\s+"([^"]+\.csv)"'

# 11. Describe column
pattern = r'describe\s+column\s+"([^"]+)"'

# 12. Summarize data
pattern = r'summarize\s+"([^"]+)"'

# 13. Find average
pattern = r'average\s+"([^"]+)"'

# 14. Max value
pattern = r'max\s+"([^"]+)"'

# 15. Min value
pattern = r'min\s+"([^"]+)"'

# 16. Replace value
pattern = r'replace\s+"([^"]+)"\s+with\s+"([^"]+)"'

# 17. Rename column
pattern = r'rename\s+column\s+"([^"]+)"\s+to\s+"([^"]+)"'

# 18. Drop column
pattern = r'drop\s+column\s+"([^"]+)"'

# 19. Drop row
pattern = r'drop\s+row\s+(\d+)'

# 20. Add column
pattern = r'add\s+column\s+"([^"]+)"'

# 21. Count rows
pattern = r'count\s+rows'

# 22. Count columns
pattern = r'count\s+columns'

# 23. Unique values
pattern = r'unique\s+in\s+"([^"]+)"'

# 24. Sort by column
pattern = r'sort\s+by\s+"([^"]+)"'

# 25. Sort by column descending
pattern = r'sort\s+by\s+"([^"]+)"\s+desc'

# 26. Select column
pattern = r'select\s+column\s+"([^"]+)"'

# 27. Select columns
pattern = r'select\s+columns\s+"([^"]+)"'

# 28. Add row
pattern = r'add\s+row\s+"([^"]+)"'

# 29. Fill null
pattern = r'fill\s+null\s+in\s+"([^"]+)"\s+with\s+"([^"]+)"'

# 30. Group by column
pattern = r'group\s+by\s+"([^"]+)"'

# 31. Merge files
pattern = r'merge\s+"([^"]+)"\s+and\s+"([^"]+)"'

# 32. Join tables
pattern = r'join\s+"([^"]+)"\s+with\s+"([^"]+)"'

# 33. Convert to JSON
pattern = r'convert\s+to\s+json'

# 34. Convert to CSV
pattern = r'convert\s+to\s+csv'

# 35. Extract year
pattern = r'extract\s+year\s+from\s+"([^"]+)"'

# 36. Extract month
pattern = r'extract\s+month\s+from\s+"([^"]+)"'

# 37. Filter greater than
pattern = r'filter\s+"([^"]+)"\s*>\s*(\d+)'

# 38. Filter less than
pattern = r'filter\s+"([^"]+)"\s*<\s*(\d+)'

# 39. Filter equals
pattern = r'filter\s+"([^"]+)"\s*==\s*"([^"]+)"'

# 40. Help command
pattern = r'help'
