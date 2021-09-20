# CMPSC 600: Senior Thesis Proposal update

This repository contains the starter for project two (thesis proposal update) in Computer Science 600
Fall 2021. The main directory of this repository contains the LaTeX source code
for a project that is designed for use with [GitHub
Classroom](https://classroom.github.com/). To learn more about the course in
which these assignments were completed, please visit the [Computer Science Thesis Fall 2021 Allegheny College GitHub Organization](https://github.com/allegheny-computer-science-thesis-2021).

The LaTeX file in this repository is automatically compiled with GitHub Actions, ensuring that it compiles correctly and, moreover, that a PDF of the project proposal is available in your GitHub repository whenever a commit is tagged for a release.

## Introduction

This assignment requires a researcher to write a LaTeX document, stored in the
file `SeniorThesisProposalUpdate.tex`, that explains three key aspects of work
that you have completed for your proposed senior thesis research project. First,
you should state the final title for your senior thesis. Second, you should
write a one-paragraph abstract that explains your proposed research. Third, you
should include a bulleted list of the steps that you have taken to demonstrate
the feasibility of your proposed research.

The researcher is also responsible for writing a one-paragraph reflection,
stored in the file `reflection.md`, that explains the challenges that you faced
and the solutions you developed while working on your thesis project so far.
This document should also contain a detailed timeline showing when each of
the requirements for CMPSC 600 is planned to be completed. Finally, this is a Markdown
file that must adhere to the standards described in the [Markdown Syntax
Guide](https://guides.github.com/features/mastering-markdown/). Remember, you
can preview the contents of a committed Markdown file by clicking on the name of
the file in your GitHub repository.

If both your LaTeX source code and your writing meet all of the established
requirements, then you will see a green &#x2714; in the listing of commits in
GitHub. If your submission does not meet the requirements, a red &#x2717; will
appear instead. Your course  instructor will reduce a researcher's grade for
this assignment if the red &#x2717; appears on the last commit in GitHub
immediately before the assignment's due date on `4 October 2021` by `1:30 pm`.

If the green &#x2714; appears on the last commit in your GitHub
repository, then you satisfied all of the main checks, thereby allowing the
course instructors to further evaluate other aspects of your LaTeX source code
and writing, as further described in the remainder of this assignment sheet.
Unless you provide the course instructors with documentation of the extenuating
circumstances that you are facing, no late work will be considered towards your
grade for this project.

## Learning

If you have not done so already, please read all of the relevant [GitHub
Guides](https://guides.github.com/) that explain how to use many of the features
that GitHub provides. In particular, please make sure that you have read the
following GitHub guides: [Mastering
Markdown](https://guides.github.com/features/mastering-markdown/), [Hello
World](https://guides.github.com/activities/hello-world/), and [Documenting Your
Projects on GitHub](https://guides.github.com/features/wikis/). Each of these
guides will help you to understand how to use both [GitHub](http://github.com) and
[GitHub Classroom](https://classroom.github.com/).

## Tagging

Since this repository primarily contains LaTeX source code, the GitHub Actions 
configuration for it will compile the source code and automatically release a
PDF of the main file whenever the last commit is associated with a [Git
Tag](https://git-scm.com/book/en/v2/Git-Basics-Tagging). 

This will build a PDF file available in the "Releases" listing
for this repository. All release numbers for your writing in this repository
should adhere to the [Semantic Versioning](http://semver.org/) standard expected
of GitHub projects. Here this means that:

* `Major version` releases feature a tag number change reflecting full releases; generally these start at `1.0.0`
* `Minor version` releases indicate small changes or additions to documents; typically these increment the second digit in the version (e.g. `1.1.0`)

Please note that your readers will only read the PDF generated from "tagged" releases 
of the file `SeniorThesisProposal.pdf` that has a version number greater than
1.0.0. 

That is:

* if your commit is tagged `SeniorThesisProposalUpdate-chompers-1.0.0`, then 
* the file `SeniorThesisProposalUpdate.pdf` should be available for download in the "Releases" tab in your GitHub repository for this project under the name
`SeniorThesisProposalUpdate-chompers-1.0.0`.

To ensure you can create a release appropriately, make a single small change to the
`SeniorThesisProposalUpdate.tex` and:

1. `commit` your file using a `git commit` command
2. create your first tag for this repository: type `git tag senior_thesis_proposal_update-YOUR_USERNAME-0.1.0`. 
3. You are now ready to push your changes with the tag number using  `git push -u origin main --tags`

The above steps should build a version of your project.

When you make subsequent changes to your files and perform commits and you are
ready to release a new version of `SeniorThesisProposalUpdate.pdf`, then you should
again tag your work _before a `push` command_ with a tag that
adheres to the [Semantic Versioning](http://semver.org/) standard. 

Each time that you correctly execute this sequence of commands you will release a new
version of your document to GitHub that is easily accessible as a PDF to you and
to your first and second readers.

## Updates

If a course instructor updates the provided material for this assignment and
you would like to receive these updates, then you can type this command in the
main directory for this assignment:

```
git remote add download git@github.com:allegheny-computer-science-thesis-2021/cmpsc-600-senior-thesis-proposal-update.git
```

You should only need to type this command once; typing the command additional
times may yield an error message but will not negatively influence the state of
your repository. Now, you are ready to download the updates provided by the
course instructor by typing:

```
git pull download main
```

This second command can be run whenever the faculty need to provide you
with new source code for this assignment. However, please note that, if you have
edited the files that the course instructor updated, running the previous
command may lead to Git merge conflicts. If this happens, you may need to
manually resolve them with the help of the instructor or a teaching assistant.

## Problems

If you have found a problem with this assignment's provided source code, then
you can go to the [Computer Science 600 Proposal Update
Starter](https://github.com/allegheny-computer-science-thesis-2021/cmpsc-600-senior-thesis-proposal-update)
repository and create an issue by clicking the "Issues" tab and then clicking
the green "New Issue" button. To ensure that your issue is properly resolved,
please provide as many details as is possible about the problem that you
experienced.

Students who find, and use the appropriate GitHub issue tracker to correctly
document, a mistake in any aspect of this laboratory assignment will receive
free laptop stickers and extra credit towards their grade for it.

## Assistance

If you are having trouble completing any part of this project, then please talk
with your first reader. In particular, if you have questions about your research project, please
see your first reader. Alternatively, you may ask questions in the Slack channel for this course.