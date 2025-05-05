# ec4-403-assignment-3-model-predictive-contol-solved
**TO GET THIS SOLUTION VISIT:** [EC4.403 Assignment 3-Model Predictive Contol Solved](https://www.ankitcodinghub.com/product/ec4-403-assignment-3-model-predictive-contol-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95469&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EC4.403 Assignment 3-Model Predictive Contol Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (5 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
In this assignment we will pose local planning as a optimization problem with constraints and use predictive control technique called as Model Predictive Control(MPC) to execute the plan. You need to have some understanding of optimization [1]. Please use the resource attached for discrete MPC(available on Moodle, MPC subsection).

Question:

Implement a discrete MPC planner for omni-wheel robot. You must implement the MPC algorithm for a two cases (i) With Obstacles (ii) Without Obstacles. You can use solvers like cvxopt in python or any other equivalent in Matlab.

• Your planner for a robot needs to satisfy various constraints on speed, acceleration, obstacle avoid- ance to make it feasible. Additionally your plan needs to optimize some aspect in your environment like speed, time or safety. Your plan should be n steps into the future.

You should frame Quadratic Programming QP for your planner to minimize goal reaching cost given by:

</div>
</div>
<div class="layoutArea">
<div class="column">
robot model is given by

velocity constraints are given by

</div>
<div class="column">
(xn −xg)2 +(yn −yg)2 xt+dt =xt +vxt ∗dt

yt+dt =yt +vyt ∗dt 0≤vxi ≤vmax ∀i∈[1,n]

0≤vyi ≤vmax ∀i∈[1,n]

</div>
</div>
<div class="layoutArea">
<div class="column">
• For (i)(with obstacles) : Extend the planner by adding circular obstacles. You can use euclidean distance constraint for obstacle avoidance. This adds Quadrtic constraint to Your problem. For example an static obstacle of radius r1 which is located at (xo, yo) then your constraint is given by.

(xi −xo)2 +(yi −yo)2 ≥r12 ∀i∈[1,n]

References

[1] https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf 1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Deliverables:

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>Code for both the cases. You can use Python, MATLAB or whichever language you are comfortable with. Please ensure the code is well written, and we can ask you to explain certain snippets of it during the evaluations.</li>
<li>A report summarising your understanding of the algorithms and explaining the results.</li>
<li>Put all these files in a folder 〈TeamName〉, zip it, and submit it on moodle.Feel free to reach out to the TA’s for any queries. All the best, and may the Force be with you.</li>
</ul>
</div>
</div>
</div>
