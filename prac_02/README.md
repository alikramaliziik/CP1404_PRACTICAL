# Practical 2 – Functions and the Single Responsibility Principle

## Programs

| File | Description |
|------|-------------|
| `scores.py` | Evaluated a user score and a random score using a shared `get_score_result()` function |
| `score_menu.py` | Menu-driven score manager — get, print result, show stars, quit — all split into focused functions |
| `temperatures.py` | Temperature converter refactored into `convert_celsius_to_fahrenheit()` and `convert_fahrenheit_to_celsius()` functions |
| `password_stars.py` | Password validator that prints asterisks for the password length — `get_password()` and `print_asterisks()` separated cleanly |

---

## CP1404 Practical Reflection

**What percentage of the lecture videos have you watched so far?**  
70%

**What time, location and duration have you scheduled to watch lecture videos?**  
I watch them early in the morning at 6:00AM because I am most attentive at that time. Location is at my Brisbane home, duration is an hour, then I do practice exercises and practicals.

**What are you doing well in the subject so far that you will keep doing?**  
Writing proper functions with the SRP principles followed.

**What do you need to stop or change in your work for this subject overall so far?**  
So far I am seeing positive progress in my learning as I get to write code better. I don't see something to be changed as for now — with more learning I will be able to identify areas for improvement more clearly, and also with correction and guidance from my lecturer.

**What are you currently doing poorly for practicals in this subject that you will change?**  
Sometimes I forget to check for exceptions that allow the user to enter a value that does not work, and I only realise it when I go through the code again. I will practise writing code on paper more so I can think through edge cases thoroughly before typing.

**What are you doing really well for practicals in this subject?**  
Naming variables with proper, descriptive names that do not cause confusion, and structuring the format of functions well.

---

## Reflection – Practical 2

**1. What did you learn about functions this week?**  
I learned that functions should do one job only (Single Responsibility Principle). When each function has a clear, focused purpose — like `get_valid_score()` only getting and validating a score — the code becomes much easier to read, test, and reuse across different parts of the program.

**2. What was the hardest part?**  
The hardest part was structuring the menu code in `score_menu.py` and deciding what belonged in `main()` versus what should be its own function. It took a few iterations to get the separation right without making the code feel over-engineered.

**3. What did you enjoy or do well?**  
I liked how refactoring `temperatures.py` into functions made it instantly cleaner — the two conversion functions are short, readable, and could be reused anywhere. I also did well keeping `main()` as a coordinator rather than putting all the logic directly inside it.

**4. What would you change or do better next time?**  
Next time I will plan my functions before writing any code — sketch out the function names, their inputs, and what they return. Starting from that design first should make the actual writing faster and more organised.

**5. How do you feel about using Git and GitHub?**  
Git is a bit tricky at first but I can see how it helps to save and track versions of my work. I am slowly getting more comfortable with committing and pushing, and I want to make a habit of committing after each working milestone rather than at the very end.
