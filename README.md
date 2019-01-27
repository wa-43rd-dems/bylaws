# Rules and Bylaws of the Washington State 43rd District Democrats
This repository contains the ongoing work of the [43rd District Democrats](https://www.43rddemocrats.org/) Rules and Bylaws Committee.

## Repository Usage
### Document Formats
The bylaws are stored in two formats:
1. `Bylaws.tex`: A text file containing the bylaws, represented using the [LaTeX typesetting system](https://www.latex-project.org/).
2. `Bylaws.pdf`: A PDF file generated from `Bylaws.tex`.

### Branches and Tags
The [`master`](https://github.com/wa-43rd-dems/bylaws/tree/master) branch tracks the current rules and bylaws of the organization, as adopted and amended by the membership.

The [`committee-recommendation`](https://github.com/wa-43rd-dems/bylaws/tree/committee-recommendation) branch tracks the changes currently recommended by the committee.

When the membership adopts a new version of the bylaws, that version will be tagged with the date of adoption. For example:
* [2018-01-16](https://github.com/wa-43rd-dems/bylaws/tree/2018-01-16): Bylaws as adopted on January 16, 2018
* [2019-01-15](https://github.com/wa-43rd-dems/bylaws/tree/2019-01-15): Bylaws as adopted on January 15, 2019

### Workflow
New branches should be created for each change proposed to and considered by the committee. These branches should track the `committee-recommendation` branch as their upstream, or another proposal branch if the new proposal is an amendment to an existing proposal.

When the committee votes to recommend a proposal, the proposal's branch should be merged into the `committee-recommendation` branch. When the full set of changes in the `committee-recommendation` branch are adopted by the membership, this branch should be merged into `master`. If the membership rejects changes, then the `committee-recommendation` branch should be rebased from `master`, with the rejected commits removed.

## FAQ
### Why are we using GitHub and LaTeX instead of Google Docs?
GitHub and LaTeX allows us to do several things that Google Docs (and other similar online collaboration tools) do not:
* Work on multiple different versions at the same time.
* Arbitrarily compare any two versions of a document to one another.
* Suggest, view, and comment on complex changes involving multiple edits across multiple documents.
* Completely control the format of the document.
* Provide a human-readable, layperson-friendly text representation of documents.

### How do I suggest a change?
There are three ways to suggest a change:
1. [Open a new issue](https://github.com/wa-43rd-dems/bylaws/issues/new) for it.
2. Submit the change as a pull request.
3. Submit your suggestion to [bylaws@43rddemocrats.org](mailto:bylaws@43rddemocrats.org).

### How can I keep up with what the Committee is up to?
You can follow our work directly by reading the [Rules and Bylaws Committee Google Group](https://groups.google.com/forum/#!forum/43rd-bylaws). Alternatively, you can subscribe to the [bylaws-interest mailing list](https://www.43rddemocrats.org/lists/bylaws-interest) to receive regular updates on the work of the Committee.

### Who is on the Rules and Bylaws Committee?
The members of the Rules and Bylaws Committee as of January 26, 2019 are:
* Annabelle Backman (Chair)
* Brad Bell
* Heidi Bennett
* Aiden Carroll
* Tara Gallagher
* Amy Madden
* James Williams
