Footnotes allow you to add references or notes without cluttering the main text.

### Basic Syntax

```markdown
This is a sentence with a footnote.[^1]

[^1]: This is the footnote text.
```

Result (on supported Markdown renderers):

> This is a sentence with a footnote.¹

---

### Multiple Footnotes

```markdown
Markdown is easy to learn.[^md]

Git is essential for developers.[^git]

[^md]: Markdown is a lightweight markup language.

[^git]: Git is a distributed version control system.
```

---

### Named Footnotes

The identifier doesn't have to be a number:

```markdown
I love Markdown.[^markdown]

[^markdown]: Because it is simple and readable.
```

---

### Multi-line Footnotes

```markdown
This is an important statement.[^note]

[^note]: This is the first line of the footnote.

    This is a continuation of the same footnote.

    You can even have multiple paragraphs.
```

---

### GitHub Support

GitHub supports footnotes in README files and Markdown documents.

Example:

Rabbitfolio is my major project.[^rabbitfolio]

[^rabbitfolio]: A platform focused on developer portfolios and discoverability.

---

### Real Example


## About Me

My name is Naveen Kumar and I enjoy building software systems.[^1]

I am currently focused on DSA, MERN, and System Design.[^2]

[^1]: Software Engineer and builder.
[^2]: Preparing for interviews while building real-world projects.

### Best Practices

* Use descriptive names when possible (`[^github]`, `[^note]`).
* Keep footnotes at the bottom of the document.
* Use footnotes for extra context, references, or explanations.
* Avoid overusing them in README files; links and tables are often easier to read.
