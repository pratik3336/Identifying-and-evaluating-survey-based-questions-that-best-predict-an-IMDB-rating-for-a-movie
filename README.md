# Identifying-and-evaluating-survey-based-questions-asked-to-Customers-that-best-predict-an-IMDB-rating-for-a-movie

Analyzing the survey questions to determine which are most predictive of a movie's IMDB rating, critic meta-score, or gross USA ticket sales. 


Data variables description:

SURVEY QUESTIONS: All of the following variables are direct reports of survey questions that were filled out by survey-takers. The data are their responses. These are the data to use to predict movie attributes.

- What is this movie's name? (Use exact spelling)	
- What year was this movie released?	
- How long is this movie?	
- What is the plot of this movie? (5 sentences)	
- Had you watched this movie previously, or was this your first time?	
- What were the characteristics of the protagonist?	
- What were the characteristics of the antagonist? 	
- How invested did you feel in the drama?	
- How much did the main characters change over the course of the story?	
- To what extent did the characters feel real and complex?	
- How invested did you feel in the characters?	
- How many narrators/perspectives were there? (Integer answer)	
- How fast-paced was this movie overall?	
- How fast-paced was the beginning of the movie?	
- How fast-paced was the middle of the movie?	
- How fast-paced was the end of the movie?	
- Did the movie feature a substantial turning point in the plot?	
- Did the movie feature a plot twist?	
- Was there a noticeable "sag" in plot tension at any of the following points of the movie? (please check timestamps to be as accurate as possible about the % in)	
- What were the qualities of the beginning? Check all that apply	
- What were the qualities of the ending? Check all that apply	
- Which of the following describes the movie's climax? Check all that apply	
- Was the movie plot-driven or character-driven?	
- How immersive did the world of the movie feel?	
- How important was the immersiveness of the world for this movie?	Did the world of the movie feel real?	
- How engaging was the dialogue?	
- What characteristics apply to this movie's dialogue?	
- By the end of the movie, how emotionally affected were you?	
- By the end of the movie, how intellectually engaged did you feel?	
- Check all attributes that apply to this movie:	
- Which of the following would you characterize as among the film's intended artistic objectives?	
- Which of the following objectives did the film succeed at? (Only potentially check boxes for those that were checked above, if any)	
- What were the movie's (up to three) main themes? (one or two word phrases each, separated by semicolons)	
- How clear and consistent were the themes of this movie?	
- What were the movie's (up to three) main tropes? (e.g. "enemies to lovers"; also separated by semicolons)	
- How much did you enjoy the movie's score? (that is, the music/sound)	
- How important was the movie's score to your emotional experience of the narrative?	
- How much did you enjoy this movie?	
- How strong was the acting?	
- How strong was the directing?	
- How strong was the cinematography?	
- What's the most important attribute of this movie that this survey missed?	

DATA ATTRIBUTES: All the following variables describe other attributes of the movie.

- moviename -- Name of the movie
- year -- Year of movie's release	
- src -- Link to IMDB page for this movie	
- title -- Name of the movie
- genres	-- Genres of the movie, in list form
- stars -- Notable stars in the movie
- Scores of different attributes that determine maturity rating:
 - violencegore_score	
 - alcohol_score	
 - frightening_score	
 - profanity_score	
 - sexnude_score	
- runtime -- Runtime of the movie	
- runtime_log -- log of above
- budget -- Budget of the movie
- budget_log -- log of above 
- user_id -- Unique ID of the survey taker
- rating -- Maturity rating of the movie
- release_type -- Whether the movie received wide or limited release
- num_reviews_written -- Number of IMDB reviews written for movie

OUTCOMES: All of the following variables describe the outcomes of the movie that we'd like you to predict, with * denoting those that we'd like you to focus on for this task, and *** denoting our favorite.
- opening_weekend_box_office	
- opening_weekend_box_office_log	
- * gross_usa *
- * gross_usa_log *
- cumulative_worldwide_gross	
- cumulative_worldwide_gross_log	
- * metascore *
- number_of_nominations	
- number_of_wins		
- *** imdb_rating_updated ***
