# Practical 5 – Dictionaries and String Operations

## Programs

| File | Description |
|------|-------------|
| `state_names.py` | Looks up full Australian state names from abbreviations using a constant dictionary with `try/except KeyError` for invalid entries |
| `hex_colours.py` | Colour-to-hex lookup program using a dictionary constant, with formatted column output for all available colours |
| `emails.py` | Extracts a name from an email address using string splitting and `.title()`, then stores email-to-name mappings in a dictionary |
| `word_occurrences.py` | Counts how many times each word appears in a user-input string, using a dictionary and `try/except KeyError`, then prints sorted aligned results |
| `wimbledon.py` | Reads a CSV of Wimbledon champions, counts wins per player using a dictionary, gets unique countries using a set, and displays formatted results |
| `kivy_layout.kv` | Kivy layout file introducing the basics of GUI design with Python |

---

## Reflection – Practical 5

**1. What did you learn about dictionaries this week?**  
I learned that dictionaries are the right tool when you need to map one thing to another — abbreviation to full name, email to person, word to count. The `dict.get()` method was useful for counting without needing a separate `if` check first. I also learned that `try/except KeyError` is cleaner than checking `if key in dict` every time you do a lookup.

**2. What was the hardest part?**  
`wimbledon.py` was the hardest — it combined file reading, a dictionary for counting, a set for unique countries, and formatted output all in one program. Keeping each responsibility in its own function (`read_wimbledon_data`, `count_champions`, `get_unique_countries`, `display_results`) was the right approach but required planning before writing.

**3. What did you enjoy or do well?**  
I enjoyed `emails.py` — parsing a name out of an email address using `.split('@')`, `.replace()`, and `.title()` felt like real string manipulation rather than a textbook exercise. I did well keeping the `extract_name_from_email()` function focused and reusable, and handling the confirmation step cleanly inside `main()`.

**4. What would you change or do better next time?**  
I went over my time estimates on most programs this week — `emails.py` took 35 minutes instead of 20, and `wimbledon.py` took an hour instead of 40 minutes. Next time I will break programs into functions on paper first before typing, which should cut down on restructuring time mid-way through.

**5. How do you feel about using Git and GitHub?**  
I am getting more comfortable. I now commit after each program is working rather than at the end of the session, which makes the history more meaningful. I want to work on writing clearer commit messages that describe what changed and why.
