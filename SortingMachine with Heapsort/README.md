Project: SortingMachine with Heapsort
 
Objectives
Familiarity with writing a kernel class for a new type and its kernel operations (SortingMachine layered on Queue and arrays, using heapsort).
Familiarity with developing and using specification-based test plans.
The Problem
The problem is to complete and carefully test implementations of the constructor and all kernel methods defined in interface SortingMachineKernel, building the data structure representing a SortingMachine object by layering it on top of Queue and arrays. The algorithmic approach is to use the heapsort sorting algorithm discussed in class.


Setup
Only one member of the team should follow the steps to set up an Eclipse project for this assignment. The project should then be shared with the rest of the team by using the Subversion version control system as learned in the Version Control With Subversion lab.

To get started, import the project for this assignment, SortingMachineWithHeapsort, from the SortingMachineWithHeapsort.zip file available at this link. If you don't remember how to do this, see these Setup instructions from an earlier project.

Method


Complete the bodies of the exchangeEntries, siftDown, heapify, buildHeap, and createNewRep private methods, and of the kernel methods (add, changeToExtractionMode, removeFirst, and size) in SortingMachine5a in the src folder. The kernel methods isInInsertionMode and order are trivial and already implemented (but should still be tested).
Note that a strict requirement for your implementation is that you use the recursive algorithms discussed in class for the private methods siftDown and heapify. A significant penalty will be applied for using any other algorithms (recursive or not).

Develop a complete and systematic test plan for the SortingMachineKernel constructor and kernel methods and add your test cases at the end of SortingMachineTest in the test folder. Note that you may have already developed such a test plan for a couple of earlier labs (Queue Insertion Sort and Queue Quicksort). Just make sure you improve it as necessary to meet the standards of quality and completeness that have been discussed before.
When you and your teammate(s) are done with the project, decide who is going to submit your solution. That team member should select the Eclipse project SortingMachineWithHeapsort (not just some of the files, but the whole project) containing the complete group submission, create a zip archive of it, and submit the zip archive to the Carmen dropbox for this project, as described in Submitting a Project. Note that you will only be allowed one submission per group, that is, your group can submit as many times as you want, but only the last submission will be on Carmen and will be graded. Under no circumstance will teammates be allowed to submit separate solutions. Make sure that you and your partner agree on what should be submitted.
