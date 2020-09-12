# pandas-challenge
pandas_hw HeroesOfPymoli.ipynb
## Option 1: Heroes of Pymoli in 

Took what we took in class and created a dataframe for every table to displat an output.

I mainly created variables for columns and aggregating. I used the concept below.

#create variables out of columns and aggregating 
items = df["column_name"].aggregate() - count, mean, sum, etc

#create a data frame for display
data_frame = pd.DataFrame({
	"Column Output Name": [items]
