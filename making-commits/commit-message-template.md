## Format of the commit message:

```
<type>(<scope>): <subject>

<body>

<footer>
```

## Example commit message:

```
chore(deployment): add deployment hosts

Add configuration for deployment hosts for the different development stages

Resolves #8
```

## Message subject \(first line\)

* Uses the imperative, present tense: “change” not “changed” nor “changes”
* Should not be longer than 70 characters.
* The type, scope, and subject should always be lowercase.

### Allowed`<type>`values:

* **feature **\(new feature for the user, not a new feature for build script\)
* **fix **\(bug fix for the user, not a fix to a build script\)
* **documentation **\(changes to the documentation\)
* **refactor **\(refactoring production code, eg. renaming a variable\)
* **test **\(adding missing tests, refactoring tests; no production code change\)
* **chore **\(development tasks etc; no production code change\)
* **update **\(updating\)

The`<scope>`can be empty \(e.g. if the change is a global or difficult to assign to a single component\), in which case the parentheses are omitted.

## Message body

* Uses the imperative, present tense: “change” not “changed” nor “changes”
* Includes motivation for the change and contrasts with previous behavior

## Message footer

### Referencing issues

Closed issues should be listed on a separate line in the footer prefixed with "Resolves" keyword like this:

```
Resolves #5
```

or in the case of multiple issues:

```
Resolves #5, #8, #12
```



