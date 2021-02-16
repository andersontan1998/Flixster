# Flix
Flix is an app that allows users to browse movies from [The Movie Database API](http://docs.themoviedb.apiary.io/#).

📝 `NOTE - PASTE PART 2 SNIPPET HERE:` Paste the README template for part 2 of this assignment here at the top. This will show a history of your development process, which users stories you completed and how your app looked and functioned at each step.

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