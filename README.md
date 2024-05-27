Git-Assignment-5 Solution

**For the detailed solution to this assignment, click this link:** https://medium.com/devops-guides/create-a-git-workflow-architecture-use-hotfix-to-push-a-file-git-assignment-5-6becb8ae107b


**Step 1:** First, we will create a main.txt file under the "master” branch.

**Step 2:** Create feature1 branch & here, create the "feature1.txt" file.

**Step 3:** Create feature2 branch & here, create the "feature2.txt" file.

**Step 4:** Instead of direct merging with master, we will create a new branch "test" & it's a precautionary branch to verify the work done. Merge feature1 & feature2 branches with the “test” branch.

**Step 5:** Merge "test" with “master".

**Step 6:** If release date is 9th of April, if client wants to add urgent.txt file in the “master”. We don't go to "feature1" & "feature2" because we have to repeat all the process one by one here. It's a tidy process.

**Step 7:** If our release date is on 09th April & we have a last minute changes, we will create a branch from master named as "hotfix". Here, create the “urgent.txt” file & merged the "hotfix" branch with "master". 

**Step 8:** After merging the branch, we will delete the "hotfix" branch. Now, the last minute changes will be successfully done in “master” & we are ready for release the product.
