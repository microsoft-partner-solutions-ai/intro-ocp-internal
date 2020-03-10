# Introduction to the US OCP AI Git Repo

# Overview

This project is aimed to serve as a central repository for assets, solutions, and content aimed to serve US OCP AI partners.

Partners can leverage, fork, contribute and share content within this project as a traditional public repo.

This project welcomes contributions, assets and suggestions.  The contributions within this project imply an agreement declaring that you grant the rights to use your contribution for public consumption.

This project has adopted the [Microsoft Open Source Code of
Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct
FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any
additional questions or comments.

## Permissions & Contributions

There are two ways in which you can help update the content:

* **Share Personal Public Repo:** \
If you are an ad-hoc contributor to the project, but you would like to
maintain the changes within your personal projectscontribute some changes, the best way to do it is:

  1. Fork from your personal repo into this project
  2. Periodically, update the "us-ocp-ai" repo to sync with your linked repo.

* **US-OCP-AI Original Repo:** \
If you plan to create content that originates from within this project, thus you can update the content semi-regularly or regularly, each US OCP AI internal team member is listed as project's Owners group. 
We will then want to leverage PR against master in order to merge your changes.
  1. Fork the repo or create a new feature branch
  2. Write in your contributions
  3. Create a PR into this repo


## Git Training

Consistent with the practices suggested in this playbook, please follow the
specifics regarding git as described in this section.

- [Git Training] (https://gist.github.com/peterhurford/4d43aa5d6de114c0c741ba664c9c5ff5)

### Branch naming convention

In this repo, we use the following branch naming conventions:

| Branch Type | Pattern | Example |
| - | - | - |
| Feature | feature/\<issue#>-\<short description> | feature/498-reorganize-scm-section |
| Bug Fix | fix/\<bug#>-\<short description> | bug/978-correct-grammar-myfile.md |

> **Note:**
>
> * Please, do not use personal branches. Work should refer back to a
feature/bug fix in the backlog.
> * Mind the capitalization of the branch prefix (feature, fix). Tools that
diplay branches as a hierarchy are typically case sensitive, and will display
different hierarchies for the same words with different capitalization.


### Example Directory Hierarchy

The following illustrates how the directory structure could be organized.

```plaintext
- README.md (Detailed Descriptions)
- /<Folder Structure>
    - /<sub-folder 1>
        - README.md
    - /<sub-folder 2>
        - README.md
```

## Legal Notices

Microsoft and any contributors grant you a license to the Microsoft
documentation and other content in this repository under the
[Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/legalcode),
see the [LICENSE](LICENSE) file, and grant you a license to any code in the
repository under the [MIT License](https://opensource.org/licenses/MIT), see the
[LICENSE-CODE](LICENSE-CODE) file.

Microsoft, Windows, Microsoft Azure and/or other Microsoft products and services
referenced in the documentation may be either trademarks or registered
trademarks of Microsoft in the United States and/or other countries.
The licenses for this project do not grant you rights to use any Microsoft
names, logos, or trademarks. Microsoft's general trademark guidelines can be
found at <http://go.microsoft.com/fwlink/?LinkID=254653>.

Privacy information can be found at <https://privacy.microsoft.com/en-us/>

Microsoft and any contributors reserve all others rights, whether under their
respective copyrights, patents, or trademarks, whether by implication, estoppel
or otherwise.
