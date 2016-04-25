# Optimal MetaTags with OpenGraph Data 

[![license][license-image]][license-url]

A snippet for your page's ``<head>`` that includes all the meta tags you'll need for OPTIMAL sharing and SEO. Extensive work has been put into ensuring your images are optimized for the most important social media platforms are supported.

## Testing:
* Twitter: https://dev.twitter.com/docs/cards/validation/validator
* Facebook: https://developers.facebook.com/tools/debug
* Google: http://www.google.com/webmasters/tools/richsnippets
* Pinterest: http://developers.pinterest.com/rich_pins/validator/
* Google Structured Data: https://developers.google.com/structured-data/testing-tool/

## Sources:
* https://moz.com/blog/meta-data-templates-123
* https://blog.bufferapp.com/ideal-image-sizes-social-media-posts
* https://blog.bufferapp.com/ideal-image-sizes-social-media-posts#linkedin
* https://developers.facebook.com/docs/sharing/best-practices
* https://dev.twitter.com/cards/getting-started
* http://havecamerawilltravel.com/photographer/images-photos-facebook-sizes-dimensions-types
* https://blog.bufferapp.com/ideal-image-sizes-social-media-posts#pinterest
* http://www.iacquire.com/blog/18-meta-tags-every-webpage-should-have-in-2013
* http://www.metatags.info

## Further resources
* http://ogp.me

## Contributing
Please take a moment to review this section in order to make the contribution process easy and effective for everyone involved.

Following these guidelines helps to communicate that you respect the time of the developer(s) managing and developing this open source project. In return, they should reciprocate that respect in addressing your issue or assessing patches and features.

### Using the issue tracker

The issue tracker is the preferred channel for [bug reports](#bugs),
[features requests](#features) and [submitting pull
requests](#pull-requests), but please respect the following restrictions:

* Please **do not** use the issue tracker for personal support requests.

* Please **do not** derail or troll issues. Keep the discussion on topic and
  respect the opinions of others.


### Bug reports

A bug is a _demonstrable problem_ that is caused by the code in the repository.
Good bug reports are extremely helpful - thank you!

Guidelines for bug reports:

1. **Use the GitHub issue search** – check if the issue has already been
   reported.

2. **Check if the issue has been fixed** – try to reproduce it using the
   latest `master` branch in the repository.

3. **Isolate the problem** – create a live example (e.g., on
   [Codepen](http://codepen.io)) of a [reduced test
   case](http://css-tricks.com/6263-reduced-test-cases/).

A good bug report shouldn't leave others needing to chase you up for more
information. Please try to be as detailed as possible in your report. What is
your environment? What steps will reproduce the issue? What browser(s) and OS
experience the problem? What would you expect to be the outcome? All these
details will help people to fix any potential bugs.

Example:

> Short and descriptive example bug report title
>
> A summary of the issue and the browser/OS environment in which it occurs. If
> suitable, include the steps required to reproduce the bug.
>
> 1. This is the first step
> 2. This is the second step
> 3. Further steps, etc.
>
> `<url>` - a link to the reduced test case
>
> Any other information you want to share that is relevant to the issue being
> reported. This might include the lines of code that you have identified as
> causing the bug, and potential solutions (and your opinions on their
> merits).


### Feature requests

Feature requests are welcome. But take a moment to find out whether your idea
fits with the scope and aims of the project. It's up to *you* to make a strong
case to convince the project's developers of the merits of this feature. Please
provide as much detail and context as possible.


### Pull requests

Good pull requests - patches, improvements, new features - are a fantastic
help. They should remain focused in scope and avoid containing unrelated
commits.

**Please ask first** before embarking on any significant work, otherwise you
risk spending a lot of time working on something that the project's developers
might not want to merge into the project.

Please adhere to the coding conventions used throughout a project (whitespace,
accurate comments, etc.) and any other requirements (such as test coverage).

Follow this process if you'd like your work considered for inclusion in the
project:

1. [Fork](https://help.github.com/articles/fork-a-repo/) the project, clone your
   fork, and configure the remotes:

   ```bash
   # Clone your fork of the repo into the current directory
   git clone https://github.com/<your-username>/normalize.css
   # Navigate to the newly cloned directory
   cd normalize.css
   # Assign the original repo to a remote called "upstream"
   git remote add upstream https://github.com/necolas/normalize.css
   ```

2. If you cloned a while ago, get the latest changes from upstream:

   ```bash
   git checkout master
   git pull upstream master
   ```

3. Never work directly on `master`. Create a new topic branch (off the latest
   version of `master`) to contain your feature, change, or fix:

   ```bash
   git checkout -b <topic-branch-name>
   ```

4. Commit your changes in logical chunks. Please adhere to these [git commit
   message conventions](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
   or your code is unlikely be merged into the main project. Use Git's
   [interactive rebase](https://help.github.com/articles/interactive-rebase)
   feature to tidy up your commits before making them public.

   Be sure to test the `normalize.css` file for style conformance.

   ```bash
   npm test
   ```

   Be sure to add a test to the `test.html` file if appropriate, and test
   your change in all supported browsers.

5. Locally rebase the upstream development branch into your topic branch:

   ```bash
   git pull --rebase upstream master
   ```

6. Push your topic branch up to your fork:

   ```bash
   git push origin <topic-branch-name>
   ```

10. [Open a Pull Request](https://help.github.com/articles/using-pull-requests/)
    with a clear title and description.

**IMPORTANT**: By submitting a patch, you agree to allow the project owner to
license your work under the same license as that used by the project.