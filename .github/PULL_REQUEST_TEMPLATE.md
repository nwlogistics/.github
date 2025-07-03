<!-- markdownlint-disable MD012 MD033 MD041 -->

<!--- Provide a general summary of your changes in the Title above -->

## Description

<!--- Describe your changes in detail -->

## How to test

<!--- How to test your changes -->

### Checkout the branch

```bash
git fetch origin pull/<PR_NUMBER>/head
git checkout FETCH_HEAD
```

### Reproduce changes

*
*

### Switch back to previous branch

After testing the PR, switch back to the previous branch as it's in a detached `HEAD` state that's decoupled from tracked changes.

```bash
# switch to previous branch
git switch -

# switch to main
git switch main
```

## Checklist

<!--- Go over all the following points, and put an `x` in all the boxes that apply. -->
<!--- If you're unsure about any of these, don't hesitate to ask. We're here to help! -->

* [ ] My code follows the code style of this project.
  * Fix via `ruff check --fix` and/or `ruff format .`
* [ ] My change requires a change to the documentation.
* [ ] I have updated the documentation accordingly.

## Screenshots (if appropriate)


## Close issues

Closes issue #<issue-number>
