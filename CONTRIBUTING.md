## How to contribute to vocabularies and ontologies of the German National Library

Welcome! Thank you for contributing to the vocabularies and ontologies of the German National Library.

Below you will find a set of guidelines on how to contribute to the vocabularies and ontologies. We use a simple workflow: the main branch is always the currently valid release. New versions are prepared in development branches, which are added to the main branch after some time and lead to a new release. 

### How can I contribute?

We welcome contributions and encourage you to submit suggestions by creating an issue or a pull request in this GitHub repository.

### Suggestions for improvements

This section explains how to submit suggestions for improvements to the vocabularies and ontologies. Following these guidelines will help maintainers and the community to understand your suggestion and find related suggestions.

Before submitting an improvement suggestion, please perform a search to see if the improvement has already been suggested. If this is the case, add a comment to the existing suggestion instead of opening a new issue. When creating a suggestion, please provide as much detail as possible:

#### How can I submit a suggestion?

For an improvement suggestion, create a new GitHub issue.

Please provide the following information:

- A clear and descriptive title for the problem to identify the suggestion.
- Describe the proposed improvement step by step and in as much detail as possible.
- Provide concrete examples to illustrate the steps. Include copy-pasted snippets used in these examples as Markdown code blocks.
- Explain why this improvement would be useful for most users.

#### Pull requests

Please follow these steps to suggest contributions to the project.

When submitting a pull request, use a meaningful title and use keywords in the description of the pull request to refer to the problem it is intended to solve. This is followed by the review process by a reviewer. The reviewer may ask you to make additional formatting or other changes before your pull request is finally accepted.

### Git conventions

Git commits should be as granular as possible. When we work on fixing issue X, we don't try to include other things we notice (formatting, etc.) in the same commit. These things should be put in a separate commit in the same branch. 

Commit messages:
- Use the imperative in the subject line ("Add term" not "Added term").
- Separate the subject from the text with a blank line.
- Capitalize the subject line.
- Do not end the subject line with a period.
- Explain the what and why in the body text, not the how (which can be seen in the diff).

### Publishing new vocabulary versions

We use semantic versioning in version numbers A.B.C, i.e. A is incremented if it is a major version that removes backward compatibility; B is incremented if there are new terms; C is incremented if bugs have been fixed. (You can read more on [semantic versioning](https://semver.org/).)

### Acknowledgment

Thank you for contributing to the vocabularies and ontologies of the German National Library! We refer to all those who contribute via this way about the statement:
```
<owl:Ontology rdf:about="https://d-nb.info/standards/elementset/gnd#"> <dct:contributor rdf:resource="#githubContributors" />
      <foaf:Group rdf:about="#githubContributors">
            <rdfs:label xml:lang="en">Github Contributors</rdfs:label>
      </foaf:Group>
```
For special contributions, contributors are named separately in the respective vocabulary.

### Do you have further questions?

If you have questions about working with the vocabularies and ontologies of the German National Library or simply want to share what you are currently working on, visit the [metadaten.community Forum](https://metadaten.community/).

You also have the possibility to write an e-mail
  * [Linked Data Service mailing list](mailto:lds@lists.dnb.de)
  * [GND Ontology mailing list](mailto:gnd-ontology@lists.dnb.de)
  * [Metadata services of the German National Library](mailto:metadatendienste@dnb.de) 


Thank you! :heart: 

Linked Data Team
