---
test: 'some test frontmatter'
---

# Docusaurus website dogfooding

This is where we test edge cases of Docusaurus by using fancy configs, ensuring they all don't fail during a real site build.

Eventually, we could move these tests later so another test site? Note there is value to keep seeing the live result of those tests.

Fancy things we can test for here:

- Plugin Multi-instance
- Symlinks support
- Webpack configs
- \_ prefix convention
- Huge sidebars impact
- Using folders with spaces on purpose
- Importing md docs that are out of content plugin folders as partials (such as this README file!)