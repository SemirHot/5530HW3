# 5530HW3

<h1>Task 0/Initializing</h1>
I started out by getting the data into Google Colab and imported the CSV file. Once i did this i set the dataframe equal to diabetes_data and i called the head to just get an idea of what kin of data that im working with.
<img width="1003" alt="Screen Shot 2023-11-27 at 3 27 31 PM" src="https://github.com/SemirHot/5530HW3/assets/70181745/8c098b4e-f78e-43a8-981f-a90d48b5f2a9">


Once i did that i looked ahade in the assingment and saw i had to set a seed value and the sample size for the data that we are getting the sample data for, so i next set the seed to 75, i wasnt sure what number to go with so i just went for the first number that came to my head. After that i set the sample value to 25 as it said in the assingment. This worked for the first 2 tasks but for the third task i saw my results were slightly off so i had to set the seed value to 75 again in my last bit of code.

<img width="416" alt="Screen Shot 2023-11-27 at 3 27 50 PM" src="https://github.com/SemirHot/5530HW3/assets/70181745/3de4f664-b032-4504-8a0d-4e10c6e9953b">

<h1>Task 1</h1>
I started out with the sample data, i got the mean of the glucose from the sample set and i set that to sample_mean_glucose and did the same thing with sample highest glucose, i used the max() methode to do this and i set it equal to sample_highest_glucose. I set them equal to these values to make it easy to recall later when i am doing the visualziation for it. Before that i did the exact same thing for the population data. Once i had all of the things i needed to make my visualization i went with a barchart for both task 1 and 2. If we take a look at the results we can see that the sample mean was higher by 0.745, a very small amount but when we take a look at the highest, we can see that the population had a much greater max value comapred to the sample. 

![image](https://github.com/SemirHot/5530HW3/assets/70181745/6880cf21-1207-472f-a092-71f43fdb6ba6)
