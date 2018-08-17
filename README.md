Bob and Carol failed to pull from master when they switched to Bob's computer. After this happened, the master on Bob's computer did not match, which led to a merge conflict. 

After we resolved that, we made the mistake of adding new features in the master branch, instead of making separate branches, which caused Alice's changes to be rejected when we wanted to push to master. 

What we should have done:
Bob should have pulled from master to ensure he was on the newest, most up-to-date code. 
Never code on the master branch.
