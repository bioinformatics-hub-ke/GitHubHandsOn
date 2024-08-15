## Alphabetize participants list
### Tutorial instructions

Now comes the fun part! You will create something that sounds simple: an alphabetical list of all the workshop participants on GitHub.
Below are few rules:

1. **Name Submission:** Each participant can only enter their own name. To do this, each participant will create a branch in the shared [repo](https://github.com/bioinformatics-hub-ke/ParticipantsList-GitHandsOn/tree/main) . The branch should be named in the format `FirstName_LastName`. In this branch, you will write your name (FirstName LastName) in the `README.md`.

2. **Binary Tree Structure:** The list must be compiled as a binary tree. Pair up with another participant and merge both lists into one of your branches. You will need to use `git fetch`, keeping in mind that your partner's branch is a remote branch. Together, resolve any conflicts and ensure the list is alphabetized.

3. **Merging Pairs:** After pairing up, merge the result with another pair. The participant whose name appears earliest in the alphabet is responsible for merging into their branch. Ensure the list remains alphabetized after resolving conflicts. At this stage, you will have a list of four participants.

4. **Final List:** Continue merging until you have the final list of all participants. Merge that into the master branch.

5. **Verification:** Use git log --graph to verify that you have followed the binary tree structure

6. **Cloning:** The easiest way to get started is to clone our [GitHub repository](https://github.com/bioinformatics-hub-ke/ParticipantsList-GitHandsOn/tree/main).


### Acknoledgement:

The idea for this tutorial was developed by [Samuel Coulbourn Flores](https://github.com/samuelflores) for the [MedBioInfo](https://www.medbioinfo.se/) course. It has been adapted for use in this workshop.
