**Name**
See All Comment Threads

----

**Actor**
Any user

----

**Subject area**
Any post with more comment threads than display limit.

----

**Preconditions**
None

----

**Termination outcome**
All top-level comments are visible with their reply counts.

----

**Basic flow**

- User sees a post with its first N threads shown (see assumptions in view-thread.md about display) and an indication of additional threads such as "4 more threads".
- User selects a "show all threads" control.  Perhaps "4 more threads" is a link that does that or perhaps there is another control (defer to designers).
- New threads are added in-place in collapsed state.

----

**Notes**

Should there be a way to collapse threads (a "collapse everything" control)?  If so, should it always be present, even if the thread count didn't exceed the limit?

If the user's trust level allows seeing archived threads, they are shown but with a visual indicator of their status.

----

**Related use cases**

comments/view-thread.md
