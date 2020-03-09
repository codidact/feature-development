**Name**  
Browse post list

----

**Actor**  
Any user

----

**Subject area**  
Any post list (in any category)

----

**Preconditions**  
None

----

**Termination outcome**  
User is back on post list or has navigated away to an individual post

----

**Basic flow**

User sees a page with a list of posts.  Each item on the list shows the post title, tags, up/down votes (if applicable), user name/link for the person who last modified it, and timestamp of last modification.

User scrolls or pages through list reading info until spotting a post of interest.

Upon spotting an interesting post, user clicks to read the individual post.  (Possible termination condition.)

**If the user returns to the question page via browser 'back'**, user should be in the same position in the post list (not back at the top or back on page one if pagination was involved).

User continues browsing (iterating above steps).  Upon reaching the bottom of the page, user sees pagination controls and chooses "next page" or a specific page number among those shown.

