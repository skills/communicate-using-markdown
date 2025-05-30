## Step 2: Make a list

Markdown supports 3 types of common lists. They include:

- [Unordered](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#lists) - Bulleted list
- [Ordered](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#lists) - Number list
- [Task](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) - Checkbox list

### Unordered list

An unordered list is simple to show. Each item is placed on its own line using a `-`, `*`, or `+` character.

```md
- Item 1
- Item 2
- Item 3
```

- Item 1
- Item 2
- Item 3

### Ordered List

A list is changed to ordered by using any number instead of the list character. Notice how markdown automatically handles the counting. Nice!

```md
1. Step 1
1. Step 2
1. Step 3
```

1. Step 1
1. Step 2
1. Step 3

### Task List

A task list is extends the unordered list to use check boxes.
Add empty brackets `[ ]` for incomplete tasks and filled brackets `[x]` for complete tasks. Note: The empty required space for empty brackets.

```md
- [x] This task is complete
- [ ] This task is not complete
```

- [x] This task is complete
- [ ] This task is not complete

> [!TIP]
> Issues and pull requests can use task syntax for [conveying progress](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/about-tasklists).

### :keyboard: Activity: Add ideas and goals to our morning plan

1. On the `start-blog` branch, open the `day-1.md` file for editing.

1. Add the following task list below **morning planning** level two heading to track goals you want to achieve.

   ```md
   - [ ] Check out the [github blog](https://github.blog/) for topic ideas.
   - [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
   - [ ] Convert my first blog post into an actual webpage.
   ```

1. Use the **Preview** tab to check your Markdown formatting.

1. In the top right, click the **Commit changes** button and commit directly to the `start-blog` branch.

1. With our code block committed, Mona should be busy reviewing your work and preparing the next steps.

<details>
<summary>Having trouble? 🤷</summary><br/>

- Confirm you are editing the correct file and branch.
- Double check your syntax. The must be a space inside the `[ ]` for task lists.

</details>
