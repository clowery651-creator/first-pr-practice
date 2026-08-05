# first-pr-practice

A tiny practice project for learning the PR workflow: fork/branch, commit, push, open a pull request.

## What's here

`math_utils.py` has four basic functions: `add`, `subtract`, `multiply`, `divide`.

Run the tests with:

```bash
pytest
```

## Practicing the PR workflow

1. Create a branch: `git checkout -b my-change`
2. Make a small edit (e.g. tweak a function or add a test) and commit it: `git commit -am "Describe the change"`
3. Push the branch: `git push -u origin my-change`
4. Open a pull request against `master`:
   ```bash
   gh pr create --base master --head my-change --fill
   ```
5. Review the diff, then merge it: `gh pr merge --squash`

Repeat with a new branch each time to build the habit.
