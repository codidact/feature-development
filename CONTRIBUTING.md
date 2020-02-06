# Contributing to Codidact Feature Development
Contributions are very welcome! Codidact is an open, community-run project, and that means not only the code - but the design too.

## What needs doing?
 - **Creating new use cases** Use cases are an important first step for feature development. Ping a docs project lead or @cellio for more information. Any issue with the `new use case` and `help wanted` tags will be up for grabs. Follow the existing format in another use case.
 - **Requests for features** As feature development gets further developed, scope becomes narrower. So providing a 22 point list of feedback for a high fidelity design is not so useful, but comments, feedback and constructive criticism is welcome for our use cases and wireframes. Don't expect things to veer too far away from what was outlined in our [functional specification](https://github.com/codidact/docs/wiki/Functional-Specification) though.

To submit a request - create an issue linking to the existing use case markdown file or wireframe image and clearly describe your thoughts and/or suggestions. Remember, we are actively in the creation of this app and your contributions, no matter how small will make a big impact!

Just like any other OSS project, don't open an issue without checking if it already exists! Adding tags to new issues is going to be a really important way to keep this information organised and searchable so try and use the following tags where appropriate:

* `new use case` Highlights a use case that is yet to be created
* `help wanted` or `good first issue` This is your queue to grab this use case or wireframe and hack away!
* `feature request` This is a proposal for a whole feature. We don't expect too many of these (but welcome good ideas)
* `change request` A request to change an aspect of an existing use case or wireframe
* `for consideration` This is a way to share some thoughts that we should be considering within a use case or wireframe, and will not necessarily result in an action

## What's the workflow?
 * First, **you need an issue to work under**. Either assign yourself to an existing issue (or request it be assigned to you).
 * Second, you can make your changes. If you have access to the repository, create a topic branch (please use the format
   `art/40/add-bells-and-whistles`, i.e. `username/issue-number/brief-description`) and make your changes there; if not, fork
   the repository and work in your fork.
 * Once you've made your changes, submit a pull request targeting the `for review` branch.

Keep in mind that **at least one approving review** is required from the team before
any pull request can be merged.

We also have some [guidelines for commit messages](https://github.com/codidact/core/wiki/Committing-guidelines). Again, please follow these where possible, as they help us to keep a cohesive commit history and see how the project has developed.

## What's the actual process here?


* Feature/process use cases are defined as a markdown file, within this repository within a directory structure as follows:

         process_name 
          |- process_name.md
          |- process_name-hifi-V1.jpg
          |- process_name-fms.jpg
          |- feature_name
               |- feature_name.md
               |- feature_name-hifi-V1.jpg
               |- feature_name-fms.jpg
          |- another_feature_name

* Everything canon will live in this repository. A feature/process will be present both as a directory in the repo and also as a card in the project kanban in the same repository. This kanban is used to identify where in the current process the feauture or process is

* Use cases can be created by contributors by either creating an issue or submitting a PR with the use case in a markdown file in the same format as other use cases.

* Completed use cases get assigned to `@cellio`, or the group design lead (currently `@mattjbrent`) for approval

* Wireframes are created in Figma in a closed environment. Suggestions or ideas can be posted as issues in the repo, clearly tagged with the appropriate information. Wireframes can also be submitted in an issue as visuals which wil lbe translated to the Figma files by Codidact designers

* Once approved, wireframes are handed off the back end dev for technical consideration and implementation

* High fidelity designs will be created in Figma in a closed environment. Suggestions or ideas can be posted as issues in the repo, clearly tagged with the appropriate information.

* High fidelity designs get approved by the `group design lead` for design. At this stage, it should just be visual considerations. Any functional/technical considerations should have already been approved in wireframes.

* Once approved, they get handed off to front end dev for implementation

## Next Steps
We will work on global processes and features first. This will allow back end and front end to create something visual and allow for setup of routing etc. This will also define the basis of our design language (typography, color, spacing etc)

We have already created the authentication process and it's features as user stories and wireframes to act as a documentation of sorts for contributors and to also provide the format for future use cases.

Once global process is finished (including hi-fi designs) we can move on to speccing out all of our other processes and features. All our effort should be put into getting the global processes defined and complete so that all of our devs can be unblocked and productive, working on approved designs. Once each team has finished their aspect of global elements, they can assign other members of their team to contextual processes and features.
