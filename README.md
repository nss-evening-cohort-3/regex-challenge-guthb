# REGEX Challenge

### Goal

This lite exercise will help you gain practice in using regular expressions. While all problems require you to provide the proper regex, some will require you to also provide additional information or research the internet.

### Directions

It's recommended that the student uses https://regex101.com/ when attempting to solve the problem set. Answers for each exercise should be submitted in its own Markdown file that contains the answer and at least 3 variations test strings you used to test your regex works.

For example, exercise 3 the following will be included in a file named `3.md`:
```
# Regex
- /my regex/
- /my other regex/

# Test Strings
- a string
- some other string
- yet another
```

### Exercises

1. Provide three regexes that matches `yes yes yes` but not `no no no`
2. Provide a regex that matches valid phone numbers with the forms `678-123-1122` and `(678) 123-1122` while still allowing symbols to be optional. HINT: Research the rules around valid phone numbers.
3. Provide a regex that matches URLs like `https://regex101.com`, `http://facebook.com` and `https://www.godaddy.com` but not `https://msdn.microsoft.com`. (Trailing `/` should be allowed and optional)
4. Provide a regex that matches dates with the format: `Wed Aug 11, 2013`.
5. Provide a regex that matches dates with the format: `MM/DD/YYYY`. Use named captures to extract Day, Month and Year.
6. Provide a regex that matches `function returnOne() {return 1;}` and captures the value returned.
7. Provide a regex that matches `List<int> my_List = new List<int>();` and captures the variable name.
8. Provide two regeesx that matches `Billy Jean` but not `billy jean`.
9. Provide two regexes that matches `NSS Evening Cohort 3` and captures "Cohort 3".
10. Provide a regex that matches emails of the forms `first.last@example.com` and `something99@history.com`. Allow for numbers in the domain name as well as the email prefix. Capture the domain name.
11. Provide a regex (as if for a password checker), that enforces a password to have at least one symbol and one number.
12. Provide a regex that matches emails from the domains `.com`, `.org`, `.net`, `.io` and `.ly` but not `.biz` and `.com.uk`. This regex should capture the end result. (use #10 as a starting point).
13. Provide a regex that matches the entire [2nd paragraph of the Wikipedia page about John Lennon](https://en.wikipedia.org/wiki/John_Lennon).
14. Provide a regex that matches the numbered exercises from this challenge.
15. Provide two regexes that matches the following C# code and captures the property names. (HINT: How could you match a newline?)

```c#
public class Part
{
    public string PartName { get; set; }
    public int PartId { get; set; }
}
```
