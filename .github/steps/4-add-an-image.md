## Step 4: Add an image

Let's learn how to include [images in markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images), using relative urls, absolute urls, sizing, and basic positioning.

### Regular Markdown

Images can be displayed by providing a relative URL to a file in the repository or an absolute URL (to anywhere on the internet).

The descriptive text in the square brackets is displayed if the image is unable to load, and it is also read aloud for people using screen readers.

Note: Markdown syntax doesn't provide an option to change the image size.

### Example

Relative URL to an image in the repository:
```md
![Mona the Octocat](myrepo/original.png)

```

Absolute URL to an image on the internet:
```md
![Mona the Octocat](https://octodex.github.com/images/original.png)
```

<img alt="Mona the Octocat" src="https://octodex.github.com/images/original.png" width="200">

### Simple HTML

You will often find the need to reduce the size of an image or simply place it next to some text. Regular HTML syntax provides some additional flexibility.

- The `alt` field specifies the alternative text.
- The `src` field specifies the source url of the image.
- A `width` and/or `height` field can be used to specify the size in pixels.
- The `align` field allows setting a position (`left`, `right`)

```md
<img alt="Mona the Octocat" src="https://octodex.github.com/images/original.png"
width="200" align="right">
```

### :keyboard: Activity: Add some decoration

Our blog post is quite simple right now. Let's add some decoration.

1. On the `start-blog` branch, open the `day-1.md` file for editing.

1. Insert an image below the **Morning Planning** level 1 heading.

   ```md
   ![Cloudy morning](https://octodex.github.com/images/cloud.jpg)
   ```

1. Use the **Preview** tab to check your Markdown formatting.

   - Notice the image is too large for our purpose.

1. Replace the simple markdown version with an HTML version that includes size and position info. Much better!

   ```md
   <img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="right">
   ```

1. In the top right, click the **Commit changes** button and commit directly to the `start-blog` branch.

1. With our image added and committed, Mona should be busy reviewing your work and preparing the next steps.

<details>
<summary>Having trouble? 🤷</summary><br/>

- Confirm you are editing the correct file and branch.
- Double check your syntax. An HTML image tag must start with `img` and include the `src` property.

</details>
