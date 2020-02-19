**Name**
View Comment Thread

----

**Actor**
Any user

----

**Subject area**
Any post with at least one comment thread.

*Assumption:* each top-level comment (i.e. beginning of thread) up to some max number is shown along with an indication of thread size, e.g. "blah blah blah - SomeUser $date  (13 replies)"

----

**Preconditions**
None

----

**Termination outcome**
Chosen comment thread is visible and user can see reply threads.

----

**Basic flow**

- User chooses a comment thread to expand and selects the "expand" control.
- Thread is fully expanded in-place, with any other threads moved down the page (i.e. nothing else is collapsed/removed).  All sub-comments (those other than the first) are indented a fixed amount (no multi-level indenting yet).
- Each comment has a "reply-to" indicator of some sort.  Hovering over it highlights the comment to which this one is a reply.  **Alternative:** hovering over the comment (anywhere) causes this highlighting -- would that be un-discoverable and/or annoying?
- Each comment also has a "reply" indicator (to be addressed more in another use case).

----

**Notes**

Expanding one comment thread does not collapse others.  If you want to see everything, go for it.

Implication: expanded threads need a "collapse" control.

----

**Related use cases**

comments/see-all-threads.md
