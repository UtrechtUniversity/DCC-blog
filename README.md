# DCC-blog
This repository is used to develop, maintain a blog for the DCC (Digital Competence Center) of the library.


# How to update
There are 2 branches: main and gh-pages (standing for GitHub pages)

To develop and publish a new version:

1. Create/update a fork of this repository.
2. In your main branch, update the content, style or anything else you want to change.
3. Create a PR to the main branch of this repository.
4. Locally build your website using "quarto preview" on the command line in the root folder of your repository. This will create/update the "_site" folder.
5. Save the contents of the "_site" folder somewhere.
6. Checkout the gh-pages branch in your fork.
7. Replace the content there with the contents of your newly created _site folder.
8. Create a PR to the main repository gh-pages branch.
9. Done!

As soon as the PR is merged and gh-pages is updated, the blog will automatically be published again.
