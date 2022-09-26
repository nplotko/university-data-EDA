# University Exploratory Data Analysis with Plotly
This analysis works to explore the Plotly library by exploring the university dataset.

The dataset has the following columns: <br>
<ul>
  <li>world_rank - The rank of the school</li>
  <li>university_name - The name of the school</li> 
  <li>country - The country the school is located</li>
  <li>teaching - The score for teaching</li>
  <li>international - The score for international</li>
  <li>research - The score for research</li>
  <li>citations - The score for citations</li>
  <li>income - The income of the school</li>
  <li>total_score - The total score of the school</li>
  <li>num_students - Total number of students</li>
  <li>student_staff_ratio - The number of students per one staff member</li>
  <li>international_students - The percent of international students</li>
  <li>female_male_ratio - The number of females : The number of males</li>
  <li>year - The year of the ranking</li>
</ul>  
<br>
I make visualizations to compare the female/male ratios and the number of students in top universities. I also make visualizations to discover how the total score varies with the world rank. I examine the research/teaching scores for top universities. See the university_analysis.ipynb notebook to see the code. Some outputs are available as an svg image. Others are only available if you download the notebooks (the plots which call iplot). To see the interactive version of the plotly visualizations, remove the "svg" parameter from fig.show(). 
<br>
I also trained a linear regression model to predict the total_score for universities. This is at the bottom of the notebook.

