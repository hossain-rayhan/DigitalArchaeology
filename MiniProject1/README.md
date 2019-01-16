Mini Project1 - Text Analysis
===========

Please read the entire assignment.

Workflow
===============
1. To start, [**fork** repository][forking] [github.com/fdac18/MiniProject1][assignment]
    1. Go to github.com/fdac18/MiniProject1
    1. Click on "Fork Repository" button
	1. Select your GitHubID as the organization to fork to
	1. Go to Settings and enable issue tracking
1. Connect to your docker container
1. [**Clone**][ref-clone] the forked repository to your docker container

     ```
     git clone https://github.com/YourGHUsername/MiniProject1
     ```
1. Copy MiniProject1.ipynb to YourUTKID.ipynb

       ```
       git add YourUTKID.ipynb
       git commit -m "YOUR commit message"
       ```
1. Now back in the shell [**Push**][ref-push]/sync the changes to github.

	git push

1. At https://github.com/YourGHUsername/MiniProject1
   Create a [**pull request**][pull-request] on the
   original repository [fdac18/MiniProject1][assignment]  to
   turn in the assignment.


Social Workflow with deadlines
==============================

1. Do the first four steps listed above before the class on Sep 10: if you have any
   issues, we need to clarify them on Sep 7
1. Come up with an idea of what analysis you are going to use and
   what data sources you will use. Discuss it with your assigned peer
   (see dendrogram in
   [students/teaming.png](https://github.com/fdac18/students/blob/master/teaming.png).
   You present the idea to your peer below you in the dendrogram and you
   produce a comment for the peer above you in the dendrogram. The
   bottom one presents to the top one and the top one raises issue
   for the bottom one.
   The top person in the dendrogram comments on the presentation of
   the bottom person.  To access your peer's forked repository, manually enter the url:
   https://bitbucket.org/YourPeersGHUsername/MiniProject1
   The mapping of the GH ids to UTK IDs is in students/ports.md 

When you raise an issue, you should assign it to the GHUSER who should comment on it.
1. Start doing the analysis and discuss your progress with your peer
   so that you are done before class on Sep 12. In case you encounter any problems
   retrieving, storing, or analyzing data please discuss them with
   your peer and, if needed, escalate.
1. Prepare a few slides explaining the approach and findings and
   present to a small group as specified below.
1. We will have the entire class on Sept 12 for you to practice presentations in several groups (the order is from students/teaming.png)
    1. Group 1: ssteinb2 to hchang14
    1. Group 2: nmansou4 to mkramer6
    1. Group 3: awili13 to gjones2
    1. Group 5: eherron5 to mmahbub
    1. Group 6: trahman4 to mousavi
    1. Group 7: jpace7 to adesai6 
    1. Group 8: eezel3 to cmawhinn
1.  At the end of the presentations within the group a vote will be held (by that group) for one 
    presentation to be selected to be presented to the entire class. The first listed in each group will record that in issue https://github.com/fdac18/MiniProject1/issues/1


What operational data traces are expected
==
1. I expect you to make at least one commit (in your cloned
   repo) by Sep 7, at least three by Sep 10, and at least five total.
1. Each interaction with your peer should result in an issue that
   describes your peers comments. If you have any questions to your
   peer before each class, please document them in an issue. Both
   comments and questions should be raised against your forked
   repository. In sum: there should be at least three issues raised.

Presentations should include
===
* What is the question?
* What was the approach?
* What problems did I encounter?
* What results did I get?
* What new ideas did this generate?


<!-- Links -->
[assignment]: https://github.com/fdac18/MiniProject1
[forking]: https://guides.github.com/activities/forking/
[ref-clone]: http://gitref.org/creating/#clone
[ref-commit]: http://gitref.org/basic/#commit
[ref-push]: http://gitref.org/remotes/#push
[pull-request]: https://help.github.com/articles/creating-a-pull-request
