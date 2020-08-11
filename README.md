## Package Template
### How to Use
##### Update `package.json`:

1. Set name and displayName
2. Set package version (first version should be 0.1.0)
3. Set description
4. Set Unity version
5. Set type (modules are hidden in Unity projects)

##### Update Assembly Definitions:

1. Replace all occurrences of  `pkg-template` with the name of the package.

##### Delete CHANGELOG.md

The package should have its own changelog.
Without deleting the template's changelog, the additional updates will be appended.

##### Update README.md

Write a README.md for the package.