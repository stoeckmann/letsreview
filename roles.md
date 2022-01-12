# Roles in Code Review Groups

Just like in any given group of people, diversity in personalities has
positive impacts on the overall group performance. But what kind of
roles or archetypes exist from a review perspective?

## Hacker

A hacker tries to disassemble and tinker with any given aspect of a
product in order to understand every single bit of it. Applying a good
amount of creativity by thinking out of the box might reveal rare edge
cases and other often overlooked or even novel bugs or lack of design.

## Historian

The historian has a very good understanding of how hardware developed
over time. By considering the time at which the software was written the
historian can easily apply such knowledge of changed conditions to see
if the code was written to cover all these situations. We all know that
640 KB of RAM is enough, right? Classes of bugs which were supposed to
be fixed decades ago are still well known to the historian, so if they
appear again, they will be directly spotted.

## Librarian

When it comes to standards and specifications, then the librarian knows
them all. Mastering such profession means that at any moment a group
member has a question, the librarian can quote the relevant documents.
Proper categorization also means that common ideas within software are
easily spotted and compared. The librarian does not need creativity to
find bugs but can rely on work other developers spent in their own
projects, which the librarian simply looks up for comparison.

## Moderator

Large groups benefit from moderators to make sure that social aspects
within the group itself are properly covered. If a reviewer gets lost
or another is too fast, the moderator can remind everyone that this is
a group activity and nobody should feel or actually be excluded.

## Translator

The translator is able to detect the abstract concept of a code and to
articulate it in a way that fellow members can grasp the concept even if
they do not understand the programming language.

Such an abstraction can help others to apply their skills on the concept
without language barriers in their way.

## User

Users of software which is reviewed have a good understanding of the way
the software is actually used. Maybe the code is hard to understand but
the user can easily help out when it comes to hitting this special
feature under review with a real world example. If anyone can judge
about the quality of a comment or the documentation, the user is the
best one to ask.

# Things to Consider

Nobody is fully described by just one of these roles and a group can be
verify effective even without covering all of them. The most important
aspect is: Be excellent to each other! If someone approaches a problem
in a different way than you do then it does not imply that it's the
wrong way. And if an approach takes longer than the other, be patient.
You never know which question arises from different approaches. This
also means that seniors should always involve juniors. Never assume that
juniors are just there to learn! Good questions of juniors can easily
get seniors into trouble coming up with equally good answers.

## Authors in Review Groups

Having the author of a software product under review in your group can
have advantages and disadvantages.

The advantage is that the author can supply the group with information
which is not written anywhere, like future direction, historical
background or design choices.

The disadvantage is that authors tend to become blind to bugs and
design flaws. They know exactly what they wanted to achieve, which is
not necessarily what they actually wrote down. By influencing the group
with too much information the group may overlook difficult or complex
code which they would have had to carefully look through otherwise.

A performing group benefits the most from an author. A learning group
should inspect the code first and ask the author afterwards. This is
comparable with a book review or public reading. If you ever have the
chance to discuss various interpretations of a text with the author,
it is best to be prepared by reading it beforehand on your own.
