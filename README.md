# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

📝 `NOTE - PASTE PART 2 SNIPPET HERE:` Paste the README template for part 2 of this assignment here at the top. This will show a history of your development process, which users stories you completed and how your app looked and functioned at each step.

---

## Flix Part 1

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

<img src="https://media1.giphy.com/media/hoxQ5usLlLVt0gK7zi/giphy.gif" width=250><br>

### Notes
I struggled with displaying the labels at first. After reviewing the code for about 15 minutes, I realized that I was missing these 2 lines of code:

tableView.dataSource = self
tableView.delegate = self

After including those, I was able to get it to display successfully.
