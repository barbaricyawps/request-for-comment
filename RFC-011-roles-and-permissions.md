# RFC-011 - Organization roles and permissions

## Proposed by

Alyssa Rock, Bryan Klein


## Current status

See the status indicated on the pull request description.


## Proposal overview

Will write this later...


## Motivation

As our organization begins its migration from GitHub to GitLab (as approved in RFC-009), we need to implement a role-based-access-controls (RBAC) policy to define our organization's roles are and how they map out to specific permissions in GitLab.


## Proposal

The following sections explain each proposed role (team), its responsibilities, eligibility requirements, and the permissions that are granted to this role.


### Tech owners

The tech owner team acts as the IT administrators for the project.

This team:

- Has the highest level of permissions in the project and access to official project accounts.
- Maintains project access and permissions, such as tracking who has certain permission levels, tracking passwords, and removing permissions when people leave the project or their roles change.
- Ensures site reliability and tool reliability.
- Maintains configuration settings, handles software upgrades, and/or rotates passwords as needed.
- Enforces our security policies.

Who is eligible for this team:

- The tech owner team should consist of four project members with two tech owners in each of the major geolocations (U.S./Canada and APAC/EMEA) to ensure regular availability to project members across various time zones.
- Tech owners should have a more advanced understanding or a strong desire to learn more about the underlying technology for the project (such as GitLab and our website technologies).
- Tech owners are responsible for approving and granting access permission in accordance with our documented RBAC policies.
- Tech owners might be required to receive some informal training about general security best practices and principles.

Access permissions:

- Tech owners will have [Owner](https://docs.gitlab.com/ee/user/permissions.html#project-members-permissions) level access to GitLab.
- Tech owners will have access to official project accounts, such as the main project Google account, Netlify, website servers, and social media accounts.


### Template leads

### Project steering committee

### Co-chairs

### Working group leads

### Community moderators





## Consequences

Adopting a clear and transparent RBAC policy will:

- Ensure our project is compliant with security best practices, such as the [principle of least privilege](https://en.wikipedia.org/wiki/Principle_of_least_privilege).
- Clearly communicate to our project contributors who they can contact for tech support and repository or account access requests.


## Links and prior art

{This section is optional if you want to [link](https://example.com) to other resources.}


## Open questions

{This section is optional and is where you can list questions that won't be resolved by this RFC, including those raised in comments from community members.}


## Decisions deferred

{This section is option and is where you can list decisions that won't be resolved by this RFC, but which should be raised at a later time.}


## Feedback

{If you accept feedback from a community member, you will incorporate it into your RFC before it is accepted.
If you reject feedback, note that rejected feedback here before resolving the conversation.}


## Implementation checklist

If this proposal is accepted, the following tasks must be completed:

- [ ] Make sure this RBAC policy is clearly documented and available.
- [ ] Create/update the Our Team page on the website to follow the [Our Team template](https://github.com/thegooddocsproject/templates/pull/245/)


## Votes

Votes as per our [decision process](https://thegooddocsproject.dev/decisions/):

Project steering committee (listed alphabetically by first name):

- Aaron Peters:
- Aidan Doherty:
- Alyssa Rock:
- Ankita Tripathi:
- Bryan Klein:
- Cameron Shorter:
- Carrie Crowe:
- Erin McKean:
- Deanna Thompson:
- Felicity Brand:
- Gayathri Krishnaswamy:
- Morgan Craft:
- Ryan Macklin:
- Nelson Guya:
- Viraji Ogodapola:


Community members who voted (non-binding):

- {Your name}: {Your vote}
