# A Movies/TV shows Listing Page

Create a web page that helps users discover movies and TV shows easily. Implement the following features:
  1. List
   - 20mostpopularmovies/TVshows.
   - 20mosttrendingmovies/TVshows.
   - 20 newest movies/TV shows.
   - 20highestratedmovies/TVshows.
  2. Allowfilteringby
  - Typeofmedia-movies/TVshows.
  - Genre.
  - Year (from and to).
  - Rating.
  3. Allow searching by movie/TVshowtitle.


API
Explore the API documentation provided here as required:
https://developers.themoviedb.org/3/getting-started/introduction
Use the following key for making API calls:
**3a94078fb34b772a31d9a1348035bed7**
 
Here’s a sample request/response to start with:
Request:
https://api.themoviedb.org/3/discover/movie?api_key=3a94078fb34b772a31d9a1348035bed7&language=en-US&sort _by=popularity.desc&include_adult=false&include_video=false&page=1


Response (truncated for brevity):
```
{
​"page"​: ​1​, ​"total_results"​: ​10000​, ​"total_pages"​: ​500​, ​"results"​: [
{
​"popularity"​: ​568.124​,
​"vote_count"​: ​165​,
​"video"​: ​false​,
​"poster_path"​: ​"/zfE0R94v1E8cuKAerbskfD3VfUt.jpg"​, ​"id"​: ​474350​,
​"adult"​: ​false​,
​"backdrop_path"​: ​"/4W0FnjSGn4x0mKZlBRx8OjFxQUM.jpg"​, ​"original_language"​: ​"en"​,
​"original_title"​: ​"It Chapter Two"​,
​"genre_ids"​: [
​27 ],
​"title"​: ​"It Chapter Two"​,
​"vote_average"​: ​7.3​,
​"overview"​: ​"27 years after overcoming the malevolent supernatural entity
Pennywise, the former members of the Losers' Club, who have grown up and moved away from Derry, are brought back together by a devastating phone call."​,
​"release_date"​: ​"2019-09-06" },
... ]
}
```
Note: ​This is a public API and has a limit of 40 requests every 10 seconds.

Design/UX :-

![Design/UX](https://miro.medium.com/max/4632/1*kduoGmbaTLTK-gza24GQxA.png)

Use the following as a reference:
Instructions
  - Use a framework of your choice or vanilla JS.
  - Use CSS, LESS or SASS for styles.
  - Include instructions on how to run your app.

Judging Criteria
- Functionality.
- Progress made in given time.
- How close is it to the provided design/UX?
- Code structuring and modularity.
- Extra points for typescript!

### Time limit - 2 days


[One possible implementation](https://github.com/lapstjup/discover-tmdb)

