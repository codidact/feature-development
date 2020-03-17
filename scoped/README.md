## Use Cases

Partial index of the use cases in this directory:

- **sign-up** and **authentication**: account creation, login

- **browse**: "read" cases, mostly: question list (including expanding a
question), individual question, choosing a category, search

- **post**: create top-level post (currently just questions), answer question, rate-limited cases of those, create tag

- **edit**: suggest edit, review a suggested edit, edit directly (without review)

- **comments**: reading, replying, muting a thread, moderating comments (includes deleting comments/threads, archiving threads, declining comment flags)

- **vote**: just voting on posts so far; see also **flag** which includes hold votes

- **flag**: flag post or comment; also contains hold/dupe-handling: suggest {hold, duplicate}, review, author response.  In file names, "-OP" means author actions, '-other" means another user seeing the question after a hold/dupe vote happened, and the base name is that initial vote.

- **mod**: moderation actions at TL4 and TL5: lock, unlock, delete (more to come)


Several use cases call for contextual help, descriptions of options, responses to user actions, etc.  The use cases include the *gist* of these bits of text, but none of that is final content.  The goal *now* is to give the designers a hint about how where we'll need roughly how much text.  The actual messages will be written later, in conjunction with the designs.

