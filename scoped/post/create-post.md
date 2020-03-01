**Name**
Create post

----

**Actor** 
Signed-in user

----

**Subject area**
Any

----

**Preconditions** 
User is signed in and permitted to post (TL2+, or TL0/1 and not
rate-limited).

----

**Termination outcome**
User is on question/post page for the now-posted item.

----

**Basic flow**

- User clicks on "ask question" / "post" / etc button (name can vary by category).

- New page has:
  - for first-time poster, intro message w/link to help (just-in-time help; can be simple or omitted for MVP)
  - "New post in (category name)" - header to reinforce where you are (not changable via this interfact)
  - places to enter title, body, tags

- User enters title, body, at least one tag.  (For MVP we aren't doing any dupe-detection, auto-review, special guidance.)

- Optional: user chooses "preview" to see how the post will appear (unless we are doing an automatic in-page preview already, in which case we don't need this).

- User clicks "post" button.

- Page refreshes to show page for the individual post (e.g. question page).

----

**Notes**

Omitted for now: in-page preview, contextual guidance, switching categories, choosing post type.  Try not to do anything that precludes adding these features later.

For MVP, you post in a category by navigating to that category and then clicking "post"/"ask"/etc (same button, text can vary by category).

For MVP there is only one type of top-level post (question), but in the future there will be others.  In the future, therefore, the user will need to select a post type as part of post creation.  Possibly this is a menu on the button itself, so you've selected a type before you get the page with textboxes to fill out, or possibly it's an in-page control.  UX input wanted; feature not needed for MVP.


