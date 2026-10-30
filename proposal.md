# Community Software Analysis Proposal
Please edit this file and push to your repository.

## Software: *Eigen*

Eigen is a header-only C++ linear algebra library that provides dense and sparse
matrices, vectors, matrix decompositions, numerical solvers, and geometry tools.
Its template-heavy interface makes mathematical expressions convenient to write
and allows dimension checks at compile time when matrix sizes are known in
advance. Expression templates and vectorization help avoid unnecessary
temporaries and improve performance. Its primary audience is C++ developers,
researchers, and engineers building numerical software, including scientific
computing, robotics, computer graphics, and machine learning applications.

### Stats

| Description | Your answer |
|---------|-----------|
| Repository URL | [libeigen/eigen on GitLab](https://gitlab.com/libeigen/eigen) |
| Main/documentation website | [Project website](https://libeigen.gitlab.io/); [API documentation](https://libeigen.gitlab.io/eigen/docs-nightly/) |
| Year project was started | 2006 (Eigen 1); Eigen 2 development began in 2007 |
| Number of contributors in the past year | 56 Git author identities, November 1, 2025–October 30, 2026. |
| Number of contributors in the lifetime of the project | 663 Git author identities in the available main-branch history. |
| Number of distinct affiliations | >10, estimated from organizational email domains in the commit history; see the measurement notes below. |
| Where do development discussions take place? | [GitLab issues](https://gitlab.com/libeigen/eigen/-/issues), [merge requests](https://gitlab.com/libeigen/eigen/-/merge_requests), and Discord. The [contribution guide](https://gitlab.com/libeigen/eigen/-/blob/master/CONTRIBUTING.md) identifies Discord as the primary chat channel. |
| Typical number of emails/comments per week? | About 50 public GitLab comment events per week: 199 over October 2–29, 2026, including bot activity. | 
| Typical number of commits per week? | About 25 per week on average: 1,308 commits over November 1, 2025–October 30, 2026. |
| Typical commit size | Usually around 3 files changed and ~80-100 lines added/deleted in total per nonempty commit over the same year. |
| How does the project accept contributions? | Fork the GitLab repository, create a topic branch, and submit a merge request. Include tests and documentation as appropriate; discuss large changes first. See the [contribution guide](https://gitlab.com/libeigen/eigen/-/blob/master/CONTRIBUTING.md). |
| Does the project have an automated test suite? | Yes; CMake/CTest-based tests, documented in the [build and test instructions](https://gitlab.com/libeigen/eigen/-/blob/master/CONTRIBUTING.md#build-and-test). |
| Does the project use continuous integration? | Yes; [GitLab CI pipelines](https://gitlab.com/libeigen/eigen/-/pipelines) run automated checks and tests. |
| Does the project have an AI contribution policy? | Yes; the [provenance and attribution rules](https://gitlab.com/libeigen/eigen/-/blob/master/CONTRIBUTING.md#provenance-and-attribution) explicitly cover AI-suggested code, and [AGENTS.md](https://gitlab.com/libeigen/eigen/-/blob/master/AGENTS.md) gives agent-specific guidance. AI-suggested code must meet the same source attribution and license compatibility requirements. |
| Are any legal/licensing steps required to contribute? | Contributions must have compatible licensing and appropriate copyright/license headers. No CLA or copyright assignment is required, according to the [contribution guide](https://gitlab.com/libeigen/eigen/-/blob/master/CONTRIBUTING.md#copyright-and-credit). |

### Install and run

Check the following boxes when complete or add a note below if you
encountered a problem.

- [ ] I have installed the software
- [ ] I have run at least one example
- [ ] I have run the test suite
- [ ] The test suite passes

### Notes/concerns/risks

#### Note on copyright
Students retain copyright on any work done in completion of a CU
course, so you are authorized to sign a [contributor license
agreement (CLA)](https://en.wikipedia.org/wiki/Contributor_License_Agreement),
affirm a [developer's certificate of
origin (DCO)](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin),
etc.  If you have concerns about this, please note them and/or reach
out to Jed directly.
