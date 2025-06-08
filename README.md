<center><img src="redpopcorn.jpg"></center>

**Netflix**! What started in 1997 as a DVD rental service has since exploded into one of the largest entertainment and media companies.

Given the large number of movies and series available on the platform, it is a perfect opportunity to flex your exploratory data analysis skills and dive into the entertainment industry.

You work for a production company that specializes in nostalgic styles. You want to do some research on movies released in the 1990's. You'll delve into Netflix data and perform exploratory data analysis to better understand this awesome movie decade!

You have been supplied with the dataset `netflix_data.csv`, along with the following table detailing the column names and descriptions. Feel free to experiment further after submitting!

## The data
### **netflix_data.csv**
| Column | Description |
|--------|-------------|
| `show_id` | The ID of the show |
| `type` | Type of show |
| `title` | Title of the show |
| `director` | Director of the show |
| `cast` | Cast of the show |
| `country` | Country of origin |
| `date_added` | Date added to Netflix |
| `release_year` | Year of Netflix release |
| `duration` | Duration of the show in minutes |
| `description` | Description of the show |
| `genre` | Show genre |



Solve the following Assingnment:
# Netflix 1990s Movie Analysis

This project involves performing **exploratory data analysis (EDA)** on the `netflix_data.csv` dataset to gain insights specifically about movies from the **1990s decade**.

## Objectives

1. **Filter Movies from the 1990s**  
   Focus your analysis on movies released between **1990 and 1999** (inclusive).

2. **Determine Most Frequent Duration**  
   Identify the **most common movie duration** for this decade.  
   - Save the result as an approximate integer in a variable named:  
     ```python
     duration
     ```

3. **Count Short Action Movies**  
   Define a **short movie** as one with a duration of **less than 90 minutes**.  
   Count how many **action movies** meet this criteria and were released in the 1990s.  
   - Save this count as an integer in a variable named:  
     ```python
     short_movie_count
     ```

## Notes

- Use appropriate data filtering and grouping methods.
- You can use libraries like `pandas`, `matplotlib`, or `seaborn` to aid your analysis.
- After submitting the project, feel free to **experiment further** with the dataset.

## Dataset

Make sure the file `netflix_data.csv` is available in your working directory. The dataset typically includes fields such as:
- `title`
- `release_year`
- `duration`
- `genre`
- `type`

Happy analyzing!
