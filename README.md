# cs214-assignment-2--returned-solved
**TO GET THIS SOLUTION VISIT:** [CS214 Assignment 2- Returned Solved](https://www.ankitcodinghub.com/product/cs214-assignment-2-returned-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;90754&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS214 Assignment 2-  Returned Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
Instructions

Download arraylist.c and arraylist.h.

1.&nbsp; Extend arraylist by adding a function al_insert:

int al_insert(arraylist_t *list, int index, int item);

al_insert(l,i,n) adds a new item n into the list l at index i. Any items at or after index i in the list will be

moved forward one space.

If i exceeds the current number of entries in the list, then i will become the new nal element of the list. Any newly created entries between the previous last entry and i are not initialized and will contain undetermined values.

If data is not long enough to contain the new list, then either double its length or extend its length to include index i, whichever is longer.

That is,

<pre>    al_init(&amp;A, 10);       // create with length 10
    al_insert(&amp;A, 10, 0);  // increases length to 20
    al_insert(&amp;A, 90, 0);  // increases length to 91
    // only the indicies 10 and 90 are initialized
</pre>
al_insert returns 0 if it successfully added the item to the list and 1 if it encounters an error, such as being unable to allocate memory.

Attach your modied copies of arraylist.h and arraylist.c.

2. (6 points) Using arraylist as an model, create a library for string buers (an array list containing characters). Rename the types and functions as appropriate (e.g., “arraylist” becomes “strbuf”). Include functions

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
https://sakai.rutgers.edu/portal/site/f55b6385-2252-4de5-a0e1-6b8fe3227eeb/tool/5b736e6b-8b6b-4963-af7f-8ab2a622a40c?panel=Main 1/3

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
1/24/22, 2:43 PM sakai.rutgers.edu : CS 214 — Spring 2021 : Assignments

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
corresponding to all the functions in arraylist, including al_insert. Ensure that the string held in data is null- terminated.

Add the following function:

int sb_concat(strbuf_t *sb, char *str);

sb_concat adds the string str to the end of the string held in sb. Assume that str is a null-terminated C string.

Return 0 if successful, and 1 otherwise.

Note that sb_append, sb_insert, and sb_concat will share similar code to extend the length of the data. Consider putting this code in a separate helper function.

Attach strbuf.h and strbuf.c.

3. (3 points) Consider the behavior of the following code fragments

<pre>    // 1
    char *buffer;
    ...
    for (i = 0; i &lt; N; ++i) {
</pre>
<pre>        strcat(buffer, input[i]);
    }
</pre>
<pre>    // 2
    strbuf_t *buffer;
    ...
    for (i = 0; i &lt; N; ++i) {
</pre>
<pre>        sb_concat(buffer, input[i]);
    }
</pre>
Assume that sucient memory has been allocated in both cases, that input contains at least N elements, and that all strings are null-terminated. Will there be any notable dierences in the performance of these code fragments?

Enter your answer in the text box, or attach a text le.

Submitted Attachments

arraylist.c ( 2 KB; Feb 25, 2021 9:42 pm ) arraylist.h ( 1 KB; Feb 25, 2021 9:42 pm ) strbuf.c ( 2 KB; Feb 25, 2021 9:43 pm ) strbuf.h ( 1 KB; Feb 25, 2021 9:43 pm ) Answer3.txt ( 1 KB; Feb 25, 2021 9:43 pm )

</div>
</div>
<div class="layoutArea">
<div class="column">
Additional instructor’s comments about your submission

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
https://sakai.rutgers.edu/portal/site/f55b6385-2252-4de5-a0e1-6b8fe3227eeb/tool/5b736e6b-8b6b-4963-af7f-8ab2a622a40c?panel=Main 2/3

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
Part1: 2 Doesn’t move all items forward correctly when insert Part2: 2 not nished

Part3: 1 O(n^2) vs O(n)

</div>
</div>
</div>
</div>
</div>
