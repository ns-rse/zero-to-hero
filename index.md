# GitKraken : Zero to Hero

Here are my notes on the Workshop [GitKraken : Zero to Hero](https://srse-git-github-zero2hero.netlify.app/).

## GitHub Pages

The web-page is published using [GitHub Pages](https://pages.github.com).

1. Create an initial `index.md` and add text to it (in [Markdown](https://www.markdownguide.org)).
2. Commit and push your changes to your repository.
3. Visit your pages GitHub repository and go to `Settings`.
4. Under `Pages` select the branch where `index.md` has been created and its location (by default these are `main` and
`root`).
5. Save these changes.

You should then have a green box appear with the message "_Your site is published at..._" with a URL pointing to its
location.

You can update the theme of the site using the `Theme Chooser` on the same page. As you can see I've opted for the
`Hacker` theme.

## Collaboration

1. Make a fork of
   [RSE-Sheffield/collaborative_github_exercise](https://github.com/RSE-Sheffield/collaborative_github_exercise/fork) by
   clicking on the `Fork` button at the top-right. This copies the fork to your own account.
2. Clone the repository to your local computer by clicking on `Code`, copying the URL and typing...

```bash
git clone git@github.com:ns-rse/collaborative_github_exercise.git
```

3. Make a copy of `params/project_tmpl.R` into `params/some_unique_name.R` and start editing it.

4. Add a value between `0` and `5` for `sig2`.

5. Add a value for `species.name <- 'some_unique_name'`.

6. Change the `color <- "cyan"` (a list of possible colours are available [here](http://www.stat.columbia.edu/~tzheng/files/Rcolor.pdf))

7. Save, commit and push your changes to _your_ fork of the repository.

### Create a Pull Request
Now create a pull request from your fork on GitHub to the `master` (or `main`) branch of the base repository from which
the fork was made (`RSE-Sheffield/collaborative_github_exercise`). To do this...

1. Click on `Pull Request`.

2. Ensure the target is `RSE-Sheffield/collaborative_github_exercise` on branch `master` and the source is
  `<your-account>` and the branch is `master`.

3. Add a commit message describing what is being added "_This commit is ..._" and a message for a more information.

4. Click on "_Create Pull Request_".

# Links

* [GitKraken : Zero to Hero](https://srse-git-github-zero2hero.netlify.app/)
* [GitHub Pages](https://pages.github.com)
* [Markdown](https://www.markdownguide.org)
