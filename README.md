# tomorrowio
A Node.js library written in Typescript for interacting with the tomorrowIO v4 weather API. Our goal is near 100% coverage of the TomorrowIO API.

**This library is currently under development and not ready for production use.**

## Why?

- Currently, there are no maintained Node.js libraries providing near full coverage of the tomorrow.io API. Most libraries are either in Python, written for a specific feature, or are not currently maintained.
- Tomorrow.io's openAPI implementation via the api NPM repository is unstable. The api library does not support type definitions (and probably never will due to how it works), and tomorrow.io's openAPI definitions do not always work outside of the actual documentation website (it reports no available API paths).

## Current Features
None at the moment! This is an empty repository.

## Reporting Issues / Suggesting Features
Please submit issues and feature requests in the Issues tab on GitHub. But before you open a new issue, please search to ensure someone else did not already open an issue. If someone else already opened an issue and you have additional meaningful information to provide, please comment on the open issue instead of making a new one. Duplicate issues will be closed immediately.

## Contributing
We welcome contributions to this repository as the main developer(s) only have a limited amount of time for this project. Please see our [Contributing Guidelines](https://github.com/Lovinity/tomorrowio/blob/main/CONTRIBUTING.md) for more information.

## Roadmap

- [ ] Basic API interaction and parsing functionality
- [ ] Cache system to reduce repeat queries (???)
- [ ] API type definitions
- [ ] Class configuration
- [ ] Browser support via JavaScript
- [ ] Console logging for debug purposes
- [ ] API: Key management
- [ ] API: Errors / Exceptions
- [ ] API: Rate limit handling
- [ ] API: Location formats
- [ ] API: Pagination
- [ ] API: X-Correlation-ID
- [ ] API: Max, Min, Avg, MaxTime, and MinTime support
- [ ] API: Field Descriptors
- [ ] API: Data Layers / Core
- [ ] API: Timelines / Basic
- [ ] API: Timelines / Advanced
- [ ] API: Timelines / Historical
- [ ] API: Maps / Tile
- [ ] API: Routes
- [ ] API: Locations / List
- [ ] API: Locations / Retrieve
- [ ] API: Locations / Create
- [ ] API: Locations / Update
- [ ] API: Locations / Delete
- [ ] API: Events / Basic
- [ ] API: Events / Advanced
- [ ] API: Alerts / List
- [ ] API: Alerts / Retrieve
- [ ] API: Alerts / Create
- [ ] API: Alerts / Update
- [ ] API: Alerts / Linked Locations
- [ ] API: Alerts / Delete
- [ ] API: Notifications / Basic
- [ ] API: Notifications / Advanced
