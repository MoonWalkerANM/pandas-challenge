# pandas-challenge
This assignment covered combining the students and school data based on the school name for the school district to review and analyze the students' math and reading scores with other information on the schools that they attend.
The data were compiled and created the dataframe called school summary consisting the following information - 
    School name
    School type
    Total students
    Total school budget
    Per student budget
    Average math score
    Average reading score
    % passing math 
    % passing reading 
    % overall passing 
At a glance, the charter schools' average grades as well as percent of passing are way better than district.  It is proven at the end when the scores are compared by school types.  The top 5 Highest-Performing Schools by percentage of overall passing are all from Charter type.  The lowest performing schools by percentage of overall passing are as expected as from district type.

            	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
School Type					
Charter	          83.473852	        83.896421	            93.620830	     96.586489	         90.432244
District	      76.956733	        80.966636	            66.548453	     80.799062	         53.672208


After reviewing school spending per student, it can be seen that the average grade and % of passing are inversely correlated to the spending ranges.  It proves that putting more money into the school did not increase students' performances.

                            	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Spending Ranges (Per Student)					
<$585	                         83.455399	         83.933814	             93.460096	       96.610877	     90.369459
$585-630	                     81.899826	         83.155286	             87.133538	       92.718205	     81.418596
$630-645	                     78.518855	         81.624473	             73.484209	       84.391793	     62.857656
$645-680	                     76.997210	         81.027843	             66.164813	       81.133951	     53.526855


When comparing the school sizes with the students' performances, the large school size has the lowest performance, but the difference between small and medium sizes are minimal and not conclusive.

	                Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
School Size					
Small (<1000)	     83.821598	         83.929843	            93.550225	      96.099437	        89.883853
Medium (1000-2000)	 83.374684	         83.864438	            93.599695	      96.790680	        90.621535
Large (2000-5000)	 77.746417	         81.344493	            69.963361	      82.766634	        58.286003

In addition to the limited data given, it will be useful to have the students-teacher ratio and average household income for students of each school.  These two information could give us better understanding on what affects the students' performance.