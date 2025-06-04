# NymMatcher
Multilingual Name Matching for Entity Resolution Engine 

NymMatcher is an open-source toolkit for intelligent name matching, inspired by IBM Global Name Recognition. It supports:

✅ Alias and nickname resolution

🌐 Multilingual and transliterated name matching (e.g., Arabic, Cyrillic, Pinyin)

🧠 Fuzzy and phonetic matching (Soundex, Metaphone)

🧩 Honorifics, suffixes (Jr., Sr.), and cultural name order handling

⚙️ PySpark UDFs for scalable matching workflows

📁 Support for JSON/CSV name variant dictionaries

## Key Challenges in Multi-Part Name Matching
* Ordering Variations: “Smith John” vs “John Smith”
* Initials and Abbreviations: “J. Smith” vs “John Smith”
* Nicknames and Aliases: “Bob” vs “Robert”
* Missing Components: “John Smith” vs “John A. Smith”
* Typos or OCR Errors: “Jon Smith” vs “John Smith”
* Different Delimiters or Titles: “Mr. John Smith” vs “John Smith”

