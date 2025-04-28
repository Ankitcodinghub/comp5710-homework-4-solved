# comp5710-homework-4-solved
**TO GET THIS SOLUTION VISIT:** [COMP5710 Homework 4 Solved](https://www.ankitcodinghub.com/product/comp5710-questions-contact-xiaopu-peng-problem-descriptions-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117884&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP5710 Homework 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
Problem 1:

For the following program, list the program slice by ONLY USING LINE NUMBERS for “average” in statement 26.

1. int exam() {

2. A = 0;

3. B = 0;

4. C = 0;

5. Fail = 0;

6. Count = 0;

7. TotalMarks = 0;

8. while (!eof()) {

9. scanf(“%d”, Mark);

10. if (Mark &gt;= 90) {

11. A = A + 1;

12. } else if (Mark &gt;= 80) {

13. B = B + 1;

14. } else if (Mark &gt;= 60) {

15. C = C + 1;

16. }

17. if (Mark &lt; 60){

18. Fail = Fail + 1;}

19. Count = Count + 1;

20. TotalMarks = TotalMarks + Mark;

21. }

22. printf(“Out of %d, %d passed and %d failed “, Count, A + B + C, Fail);

23. printf(“%d students got A”, A);

24. printf(“%d students got B”, B);

25. printf(“%d students got C”, C);

26. average = TotalMarks / Count;

27. printf(“The average was %d “, average);

28. PassRate = (Count – Fail) / Count * 100;

29. printf(“This is a pass rate of %d “, PassRate);

30. return 0;

31. }

Problem 2:

For the following program, list the program slice by ONLY USING LINE NUMBERS for “countEven” in statement 21.

1 #include&lt;iostream.h&gt;

2 void main(){

3 int countEven=0; 4 int countOdd=0;

5 int countZero=0;

6 int arr[10], i;

7 for(i=0; i&lt;10; i++){

8 cin&gt;&gt;arr[i];

9 }

10 for(i=0; i&lt;10; i++){

11 if(arr[i]%2==1){

12 countOdd++;

13 }

14 if(arr[i]==0){

15 countZero++;

16 }

17 if(arr[i]%2==0){

18 countEven++;

19 }

20 }

21 cout&lt;&lt;“Even Numbers = “&lt;&lt;countEven&lt;&lt;” “;

22 cout&lt;&lt;“Odd Numbers = “&lt;&lt;countOdd&lt;&lt;” “;

23 cout&lt;&lt;“Zero = “&lt;&lt;countZero&lt;&lt;” “;

24 }
