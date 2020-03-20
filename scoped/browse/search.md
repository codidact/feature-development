**Name**  
Search

----

**Actor**  
Any user

----

**Subject area**  
Any page on the site

----

**Preconditions**  
None

----

**Termination outcome**  
User sees a list of search results.

----

**Basic flow**

User selects the search box (gives it focus).

Contextual help appears, summarizing the basic search operations and linking to a help topic with more info (advanced search options).

User reads the contextual help and dismisses it (or not).

User types a search query and chooses a scope: search in (name of current cagegory), search in all categories.

A page of posts matching the search appears.  Each post indicates its type (question, answer, wiki, etc).  If user searched all categories, results indicate category for each post.

User clicks a search result and goes to that page.  If the result was an answer, the page is positioned at the answer (not the top).  User reads stuff and uses browser "back" to return to search results.

User refines the search by editing the search query (which is shown on the results page).  The user's context choice is pre-selected but can be changed.  User makes changes and submits.

Search results are updated.



----

**Notes**  

Order of search results is unspecified.  Changing the order (e.g. sort by relevance, score, age...) is out of scope for MVP but will be needed later.

If search results include more than one category, how categories are shown is unspecified.  Feel free to either group by category or indicate category for each result.

Design note: use the right column to show expanded search help -- the info in that initial help that the user might have dismissed, plus more advanced search help.  This is the same info that was linked in the initial help.

