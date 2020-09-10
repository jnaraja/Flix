# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF

<img src="https://media4.giphy.com/media/Lo0keZLJZFvaGCOEQC/giphy.gif" width=250><br>

### Notes
Styling the the superhero scene was a challenge I faced. It currently looks the best on an iPhone 11.

---

## Flix Part 1

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [x] (2pt) User can view the app on various device sizes and orientations.
- [x] (1pt) Run your app on a real device.

<img src="https://media1.giphy.com/media/hoxQ5usLlLVt0gK7zi/giphy.gif" width=250><br>

<img src="https://media1.giphy.com/media/JNOaKSOdnQAP7IN1Ev/giphy.gif" width=250><br>

### Notes
I struggled with displaying the labels at first. After reviewing the code for about 15 minutes, I realized that I was missing these 2 lines of code:

tableView.dataSource = self
tableView.delegate = self

After including those, I was able to get it to display successfully.
