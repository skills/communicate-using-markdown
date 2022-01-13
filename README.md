<!--
  <<< Author notes: Header of the course >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses Creative Commons Attribution 4.0 International.
-->

<img src=https://repository-images.githubusercontent.com/138594823/a91ab200-586d-11ea-971b-49617147d94e width=300 align=right>

# Communicating using Markdown

_This course will walk you through everything you need to start organizing ideas and collaborating using Markdown, a lightweight language for text formatting._

<!--
  <<< Author notes: Start of the course >>>
  Include start button, a note about actions minutes,
  and tell the learner why they should take the course.
  Each step should be wrapped in <details>/<summary>, with an `id` set.
  The start <details> should have `open` as well.
  Do not use quotes on the <details> tag attributes.
-->

<details id=0 open>
<summary><strong>:golf: Start</strong></summary>

**To start this course: [<img width="150" alt="Use this template" src="https://user-images.githubusercontent.com/1221423/148581131-555c0fb8-5361-4450-a760-75fa6219a2fc.png">](https://github.com/githublearn/communicating-using-markdown/generate)**

> We recommend creating a public repository, as private repositories will [use Actions minutes](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions).<br>
> After you make your own repository, wait about 20 seconds and refresh. I will go to the next step.

GitHub is about more than code. It’s a platform for software collaboration—and Markdown is one of the most important ways developers can make their communication clear and organized in issues and pull requests. This course will walk you through creating and using headings more effectively, organizing thoughts in bulleted lists, and showing how much work you’ve completed with checklists. You can even use Markdown to add some depth to your work with the help of emoji, images, and links.

- **Who is this for**: New developers, new GitHub users, and students.
- **What you'll learn**: Use Markdown to add _lists_, _images_, and _links_ in a comment or text file
- **What you'll build**: We'll update a plain text file and add Markdown formatting, and you can use this file to start your own GitHub pages site.
- **Prerequisites**: In this course you will work with pull requests as well as edit files. If these things aren't familiar to you, we recommend you take the [Introduction to GitHub](https://github.com/githublearn/introduction-to-github) course, first!
- **How long**: This course is ? steps and takes less than one hour.

</details>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

<details id=1>
<summary><strong>:evergreen_tree: Step 1: Make a task list</strong></summary>

### :wave: Welcome to "Communicating using Markdown"!

**What is _Markdown_**: Markdown is a lightweight syntax for communicating on GitHub. You can format text to add heading, lists, **bold**, _italics_, tables, and many other stylings. You can use Markdown most places around GitHub:

- Comments in [issues](https://help.github.com/articles/github-glossary/#issues) and [pull requests](https://help.github.com/articles/github-glossary/#pull-request)
- Files with the `.md` or `.markdown` extension
- Sharing snippets of text in [Gists](https://help.github.com/en/articles/about-gists)

**What is a _task list_**: A task list creates checkboxes to check off. They're very useful for tracking issues and pull requests. If you include a task list in the body of an issue or pull request, you'll see a progress indicator in your issue list. The syntax for task lists is very specific. Be sure to include the spaces where required, or else they won't render.

#### Example

```
- [x] List syntax is required.
- [x] This item is completed.
- [ ] This item is not complete.
```

#### How it looks

- [x] List syntax is required.
- [x] This item is completed.
- [ ] This item is not complete.

### :keyboard: Activity: Add a task list

GitHub Actions went ahead and made a branch and a pull request for you. So you'll need to add to the file we've created in the branch and we will check your work as you work through this course!

1. Open a new browser tab, and work on the steps in your second tab while you read the instructions in this tab
1. Open the **pull requests** tab
1. Open the pull request we made for you
1. Open the _files_ tab
1. Go to _edit this file_
1. Use Markdown to create a task list of todo items. Here is an example:
   ```
   - [ ] Turn on GitHub Pages
   - [ ] Outline my portfolio
   - [ ] Introduce myself to the world
   ```
   Remember, a task list starts with the syntax `- [ ] ` and then the task list item. The formatting is specific!
1. Use the **Preview** tab to check your markdown formatting.
1. Commit the changes to the file
1. Wait about 20 seconds then refresh this page for the next step

</details>

<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

<details id=2>
<summary><strong>:evergreen_tree: Step 2: Add headers</strong></summary>

### Nicely done friend!

A header is a larger bit of text at the beginning of a section. There are six sizes.

#### Example

```
# This is an <h1> header, which is the largest
## This is an <h2> header
###### This is an <h6> header, which is the smallest
```

#### How it looks

# This is an `<h1>` header, which is the largest
## This is an `<h2>` header
###### This is an `<h6>` header, which is the smallest

### :keyboard: Activity: Edit your file with headers

1. In this pull request, click the **Files changed** tab.
1. Select "Edit file" from the three dotted **...** menu in the upper right corner of the file view.
1. On the **Edit file** tab, add a `#`, followed by a **space**, before the content to make it an H1 Header. You can add more headers, using one to six `#` characters followed by a **space**.
1. Above your new content, click **Preview changes**.
1. At the bottom of the page, type a short, meaningful commit message that describes the change you made to the file.
1. Click **Commit changes**.
1. Wait about 20 seconds then refresh this page for the next step

</details>

<!--
  <<< Author notes: Step 3 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

<details id=3>
<summary><strong>:evergreen_tree: Step 3: Add an image</strong></summary>

### Great job adding headers to the file :sparkles:

Let's add an image. Include descriptive text in the square brackets. This text is read aloud for people using screen readers. It's also shown at times when your image doesn't display, such as when there's a poor connection. You can see the syntax for images below:

#### Example

```
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
```

#### How it looks

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

### :keyboard: Activity: Adding an image

1. As you did before, edit the file in this pull request.
1. In the file, add the correct Markdown for your image of choice. Don't forget to include alt-text!
1. Commit your changes.
1. Wait about 20 seconds then refresh this page for the next step

</details>

<!--
  <<< Author notes: Step 4 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

<details id=4>
<summary><strong>:evergreen_tree: Step 4: Add a code example</strong></summary>

### Great job an image to the file :sparkles:

In addition to code blocks, some code blocks should be rendered differently depending on the language, such as Javascript or command-line text.

#### Example

```sh
$ git init
Initialized empty Git repository in /Users/githublearn/Projects/recipe-repository/.git/
```

#### How it looks

```sh
$ git init
Initialized empty Git repository in /Users/githublearn/Projects/recipe-repository/.git/
```

### :keyboard: Activity: Adding an image

1. As you did before, edit the file in this pull request
1. In the file, add the correct Markdown for a code example of your choice
1. Commit your changes
1. Wait about 20 seconds then refresh this page for the next step

</details>

<!--
  <<< Author notes: Step 5 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

<details id=4>
<summary><strong>:evergreen_tree: Step 5: Merge your pull request</strong></summary>

### Great job adding a code example to the file :sparkles:

You can now [merge](https://help.github.com/articles/github-glossary/#merge) your pull request!

1. Click **Merge pull request**
1. Wait about 20 seconds then refresh this page for the next step

</details>

<!--
  <<< Author notes: Finish >>>
  Review what we learned, ask for feedback, provide next steps.
-->

<details id=X>
<summary><strong>:checkered_flag: Finish</strong></summary>

### Congratulations friend, you've completed this course!

<img src=https://octodex.github.com/images/welcometocat.png alt=celebrate width=300 align=right>

Here's a recap of all the tasks you've accomplished in your repository:

1. You learned about Markdown, tasks lists, headings, images, and code examples
1. You created and merged a Markdown file
1. You learned an essential GitHub skill :tada:

### What's next?

- You can enable GitHub pages and see your Markdown file as a website!
  1. Under your repository name at the upper right, click :gear: **Settings**.
  1. Then on the lower left, click **Pages**
  1. In the **GitHub Pages** section, use the **Select source** drop-down menu to select `main` as your GitHub Pages publishing source.
  1. Click the **Save** button.
- Learn more about [Markdown](https://docs.github.com/en/github/writing-on-github)
- We'd love to hear what you thought of this course [in our community forum](https://github.community/c/education/github-learning-lab/34)
- [Take another GitHub Learn Course](https://github.com/githublearn)
- [Read the GitHub Getting Started docs](https://docs.github.com/en/get-started)
- To find projects to contribute to, check out [GitHub Explore](https://github.com/explore)

</details>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our community forum](https://github.community/c/education/github-learning-lab/34) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2022 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [CC-BY-4.0 License](https://creativecommons.org/licenses/by/4.0/legalcode)
