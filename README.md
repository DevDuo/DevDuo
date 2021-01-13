# devduo
there are documentation of how our development should work

## Development workflow
1. create a branch with a name simular to the issue name
2. develop the feature and push commits to your branch
3. keep your branch uptodate with the develop branch by rebasing your branch
    * >`git checkout develop && git pull`
    * >`git checkout <your_branch> && git rebase develop`
4. open a `PR` with the same name as the issue you are working on
5. Add a brief enough description to completly understand what that `PR` is about
6. (*) Add a screenshot gif, or video if applicable
5. link the issue you have worked on in the `PR` you just opened
6. when finished just ask for a code review to merge your code into develop
