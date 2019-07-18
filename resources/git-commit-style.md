# From Udacity.com Git Commit Message style guide.
http://udacity.github.io/git-styleguide/

### Format
type: title (<50 characters, no period at end)

body (optional)

footer (optional)

### Details
**Title** should be no greater than 50 characters, should begin with a capital letter and do not end with a period.  Use an imperative tone to describe what a commit does, rather than what it did.  For example, use change; not changed or changes.  Use the **body** to explain the what and why of a commit, not the how.  The **footer** is optional and is used to reference issue tracker IDs.  

### Type
The type is contained within the title and can be one of these types:

  * feat: a new feature
  * fix: a bug fix
  * docs: changes to documentation
  * docs-examples (my addition): add examples to documentation.
  * style: formatting, missing semi colons, etc; no code change
  * refactor: refactoring production code
  * test: adding tests, refactoring test; no production code change
  * chore: updating build tasks, package manager configs, etc; no production code change

=====================  Example  ===========================  
feat: Summarize changes in around 50 characters or less

More detailed explanatory text, if necessary. Wrap it to about 72
characters or so. In some contexts, the first line is treated as the
subject of the commit and the rest of the text as the body. The
blank line separating the summary from the body is critical (unless
you omit the body entirely); various tools like `log`, `shortlog`
and `rebase` can get confused if you run the two together.

Explain the problem that this commit is solving. Focus on why you
are making this change as opposed to how (the code explains that).
Are there side effects or other unintuitive consequences of this
change? Here's the place to explain them.

Further paragraphs come after blank lines.

/ - Bullet points are okay, too

/ - Typically a hyphen or asterisk is used for the bullet, preceded
   by a single space, with blank lines in between, but conventions
   vary here

If you use an issue tracker, put references to them at the bottom,
like this:

Resolves: #123  
See also: #456, #789  
/============================================================  

