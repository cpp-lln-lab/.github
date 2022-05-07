# release protocol

- [ ] create a dedicated branch for the release candidate from `dev`
- [ ] update `version.txt`
- [ ] open a pull request (PR) from this release candidate branch targetting the default branch (`main` or `default`)
- [ ] copy this release protocol in the message of the PR
- [ ] fix any remaining failing continuous integration (test, markdown and code linting...)

---

**Where relevant**

- [ ] documentation related
  - [ ] ensure the documation is up to date
  - [ ] make sure the doc builds correctly and fix any error
- [ ] update jupyter books
- [ ] update binder
- [ ] update docker recipes
- [ ] update changelog

---

- [ ] merge to master
- [ ] create a tagged release
- [ ] update and downstream repo (for example any template repo that use this repo as a submodule)

---

**Where relevant**

- [ ] build and push docker images if necessary

---

See that of the [BIDS specs for more ideas](https://github.com/bids-standard/bids-specification/blob/master/Release_Protocol.md)
