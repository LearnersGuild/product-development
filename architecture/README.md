# Architecture

Everything we build conforms the principles of [service-oriented-architectures](../global-requirements/soa.md).

![architecture diagram][arch-diagram]

## Key Services

### Internal services

#### idm (Identity Management)

- **Domains:** user data
- **Accountabilities:** SSO, authentication, authorization, user data APIs
- **Endpoint:** https://idm.learnersguild.org
- **Repository:** https://github.com/LearnersGuild/idm

#### echo

- **Domains:** members, projects, goals, surveys
- **Accountabilities:** chapter membership, project team assignment, project goal assignment, member phase tracking
- **Endpoint:** https://echo.learnersguild.org
- **Repository:** https://github.com/LearnersGuild/echo

#### curriculum

- **Domains:**
- **Accountabilities:**
- **Endpoint:**
- **Repository:**

### External services

#### slack (Chat)

- **Domains:** real-time chat among members, integration with Echo service
- **Accountabilities:** real-time chat, single-sign-on, custom `/slash` commands
- **Endpoint:** https://learnersguild.slack.com

#### hubspot

- **Domains:**
- **Accountabilities:**
- **Endpoint:**

### Key Libraries

#### echo-cli (Echo CLI Command Parser)

- **Domains:** commands and command-line options
- **Accountabilities:** command-line option parsing, API invocations, and error handling
- **Repository:** https://github.com/LearnersGuild/echo-cli

#### idm-jwt-auth (Node.js IDM Helpers)

- **Accountabilities:** SSO for Node.js apps
- **Repository:** https://github.com/LearnersGuild/idm-jwt-auth

[arch-diagram]: https://www.lucidchart.com/publicSegments/view/701b182a-c988-4eea-8231-ecae99571426/image.png
