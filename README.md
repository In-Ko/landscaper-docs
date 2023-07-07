# landscaper-docs
Test Repo trying out doc generation for various repos.

Scenario to try out:
- have several repos which contain documentation in various folders
- use github action in this documentation repo to checkout and copy the various documentations from the various repos to some folders into this documentation repo.
- Then run Hugo (https://gohugo.io/) to do its magic and generate a nice website out of the docu folders
- Then setup an ongoing sync whenever changes are done in the original repos (copy stuff again into the documentation repo, trigger regeneration of the static site)
