# HTML Media Tags

Not only can HTML provide meaning to textual content, it can provide meaning to multi-media content. In fact, in 
order to use videos, audio tracks, images, and more...you will need to leverage some HTML tags to display them on 
your webpage.

Not every browser can render every media type though. As discussed, due to licensing issues, smaller organizations 
cannot or will not support various file formats. Or in the case of Apple, they want to push their own file 
format `.mov` so they do not support the `.ogg` format. This is true for all kinds of media. In order to make sure 
_everyone_ can consume your site's media, multiple file formats for media must be provided.

## Assignment

You are given a number of media assets including images, video, and audio. It is your job as a web developer to 
integrate these assets into an HTML page for the Pokémon Company, where you work.

You have media for three different Pokémon families: Bulbasaur, Charmander, and Squirtle. Take these assets to 
create _three_ webpages, one for each "family" of Pokémon.

Each page must have a "responsive" image using the `picture`tag, a caption for each image using `figcaption` tag. In 
addition to images, you must also incorporate the video and audio assets using the `video` and `audio` tags. Be 
sure to be mindful of video formats. A user should be able to consume all media across different browsers: Chrome, 
Safari, and Firefox.

You are also provided some `txt` files full of content for each family. Use your HTML skills you've learned last 
week to markup the content provided.

## Requirements

**Be sure to commit often. Do not commit to the `main` branch. Please create a `development` branch first!**

- Create an `index.html` page as your "homepage". This should have relative links to each of the subsequent pages 
  you'll create.
- Create an `.html` file for each of the Pokémon starter families.
- Markup the content from the `txt` files for each page.
- Each page should have a responsive image using the `picture` tag
- Each page should have a `figure` and a `figcaption` to describe images
- Each page should have a `video` _and_ an `audio` tag
- Multimedia should be consumable in Chrome, Firefox, and Safari.

> NOTE: All of the HTML standards you've learned the week before still apply here. Annotate the content using the appropriate HTML tags even if the tags aren't listed in the requirements. Just because this assignment is focused on media tags, doesn't mean other tags don't apply.

When complete, you will have the following files:

- `index.html`
- `bulbasaur.html`
- `charmander.html`
- `squirtle.html`

## Evaluation

Your assignment is going to be evaluated by the instructor using the W3C Validator. If the validator returns any errors, points will be deducted. So be sure to regualarly test your HTML files in the validator!

The instructor will pull down your code and have an initial review of the code quality. From there, the instructor will open your webpage to make sure it renders in the browser. This includes testing all links, videos, audio, images, and more.

Points will be deducted if...
- Tags are used incorrectly
- Content isn't marked up correctly or at all
- Images, videos, and audio don't work in Chrome, Safari, _and_ Firefox
- Commits to the `main` branch
- No `development` branch
- No PR created

## Submitting Your Work

When complete, create a Pull Request. Once created, copy the Pull Request URL and paste the link in Canvas to submit your assignment.

## W3C Validation
Be sure to regularly validate your HTML files using the W3C Validation Service. This will ensure that your HTML code is technically and semantically [valid](https://validator.w3.org/docs/help.html#validation_basics).

The W3C Validator might also provide clues if you are stuck.

## Resources
- [W3C Validator](https://validator.w3.org/)
- [Mozilla Developer Docs](https://developer.mozilla.org/en-US/docs/Learn/HTML)
- [Git Basics](https://rogerdudler.github.io/git-guide/)
- [Can I Use?](https://caniuse.com/)
