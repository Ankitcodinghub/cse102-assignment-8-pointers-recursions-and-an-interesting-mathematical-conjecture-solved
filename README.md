# cse102-assignment-8-pointers-recursions-and-an-interesting-mathematical-conjecture-solved
**TO GET THIS SOLUTION VISIT:** [CSE102 Assignment 8-Pointers, recursions and an interesting mathematical conjecture Solved](https://www.ankitcodinghub.com/product/cse102-assignment-8-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101992&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE102 Assignment 8-Pointers, recursions and an interesting mathematical conjecture Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
In this assignment, you will experiment with pointers, recursions and an interesting mathematical conjecture, namely Collatz.

Collatz conjecture has not been proven yet even though it is seemingly a simple problem. Consider the following function:

𝑓(𝑥)= {3𝑥+1 𝑖𝑓𝑥𝑖𝑠𝑜𝑑𝑑 𝑥/2 𝑖𝑓 𝑥 𝑖𝑠 𝑒𝑣𝑒𝑛

Starting with an integer 𝑥0 the sequence 𝑥1 = 𝑓( 𝑥0), 𝑥2 = 𝑓( 𝑥1), … tends end up with a loop 4, 2, 1, 4, 2, 1… Conjecture says that any starting integer should send this sequence to the same loop. (See https://www.youtube.com/watch?v=094y1Z2wpJg for an overview of this conjecture).

Towards the analysis of this conjecture, you are asked to write a few C functions:

<ol>
<li>(25 pts) Write a recursive function to generate and return the sequence.void generate_sequence (int xs, int currentlen, int seqlen, int *seq)
Where xs is the first element of the sequence, seqlen is the length of the sequence, currentlen is the length of the sequence in the time of the function called, *seq is the array of the sequence.
</li>
<li>(30 pts) Write a recursive function such that given any function and a starting integer check if the sequence ends up in a loop.The first input is the function for which the sequence will be generated (fill its parameters declared with “?” above), starting from the first integer xs with a length of seqlen. The last two arguments will return the loop and its length. If no loop is found, the function will not update *loop array and return 0 with looplen variable.
Note that the loop’s length can be n/2 at most and 2 at least, you should search for a loop with every possible length (until you find one) in descending order.
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
void check_loop_iterative(void (*f)(?), int xs, int seqlen, int *loop,

</div>
</div>
<div class="layoutArea">
<div class="column">
int *looplen)

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
CSE102 – Spring 2022 Assignment #8

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol start="3">
<li>(20 pts) To be used in the previous function, you are asked to write a function to check if a given sequence of numbers has a loop in it.int has_loop(int *arr, int n, int looplen, int *ls, int *le)
Thefunctionwillreceiveasequencestartingfromarr[0]andendingatarr[n-1]. Itwill check if there are any loops with a length of looplen. The first occurrence of the loop will be output with parameters ls and le.

This is not a void function, it will return 1 if a loop exists, 0 otherwise.

For example,

{15, 7, 4, 2, 1, 4, 2, 1}

has a loop starting at arr[2] and ending at ar[4]. In this case ls=2 and le=4.
</li>
<li>(25 pts) Write another recursive function that calculates the histogram of the first digits of thesequence generated by a given function.
As before the first three parameters are for the generation of the sequence. h is the histogram of the first digits of the numbers that appear in the sequence. The size of this array will be 9 (you will ignore digit 0).

For the following sequence:

{340, 170, 85, 256, 128, 64, 32, 16, 8, 4, 2, 1, 4, 2, 1}

The first digits of each integer:

{3, 1, 8, 2, 1, 6, 3, 1, 8, 4, 2, 1, 4, 2, 1}

The resulting histogram (*h) would be: {5,3,2,2,0,1,0,2,0}

meaning that there are 0 numbers starting with digit 5 while there is only one number starting with digit 6.

Every time this function is being called; it should find the total numbers of integers starting with digit.
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
void hist_of_firstdigits(void (*f)(?), int xs, int seqlen, int *h, int

</div>
</div>
<div class="layoutArea">
<div class="column">
digit)

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
CSE102 – Spring 2022 Assignment #8

</div>
</div>
<div class="layoutArea">
<div class="column">
Program flow:

<ul>
<li>❖ &nbsp;In main, take the first element and the size of the sequence as inputs from the user (assume that the inputs will be proper, i.e., positive integers).</li>
<li>❖ &nbsp;In main, call the check_loop_iterative function.</li>
<li>❖ &nbsp;In check_loop_iterative function, generate &amp; print the sequence (print it only once). Also, checkif the sequence has a loop. If there is a loop, print its size and the indexes of its first occurrence.
Do not print the loop itself in this function.
</li>
<li>❖ &nbsp;In main, print the loop (if any). If there is no loop, print this information.</li>
<li>❖ &nbsp;In main, call the hist_of_firstdigits function.</li>
<li>❖ &nbsp;Print the histogram array in main.General Rules:
<ul>
<li>Obey the style guidelines.</li>
<li>Do not change the provided function prototypes (you will not get any credits).</li>
<li>The program must be developed on Ubuntu using GCC compiler (version provided in class),compilation problems due to the use of another OS or compiler is your responsibility (you will
not get any credits).
</li>
<li>Your program should work as expected. Do not expect partial credit if your code works only insome cases but not in all cases as expected.</li>
<li>Do not use any libraries other than stdio.h, stdlib.h and util.h. You can add new functions but donot change the structure of the functions given above. Parse the parameters by using pointers
as shown above.
</li>
<li>Use malloc/calloc functions from stdlib library, make sure your program won’t end up with asegmentation error.</li>
<li>Add comments to your code.</li>
<li>You can ask your questions about the homework by using the assignment post on Teams.Handing in your work:
<ul>
<li>Hand in your work using the appropriate class Teams assignment site.</li>
<li>No late submissions will be accepted.</li>
<li>Please pack your solution directory in the following way (assuming a student with number20180000001 andnameXYZissubmitting):</li>
</ul>
</li>
</ul>
</li>
</ul>
o A directory named 20180000001_X_Z is created

o Allthesolutionsfilesalongwithamakefilearecreatedaspartoftheassignment.For

example:

o Packthisdirectoryintoazipfilenamed20180000001_X_Z.zip

o WhenunpackedasaboveinUbuntu(versionprovidedinclass)itshouldallowexecuting

the following commands in a shell:

<ul>
<li>▪ &nbsp;“$makeclean”removeseverythingexceptmakefile,sourcecode(.cand.h)andother resource files (if any) – all compiling results and intermediate files should
be removed.
</li>
<li>▪ &nbsp;“$makecompile”shouldcompilethecode.</li>
<li>▪ &nbsp;“$makerun”shouldrunthecodealongwithanyparametersneeded.</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
CSE102 – Spring 2022 Assignment #8

</div>
</div>
<div class="layoutArea">
<div class="column">
Expected outputs (first two rows are inputs, the rest is output only)

</div>
</div>
</div>
