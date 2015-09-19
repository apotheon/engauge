# Working On Engauge

1. Pick an issue from the issue tracker and assign it to yourself.

    example:
    
        add current user engaugements list

2. Fork the project.

3. Create a local branch in your development environment to work on the story.

    example:

        $ git checkout -b add-user-engaugement-list

4. Work on the story until it's complete, using red/green/refactor loop.  Make
   sure all tests for the project (still) pass.

    example:

        $ bundle exec spec

5. Commit branch to github.

    example:

        $ git commit -am "add current user engaugements list"

6. Create a pull request using the template.

    See PULL_REQUEST_TEMPLATE.MD

    Make sure the branch can merge cleanly with master.  You may need to merge
    the current state of master into your branch from your local checkout:

        $ git fetch
        $ git merge origin/master

7. Contact someone to request a code review.

8. Check review comments and make necessary changes.  Commit changes to address
   comments and push when finished.

    Expect reviews to be nitpicky; the reviewer may very well nitpick.  The
    project's standards will hopefully be high.  Take critiques as
    opportunities to improve rather than as personal criticism.  If someone
    asks you to review code, try to apply the highest standards of quality to
    any changes when commenting.  See CODE_REVIEW.md for guidelines.

9. Request someone with upstream commit access to give the code a last review
   and, if the changes are accepted, to merge with upstream.
