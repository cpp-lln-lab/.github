# release protocol

- [ ] create a dedicated branch for the release candidate from `dev`
- [ ] update `version.txt`
- [ ] add PR with INFRA (test, CI...)
- [ ] fix any remaining failing CI (test, markdown and code listing)
- [ ] ensure the doc is up to date
- [ ] make sure the doc builds correctly and fix any error
- [ ] update jupyter books and binder
- [ ] update changelog
- [ ] merge to master
- [ ] create a tagged release
- [ ] update and downstream repo (for example any template repo that use this repo as a submodule)



See that of the [BIDS specs for more ideas](https://github.com/bids-standard/bids-specification/blob/master/Release_Protocol.md)
