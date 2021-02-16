# Flix
Flix is an app that allows users to browse movies from [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)

- [x] (8pts) Expose details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.
- [x] (2pts) Allow video posts to be played in full-screen using the YouTubePlayerView.

#### BONUS

- [x] Implement a shared element transition when user clicks into the details of a movie (1 point).
- [x] Trailers for popular movies are played automatically when the movie is selected (1 point).
  - [x] When clicking on a popular movie (i.e. a movie voted for more than 5 stars) the video should be played immediately.
  - [x] Less popular videos rely on the detailed page should show an image preview that can initiate playing a YouTube video.
- [x] Add a play icon overlay to popular movies to indicate that the movie can be played (1 point).
- [ ] Apply data binding for views to help remove boilerplate code. (1 point)
- [x] Add rounded corners for the images using the Glide transformations. (1 point)

### App Walkthough GIF

Detail Activity - Portrait representation with transitions, play icons, rounded image corners, and popular movies automatically playing the trailer. 

<img src="https://github.com/andersontan1998/Flixster/blob/main/DetailActivity_Portrait.gif" width=250><br>

Detail Activity - Landscape representation with transitions, play icons, rounded image corners, and popular movies automatically playing the trailer. 

<img src="https://github.com/andersontan1998/Flixster/blob/main/DetailActivity_Landscape.gif" width=500><br>

### Notes

Flix application would automatically crash when I attempt to add additional details into the Detail Activity screen.

## Open-source libraries used
- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (10pts) User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.

#### BONUS
- [x] (2pts) Views should be responsive for both landscape/portrait mode.
   - [x] (1pt) In portrait mode, the poster image, title, and movie overview is shown.
   - [x] (1pt) In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.

- [x] (2pts) Display a nice default [placeholder graphic](https://guides.codepath.org/android/Displaying-Images-with-the-Glide-Library#advanced-usage) for each image during loading
- [x] (2pts) Improved the user interface by experimenting with styling and coloring.
- [ ] (2pts) For popular movies (i.e. a movie voted for more than 5 stars), the full backdrop image is displayed. Otherwise, a poster image, the movie title, and overview is listed. Use Heterogenous RecyclerViews and use different ViewHolder layout files for popular movies and less popular ones.

### App Walkthough GIF

**Portrait and Landscape Representation**

<img src="https://github.com/andersontan1998/Flixster/blob/main/Portrait.gif" width=250><br> 

<img src="https://github.com/andersontan1998/Flixster/blob/main/Landscape.gif" width=500><br>

**A white placeholder was used for each image during loading.** 

Because the app is ran on an emulator, the network speed of the emulator must be adjusted to test this feature.

<img src="https://github.com/andersontan1998/Flixster/blob/main/Placeholder.gif" width=250><br> 

**Placeholder during Portrait Mode**

<img src="https://github.com/andersontan1998/Flixster/blob/main/Portrait_Placeholder.gif" width=250><br> 

**Placeholder during Landscape Mode**

<img src="https://github.com/andersontan1998/Flixster/blob/main/Landscape_Placeholder.gif" width=500><br> 

### Notes
The most challenging part of the assignment was to adjust the network speed so that the placeholder would show during loading instead of the poster/backdrop image. The Flixs app would still load significantly fast even after such adjustments.

### Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Androids

## License

    Copyright [2021] [Anderson Tan]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
