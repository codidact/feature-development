**Name**
Review edit while browsing

----

**Actor**
Logged-in user with trust level that allows reviewing edits.

----

**Subject area**
Post with a pending edit.

----

**Preconditions**
None

----

**Termination outcome**
User is on same page, updated if edit was applied.

----

**Basic flow**

- User browsing the site sees a "pending edit" notice on a post.
- User clicks the link and sees the same "review edit" interface as in author-review-edit.md.
- User chooses:
  - Accept: if, with this acceptance, the threshold for approvals is satisfied, apply edit as in related use case.
  - Accept: if, with this acceptance, the threshold is not satisfied, show message like "thank you for your review; this edit still needs to be reviewed by others".
  - Reject: either reject or add vote + message like for accept.
- Change state of the "pending edit" notice somehow to indicate that user has already done that.
