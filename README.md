# JavaScript: Objects and Arrays Quiz

???

# JavaScript: Objects and Arrays Quiz

?: Given a number of elements that need to stay in order, would you use an Object or an Array?

( ) Object
(x) Array

?: Given a collection of artists and lists of their songs, would you store the artist-song-list pairs in an Object or an Array?

(x) Object
( ) Array

?: True or false: All the elements in an array must be of the same type.

( ) True
(x) False

?: True or false: All keys in an object are strings.

(x) True
( ) False

?: What happens to the array in the following code snippet?

``` javascript
const dogs = ["Fido", "Odie", "Oscar"]

dogs.length

dogs.length = 1
```

( ) Nothing
( ) The array becomes just `["Oscar"]`
(x) The array becomes just `["Fido"]`
( ) The array becomes just `["Odie", "Oscar"]`

?: What are the keys in the object after running the code below?

``` javascript
const artistsAndSongs = {
  'Prince': ["Purple Rain", "When Doves Cry"],
  'The Beatles': ["Revolution", "Norwegian Wood"],
  'Joni Mitchell': ["A Case of You", "Sunny Sunday"],
  'Justin Bieber': ["Baby"]
}

artistsAndSongs['Daft Punk'] = ["Harder, Better, Faster, Stronger"]

delete artistsAndSongs["Justin Bieber"]
```

( ) `['Prince', 'The Beatles', 'Joni Mitchell', 'Justin Bieber', 'Daft Punk']`
( ) `['Prince', 'The Beatles', 'Joni Mitchell', 'Justin Bieber']`
( ) `['Prince', 'The Beatles', 'Joni Mitchell']`
(x) `['Prince', 'The Beatles', 'Joni Mitchell', 'Daft Punk']`

?: If we run `artistsAndSongs['Daft Punk'].push("Around the World")` after running the code below, what is the value of the object?

``` javascript
const artistsAndSongs = {
  'Prince': ["Purple Rain", "When Doves Cry"],
  'The Beatles': ["Revolution", "Norwegian Wood"],
  'Joni Mitchell': ["A Case of You", "Sunny Sunday"],
  'Justin Bieber': ["Baby"]
}

artistsAndSongs['Daft Punk'] = ["Harder, Better, Faster, Stronger"]

delete artistsAndSongs["Justin Bieber"]
```

( )
``` javascript
const artistsAndSongs = {
  'Prince': ["Purple Rain", "When Doves Cry"],
  'The Beatles': ["Revolution", "Norwegian Wood"],
  'Joni Mitchell': ["A Case of You", "Sunny Sunday"],
  'Daft Punk': ["Harder, Better, Faster, Stronger"]
}
```

(x)
``` javascript
const artistsAndSongs = {
  'Prince': ["Purple Rain", "When Doves Cry"],
  'The Beatles': ["Revolution", "Norwegian Wood"],
  'Joni Mitchell': ["A Case of You", "Sunny Sunday"],
  'Daft Punk': ["Harder, Better, Faster, Stronger", "Around the World"]
}
```

( )
``` javascript
const artistsAndSongs = {
  'Prince': ["Purple Rain", "When Doves Cry"],
  'The Beatles': ["Revolution", "Norwegian Wood"],
  'Joni Mitchell': ["A Case of You", "Sunny Sunday"],
  'Daft Punk': ["Around the World"]
}
```

( )
``` javascript
const artistsAndSongs = {
  'Prince': ["Purple Rain", "When Doves Cry"],
  'The Beatles': ["Revolution", "Norwegian Wood"],
  'Joni Mitchell': ["A Case of You", "Sunny Sunday"]
}
```

?: What is the result of the following code in a browser that supports the spread operator?

``` javascript
const oneTwoThree = [1, 2, 3]
const sevenEightNine = [7, 8, 9]

[4, 5, 6, ...oneTwoThree, ...sevenEightNine]
```

( ) `[4, 5, 6, 7, 8, 9, 1, 2, 3]`
(x) `[4, 5, 6, 1, 2, 3, 7, 8, 9]`
( ) `[1, 2, 3, 4, 5, 6, 7, 8, 9]`
( ) `Error`

?: Given the array `const letters = ["alpha", "gamma", "delta"]`, which operation(s) _return_ the array `["alpha", "beta", "gamma", "delta"]`?

( ) `letters.push("beta")`
( ) `letters.unshift('beta')`
(x) `[...letters.slice(0, 1), 'beta', ...letters.slice(1)]`
( ) `letters.splice(1, 1, 'beta')`
( ) `letters.splice(1, 0, 'beta')`

???

<p class='util--hide'>View <a href='https://learn.co/lessons/javascript-objects-and-arrays-quiz'>Javascript Objects And Arrays Quiz</a> on Learn.co and start learning to code for free.</p>
