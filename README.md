# PyCity School District Analysis

### The purpose of this challenege was to analyze the school district information and inspect it for academic dishonesty. The ninth grade reading and math scores from Thomas High School appear to have been altered. In order to uphold state-testing standards, the school board has asked us remove those scores from the data while keeping the rest of it intact. From there, the school district analysis will be repeated to give a more accurate description of the reading and math scores in the school district.

## Results

#### After removing the ninth grade scores from Thomas High School we are able to see how it affects multiple factors.

- The summary of the entire district changes very little. Because the number of students in the ninth grade at Thomas High School is such a small number compared to the total number of students in the district, there was very little movement in the statistics.

![District_Summary_Clean](https://user-images.githubusercontent.com/81929616/118413223-29445780-b66c-11eb-8d51-60e74d65e586.PNG)

- As you can see from the school summary data, Thomas High School did not really suffer when the ninth grade test results were removed from the data. Their passing perecentages for each subject and overall went down by about 0.3% across the board. The first chart shows where the school metrics stood before removing the test scores. The second one shows where they stood afterwards. 

![Thomas_HS_preclean](https://user-images.githubusercontent.com/81929616/118413470-7c6ada00-b66d-11eb-8340-01c3849df1fc.PNG)

![Thomas_HS_clean](https://user-images.githubusercontent.com/81929616/118413653-6b6e9880-b66e-11eb-88c6-f9cdb41bab15.PNG)

- When comparing the schools against each other, Thomas High School still ranked among the top 5 high schools in the entire school district both before and after the clearing of the ninth grade test scores.

![Clean_School_top5](https://user-images.githubusercontent.com/81929616/118413733-c6a08b00-b66e-11eb-9cc4-16604b97566a.PNG)

- The top 5 schools ranked well above the bottom 5 schools, as you can see from the statistics of the bottom schools.

![Clean_School_bottom5](https://user-images.githubusercontent.com/81929616/118413758-e46df000-b66e-11eb-8f3c-b6a1a640784e.PNG)

- When looking at the math and reading scores by grade per school, the only differences we see here is that in the 9th grade column for Thomas High School, the value of NaN is listed, which means "not a number". The reason for this is that these were removed earlier in the exercise. The first chart shows math scores, the second shows reading.

![Math_scores_by_grade](https://user-images.githubusercontent.com/81929616/118413819-44649680-b66f-11eb-9f25-aedd78cdcf0f.PNG)   ![Reading_scores_by_grade](https://user-images.githubusercontent.com/81929616/118413824-4890b400-b66f-11eb-846c-dda57e77c72b.PNG)

