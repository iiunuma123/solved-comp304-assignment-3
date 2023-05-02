Download Link: https://assignmentchef.com/product/solved-comp304-assignment-3
<br>
<h1>Problem 1</h1>

Consider the memory management methods of contiguous allocation, paging, and segmentation. Briefly compare these methods with respect to the following: external fragmentation and code sharing among processes (1-2 sentences per method are sufficient).

<h1>Problem 2</h1>

Suppose a computer that supports virtual memory and has 32-bit virtual addresses and uses page size of 8KB.

<ol>

 <li>How much space does its page table require if a single-level page table is used? Assumeeach table entry occupies 4 bytes.</li>

 <li>If the physical addresses are 28 bits, what is the physical memory size in MB?</li>

 <li>How many pages does the physical memory have?</li>

</ol>

<h1>Problem 3</h1>

(12 points) Consider the following page reference string: 1, 2, 3, 4, 2, 1, 5, 2, 1, 2, 3

How many page faults would occur if there are 3 frames allocated for a process for the page replacement algorithms: LRU, FIFO, Optimal in the following cases? Show your work. Remember all frames are initially empty, so your first unique pages will all cost one fault each.

<h1>Problem 4</h1>

(12 points) Consider the working-set model with the working set window ∆ being 7. Given the following system with 3 independent processes and their corresponding reference strings as shown below:

1

COMP 304- Operating Systems ( Spring 2020): Assignment 3                           <em>PROBLEM5</em>

<table width="320">

 <tbody>

  <tr>

   <td width="59">Time</td>

   <td width="24">0</td>

   <td width="24">1</td>

   <td width="24">2</td>

   <td width="24">3</td>

   <td width="24">4</td>

   <td width="24">5</td>

   <td width="24">6</td>

   <td width="24">7</td>

   <td width="24">8</td>

   <td width="24">9</td>

   <td width="24">10</td>

  </tr>

  <tr>

   <td width="59">P1</td>

   <td width="24">2</td>

   <td width="24">5</td>

   <td width="24">7</td>

   <td width="24">4</td>

   <td width="24">4</td>

   <td width="24">1</td>

   <td width="24">2</td>

   <td width="24">3</td>

   <td width="24">7</td>

   <td width="24">3</td>

   <td width="24">3</td>

  </tr>

  <tr>

   <td width="59">P2</td>

   <td width="24">1</td>

   <td width="24">1</td>

   <td width="24">1</td>

   <td width="24">3</td>

   <td width="24">3</td>

   <td width="24">4</td>

   <td width="24">4</td>

   <td width="24">3</td>

   <td width="24">5</td>

   <td width="24">6</td>

   <td width="24">7</td>

  </tr>

  <tr>

   <td width="59">P3</td>

   <td width="24">4</td>

   <td width="24">9</td>

   <td width="24">3</td>

   <td width="24">2</td>

   <td width="24">9</td>

   <td width="24">8</td>

   <td width="24">7</td>

   <td width="24">7</td>

   <td width="24">7</td>

   <td width="24">1</td>

   <td width="24">2</td>

  </tr>

 </tbody>

</table>

<ol>

 <li>According to the given data above, what is the working set and working set size for eachprocess at time 9 (inclusive)?</li>

 <li>Does the system suffer from trashing at time 9 (inclusive) if there are total 10 frames inthe physical memory? Why or why not? Show your work for credit.</li>

 <li>How many frames should be in the physical memory so that the system doesn’t sufferfrom trashing at time 7 (inclusive)? Show your work for credit.</li>

</ol>

<h1>Problem 5</h1>

(14 pts) Perform the Programming Problem (12.21) in page 534 in Chapter 11 (if you have the online version of the book, then it is in page 583 in Chapter 12) in edition 9. If you do not have the book, we have provided the related pages on Blackboard and necessary input files.

This part of the project does not require you to implement any program. Instead you have to run some commands to get familiar with the file system in Unix.

<ol>

 <li>Perform the commands on your system. Include snapshots of your runs in your submission.</li>

 <li>Answer the questions in the text book.</li>

</ol>

Student Name: