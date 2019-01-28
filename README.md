# Rules and Bylaws of the Washington State 43rd District Democrats
This repository contains the ongoing work of the [43rd District Democrats](https://www.43rddemocrats.org/) Rules and Bylaws Committee.

## Repository Usage
### Document Representation
There are separate folders for the bylaws and for each standing rules document. Within each folder, there will typically be three files:
* A pair of text files representing the document using the [LaTeX typesetting system](https://www.latex-project.org/):
  * `document.tex` contains the document structure and title, and possibly other style and formatting rules specific to that document.
  * `content.tex` contains the preamble, articles, and general content of the document.
* A PDF file representing the document.

The `common` folder contains LaTeX style rules that are reused across multiple documents. It is typically included within the `document.tex` file, using LaTeX's `\input{}` command.

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
### What is GitHub?
GitHub is a free service for hosting public Git repositories. It is commonly used in the Open Source community and elsewhere to share and collaborate on software projects.

### What is Git?
Git is a popular Open Source source control management system (SCM). SCMs are used by software developers to view, comment on, update, and otherwise manage changes to software projects, particularly when those projects involve multiple developers.

### Why are we using Git and GitHub? Why not use Google Docs?
Git and GitHub allows us to do several things that Google Docs (and other similar online collaboration tools) do not:
* Work on multiple different versions at the same time.
* Arbitrarily compare any two versions of a document to one another.
* Suggest, view, and comment on complex changes involving multiple edits across multiple documents.
* File and track issues for each document.
* Accept change suggestions from members of the public.
* Open up the change process for others to observe and learn from.

### What is LaTeX?
LaTeX is an extremely powerful typesetting system, used for everything from scientific research papers to genre fiction novels. LaTeX documents contain the plaintext content of the document, marked up with relatively straightforward and unobtrusive commands to indicate how the content should be styled, laid out, and otherwise presented.

### Why not use Markdown/MediaWiki/HTML/PDFs/Word documents/etc.?
LaTeX gives us two important features: high fidelity control over style and formatting, while still being very human-readable and easy to compare.

While binary formats like PDF and Word documents provide extensive control over formatting, it is typically difficult to compare between two different versions of the same file, and comparing across different files is often impossible. You are limited by the capabilities of the program, e.g., whatever comparison features have been built into Microsoft Word itself. With a plaintext format such a LaTeX (or Markdown or HTML), it is easy to apply third-party tools to perform comparisons - Git itself supports rich comparisons between different files or versions of the same file.

While Markdown and other similar formats are human-readable and comparison-friendly, they tend to be very limited in what they allow the author to do. Even a relatively simple feature such as letter-based lists (as is found in our bylaws) is not supported by Markdown. HTML provides more flexibility, but quickly becomes less readable as documents grow more complex.

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
* Angyl Bender
* Heidi Bennett
* Aiden Carroll
* Tara Gallagher
* Amy Madden
* James Williams
