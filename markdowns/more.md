# Final words

In this course, you learned many concepts of Regular Expressions: Metacharacters, repetitions, alternations and groups.
I tried to keep the lessons simple but complete, and as language neutral as possible.

### Pros and Cons

Regular Expressions have good characteristics for text searching, but they also have their flaws:

**Pros**

1. Mature, well tested technology. If you think your problem can be solved with a regex pattern, please use it. Don't try to reinvent the wheel and create your own text parser.
2. Powerful tool. With one line of code you can create amazing searches.
3. Available in most programming languages.
4. There are many online regex tools available, where you can quickly test and fix your patterns. These online tools simplify a lot the debugging and testing of regex expressions.

**Cons**

1. Chaotic, evil syntaxes. Whoever created the regex metacharacter set was high on something. Depending on the situation, the same metacharacter has many different meanings, which makes reading a regex a complicated task. For example, the `?`? First it's a metacharacter for 0 or 1 repetitions, but suddenly it's also used as a lazy quantifier. But wait! As if two different meanings aren't enough, inside a parenthesis `(?` has more than 10 different meanings!: Non-capturing groups, named groups, lookahead and lookbehind, conditionals, recursion.... And this same thing happens with many other metacharacters. 
2. Regex expressions could have bad performance in some instances. Unbounded repetitions can match a string in many different ways, and regex engines usually need to do many steps and backtracking to find all of these matches.
3. Regular Expressions are not suited for very complex, recursive data formats, like XML or HTML. In these cases, it's better to use an XML parser.
4. There are many different regex engines, and each one has different syntaxes. Therefore depending on the language, you need to learn some particular flags and metacharacters.

In my opinion, Regular Expressions are a must-have for anybody that works on IT-related stuff (programming, databases, OS, etc.). One day or another, you'll face a problem where you need to process text streams and search for data based on patterns. Regular expressions excel at these type of tasks.

### Codingame Puzzles
There are many Codingame puzzles where you can use Regular Expressions:

-  https://www.codingame.com/training/community/brackets-extreme-edition Using regex to replace some brackets
-  https://www.codingame.com/training/community/spreadsheet-labels At least one user published a solution using Regular Expressions in C#.
-  https://www.codingame.com/training/medium/scrabble Another user and I both solved this puzzle using a Regex match in C#. 
-  https://www.codingame.com/training/community/hourglass Solved by two users in Ruby with regex patterns that I can't even understand ☺
-  https://www.codingame.com/training/community/reverse-polish-notation Some users got instruction sets as (ADD|SUB|MUL|DIV|MOD|SWP) alternations.
-  https://www.codingame.com/training/community/anagrams Some users solved this with character sets like `[CFILORUX]` in Ruby
-  https://www.codingame.com/training/community/number-of-letters-in-a-number---binary One C# user solved it with Regular Expressions 
-  https://www.codingame.com/training/community/xml-mdf-2016 Many of the published Ruby solutions used regular expresions to filter input data.

The list goes on and on.

### Other interesting links
-  https://regex101.com/ Online regex tester. One of the best on the net.
-  http://www.regexpal.com/ Online regex tester.
-  http://www.rexegg.com/ So much information about Regular Expressions that you'll hate regex with all your heart.

