# Java String
In Java, strings are immutable objects provided by the `String` class, which comes with a rich set of methods to perform various operations. Here is a comprehensive list of operations you can perform on a string:

1. **Creating Strings**:
   - Direct assignment: `String str = "hello";`
   - Using `new` keyword: `String str = new String("hello");`
   - From `char` array: `String str = new String(charArray);`
   - From byte array: `String str = new String(byteArray);`

2. **Concatenation**:
   - Using `+` operator: `String result = str1 + str2;`
   - Using `concat()` method: `String result = str1.concat(str2);`

3. **Length**:
   - `int length = str.length();`

4. **Character Access**:
   - Single character: `char ch = str.charAt(index);`
   - Characters array: `char[] charArray = str.toCharArray();`

5. **Substring**:
   - Substring from index: `String substr = str.substring(beginIndex);`
   - Substring with end index: `String substr = str.substring(beginIndex, endIndex);`

6. **Comparison**:
   - Equals: `boolean equals = str1.equals(str2);`
   - Equals ignoring case: `boolean equalsIgnoreCase = str1.equalsIgnoreCase(str2);`
   - Compare lexicographically: `int cmp = str1.compareTo(str2);`
   - Compare lexicographically ignoring case: `int cmpIgnoreCase = str1.compareToIgnoreCase(str2);`
   - Region matches: `boolean matches = str1.regionMatches(start1, str2, start2, length);`

7. **Searching**:
   - Index of character: `int index = str.indexOf('c');`
   - Index of substring: `int index = str.indexOf("substring");`
   - Last index of character: `int lastIndex = str.lastIndexOf('c');`
   - Last index of substring: `int lastIndex = str.lastIndexOf("substring");`
   - Contains: `boolean contains = str.contains("substring");`
   - Matches regular expression: `boolean matches = str.matches(regex);`

8. **Modification**:
   - Replace characters: `String result = str.replace('oldChar', 'newChar');`
   - Replace substring: `String result = str.replace("oldSubstring", "newSubstring");`
   - Replace all using regex: `String result = str.replaceAll(regex, replacement);`
   - Replace first using regex: `String result = str.replaceFirst(regex, replacement);`

9. **Case Conversion**:
   - To lowercase: `String lower = str.toLowerCase();`
   - To uppercase: `String upper = str.toUpperCase();`

10. **Trimming**:
    - Trim whitespace: `String trimmed = str.trim();`

11. **Splitting**:
    - Split by regex: `String[] parts = str.split(regex);`
    - Split by regex with limit: `String[] parts = str.split(regex, limit);`

12. **Joining**:
    - Using `String.join()`: `String joined = String.join(delimiter, elements);`

13. **Formatting**:
    - Using `String.format()`: `String formatted = String.format(format, args);`

14. **Conversion**:
    - To `char` array: `char[] charArray = str.toCharArray();`
    - To `byte` array: `byte[] byteArray = str.getBytes();`
    - Value of various types to string: `String str = String.valueOf(value);`

15. **Other Utility Methods**:
    - Check if empty: `boolean isEmpty = str.isEmpty();`
    - Check if blank: `boolean isBlank = str.isBlank();` (Java 11 and above)
    - Repeat: `String repeated = str.repeat(count);` (Java 11 and above)
    - Strip: `String stripped = str.strip();` (Java 11 and above)
    - Strip leading: `String leadingStripped = str.stripLeading();` (Java 11 and above)
    - Strip trailing: `String trailingStripped = str.stripTrailing();` (Java 11 and above)
    - Indent: `String indented = str.indent(n);` (Java 12 and above)
    - Transform: `String result = str.transform(func);` (Java 12 and above)
    - Lines: `Stream<String> lines = str.lines();` (Java 11 and above)
    
