<div align="center">

# Markdown 101
### Small symbols. Clear documents. One step at a time.

A beginner-friendly guide to writing and formatting with Markdown.

**Learn the basics · Copy the examples · Practise as you go**

[Start learning](#start-here) · [Build a table](#build-your-first-table) · [Try the challenge](#practice-challenge)

</div>

---

## Welcome to md101

**md101** is a learning repository for anyone who is new to Markdown. It explains how simple text symbols become headings, lists, links, tables, and well-organised documents.

No coding experience is needed. Start with one example, make a small change, and see what happens.

### What is a repository?

A **repository**, often called a **repo**, is a project's home on GitHub. It holds files and keeps a history of changes. This file, **README.md**, introduces the project and doubles as your first tutorial.

### What is Markdown?

Markdown is a lightweight **markup language**: a way to describe how text should look using simple symbols. It is not a programming language.

The `.md` at the end of a filename means it is a Markdown file. GitHub turns supported Markdown formatting into a readable page.

**You type:**

```markdown
**Hello world**
```

**You see:**

**Hello world**

> Think of Markdown as plain text with a few formatting instructions.

## What you will learn

| Skill | What it helps you do |
| :--- | :--- |
| Headings and paragraphs | Give your document a clear structure |
| Bold and italic text | Draw attention to important words |
| Lists and checkboxes | Organise ideas and track tasks |
| Links and images | Connect readers to useful resources |
| Tables | Arrange information into rows and columns |
| Quotes and code blocks | Make examples easy to recognise |

## Start here

1. Read an example below.
2. Copy the text inside its code box into a Markdown file, such as `practice.md`.
3. Change the words to make it your own.
4. Open your editor's Markdown preview to see the result.

You can read this entire tutorial on GitHub without installing anything. When practising, keep a blank line between different sections of your document.

## The basics

### 1. Headings

Type a hash symbol, a space, and your heading. More hashes create a lower-level heading. There are six levels.

```markdown
# Main title
## Section heading
### Smaller section
```

**Try it:** Make a main heading called “My First Document”.

### 2. Paragraphs

Type normally. Leave a blank line between paragraphs.

```markdown
Hello! I am learning Markdown.

This is my second paragraph.
```

### 3. Bold and italic text

Put two asterisks on each side for bold, or one for italic.

| You type | You see |
| :--- | :--- |
| `**Important**` | **Important** |
| `*A little emphasis*` | *A little emphasis* |
| `***Both together***` | ***Both together*** |

### 4. Lists

Use a dash followed by a space for bullet points:

```markdown
- Learn headings
- Practise lists
- Build a table
```

Use numbers followed by a full stop and a space for steps:

```markdown
1. Write your text.
2. Preview the result.
3. Save your changes.
```

GitHub also supports task lists. Use `[ ]` for an unfinished task and `[x]` for a completed one:

```markdown
- [x] Create a heading
- [ ] Add a table
- [ ] Try a link
```

### 5. Links and images

A link has clickable words in square brackets and an address in parentheses:

```markdown
[Explore md101](https://github.com/zezadercksen/md101)
```

An image uses the same pattern with `!` at the beginning:

```markdown
![A description of the image](images/my-photo.jpg)
```

The image example works after you add a file named `my-photo.jpg` inside an `images` folder. Replace the path with your own image's location.

### 6. Quotes and dividing lines

Start a quote with `>` and a space:

```markdown
> Every expert was once a beginner.
```

Add a dividing line with three dashes. Leave a blank line before and after it:

```markdown
Text above the line.

---

Text below the line.
```

### 7. Code and literal symbols

Wrap a short piece of code in single backticks, like `\`README.md\``.

For a code box, place three backticks on a line before and after your text:

````markdown
```
Your example goes here.
**These stars remain visible inside the code box.**
```
````

To display a formatting symbol as ordinary text, put a backslash before it:

```markdown
\*These stars will appear in the text.\*
```

## Build your first table

Tables are useful for schedules, learning plans, and comparisons. GitHub supports them through **GitHub Flavored Markdown**, its version of Markdown with extra features.

### Step 1: Write the column headings

Use a pipe symbol (`|`) to separate columns.

```markdown
| Topic | Progress |
```

### Step 2: Add the required separator

Put at least three dashes under each heading, keeping the pipes.

```markdown
| Topic | Progress |
| --- | --- |
```

### Step 3: Add a row for each item

```markdown
| Topic | Progress |
| --- | --- |
| Headings | Complete |
| Lists | Complete |
| Tables | Learning |
```

**Your finished table looks like this:**

| Topic | Progress |
| --- | --- |
| Headings | Complete |
| Lists | Complete |
| Tables | Learning |

### Step 4: Adjust alignment if needed

Add colons to the separator row to choose where text sits.

| Separator | Alignment |
| :--- | :--- |
| `:---` | Left |
| `:---:` | Centre |
| `---:` | Right |

**Remember:** Leave a blank line before a table, keep the same number of cells in each row, and include the separator line. The spaces do not have to line up perfectly.

## Practice challenge

Copy this starter into `practice.md` and personalise it:

```markdown
# My Markdown Journey

Hello! My name is **Your Name**.

I am learning *one step at a time*.

## My goals

- Write clear notes
- Create useful tables
- Build my first README

## My progress

| Skill | Status |
| --- | --- |
| Headings | Done |
| Tables | Practising |
| Links | Next |

## A useful link

[Markdown 101](https://github.com/zezadercksen/md101)

> Small steps still count.
```

Then try these changes:

- [ ] Replace “Your Name” with your name.
- [ ] Add one more goal.
- [ ] Add a row to the table.
- [ ] Preview your document.

## Common beginner mistakes

| Problem | What to check |
| :--- | :--- |
| A heading looks like plain text | Add a space after `#` |
| Paragraphs run together | Leave a blank line between them |
| A table does not display | Add the separator row and check your editor supports tables |
| Bold formatting continues too far | Close the text with another pair of `**` |
| An image does not appear | Check the file exists and the path matches its name |
| Symbols show inside a code box | That is expected: code boxes display your example literally |

## Keep learning

- [GitHub's Markdown formatting guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [GitHub's guide to tables](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables)

## About this project

Created by [Zéza Dercksen](https://github.com/zezadercksen) as a welcoming place to learn Markdown from the beginning.

Suggestions, corrections, and clearer beginner examples are welcome.

### License

This repository uses the [MIT License](LICENSE).

---

<div align="center">

**Start simple. Keep practising. Make it yours.**

[Back to the top](#markdown-101)

</div>

