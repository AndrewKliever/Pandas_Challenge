Written report

1.small to medium sized schools by student population have a higher passing average in both math and reading.
2.charter schools have a higher passing percentage of students than district schools even though the spending range per student is similar 

the conclusion i draw from this information is charter schools are able to give more attention to their students due to smaller class sizes or have a better curriculum resulting
 in a better education than district school. the amount of money per student does not seem to have a correlation between passing rates either, indicating the resources are not the issue either. 
further supporting that class size has a larger effect on grades than school funding.



dataframes list

- sch_df 
	is the 1st read csv file

- stu_df
	is the 2nd read csv file

- school_info_df
	is the merged dataframe of both csv files

- district_summary_df 
	is the snap shot of all merged info

- School_summary_df
	is schools comparison of passing :reading, math and overall

- top_schools
	is schools decending list by overall passing

-lowest schools
	is school in assending list

- math_score_by_grade
	is schools math score comparison

- reading_scores_by_grade
	is schools reading score comparison

- school_spending_df
	schools binned by budget per student

- school_size_df
	schoos binned by # of students




Chat Gpt was used to assist with certain formatting aspects like "school_spending_df['Per Student Budget'] = school_spending_df['Per Student Budget'].replace(r'[\$,]', '', regex=True).astype(float)"
