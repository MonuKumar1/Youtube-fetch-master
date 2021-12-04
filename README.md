# Youtube_Fetch_API
 An API to fetch latest videos sorted in reverse chronological order of their publishing date-time from YouTube for a given tag/search query in a paginated response.
# Basic Requirements:
- Server should call the YouTube API continuously in background (async) with some interval (say 10 seconds) for fetching the latest videos for a predefined search query and should store the data of videos (specifically these fields - Video title, description, publishing datetime, thumbnails URLs and any other fields you require) in a database with proper indexes.
- A GET API which returns the stored video data in a paginated response sorted in descending order of published datetime.
- A basic search API to search the stored videos using their title and description.

# To Run the project:
 Following steps has to be taken before that we have to download ".env" file which contains private keys:<br>
-step 1 : creating virtual environment by command "python3 -m venv venv"<br>
-step 2 : Entering to virual environment  "venv\Scipts\activate<br>
-step 3 : Download required libraries by "pip install requirements.txt"<br>
-step 4 : final command "run"
# Quering:
<a href="url"><img src="https://github.com/MonuKumar1/Youtube_Database_Fetch/blob/master/images/query1.png" ></a>
# Searching
<a href="url"><img src="https://github.com/MonuKumar1/Youtube_Database_Fetch/blob/master/images/search.png" ></a>

 

   

   
   
