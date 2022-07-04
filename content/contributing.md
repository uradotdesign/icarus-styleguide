+++
title = "Contributing"
+++

Getting started
===============

We are making Icarus usable for everyone.

The Icarus style guide is based on [Bootstrap](https://getbootstrap.com/ "Bootstrap"), an open-source toolkit for developing with HTML, CSS, and JS. We are currently on [v5.2.0](https://getbootstrap.com/docs/5.2/getting-started/introduction/ "Bootstrap Introduction").

To improve the Icarus style guide, you can clone the repo and modify the content.

Bootstrap contains a few JavaScript libraries for extra interaction with the DOM. We use these libraries but do not add extra JavaScript, so that only few elements are affected if you disable JavaScript.

This style guide has been built using [Hugo](https://gohugo.io/ "Hugo"). Hugo is one of the most popular open-source static site generators. You can build this yourself by [installing Hugo](https://gohugo.io/getting-started/installing/ "Hugo installation").

Reuse in a project
------------------

The components used in the Icarus Style Guide are created with portability in mind. This means they can be reused elsewhere without having to reinvent the wheel.

The easiest way to do this is to download the scss style (components.scss) and import it in your project with bootstrap included.

If you want to use SASS you can download the complete archive for the styleguide. [SASS](https://sass-lang.com/ "SASS") is a CSS extension The scss folder under assets contains all the sass files. Since we use Bootstrap, we only add a few styles without modifying bootstrap core or defining new elements whenever possible.

###### Use the Icarus Style Guide

This package includes .scss files

[Visit Repo](https://github.com/uracreative/icarus-styleguide/tree/master/assets "Icarus Repo")

Contributing
------------

If you an interested in contributing to our design system, the first step is ensuring that an issue exists in our issue tracker. There are many applications that an issue can have, including:

*   Submitting feature proposals
*   Asking questions
*   Reporting bugs and malfunctions
*   Obtaining support
*   Enhancing code implementations

If you were unable to find a related issue in our issue tracker, begin by creating a new one. Creating an issue for each change allows us to easily track all proposals in one place. For changes that affect visual designs or user experiences, it can be helpful to include a mockup.

### UX proposals

If your proposal involves a new guideline or UX paradigm, ping a UX reviewer or maintainer to review and provide feedback.

### Frontend proposals

If your proposal involves a change to the frontend implementation, ping a frontend reviewer or maintainer to review and provide feedback.

Contribute a merge request
--------------------------

To make changes within our Design System, follow these instructions:

1.  Choose an issue to work on. If one does not exist, please review the contribution guidelines regarding creating a new one. This opens the conversation and allows feedback to happen early, preventing risks such as duplicated or unnecessary work. It can be helpful to comment in the issue to verify that no one is working on it and that the issue is still relevant.
2.  Fork this project.
3.  Make changes reflecting the issue you've chosen to work on.
4.  Create a merge request. The earlier you open a merge request, the sooner you can get feedback. You can mark it as a Work in Progress to signal that you're not done yet.
5.  Get your merge request approved. If your changes involved a new guideline or UX paradigm, then ping a UX reviewer or maintainer to approve your changes. If your changes involve an update to frontend implementation, ping a frontend reviewer or maintainer to approve. Some merge requests will require both a UX and frontend approver.
6.  Get your changes merged! After the necessary approvals have been added, a UX or frontend maintainer can then merge your merge request. 🙌