- š Hi, Iām @adirhbj
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
adirhbj/adirhbj is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
fetch ( "https://api.spotify.com/v1/audio-analysis/6EJiVf7U0p1BBfs0qqeb1f" ,  { 
  method :  "GET" , 
  headers :  { https://artists.spotify.com/c/artist/4kj2gMXV13rrCyDkmjuuuL/profile/overview
    Authorization :  ` Bearer ${ userAccessToken } `
   } 
} ) 
. kemudian ( respon  => respon . json ( ) ) 
. maka ( ( { ketukan } )  =>  { 
  ketukan . forEach ( (mengalahkan , indeks )  =>  { 
    konsol . log ( ` Beat ${ index } dimulai dari ${ beat . start } ` ) ; 
{"https://api.spotify.com/v1/artists/4kj2gMXV13rrCyDkmjuuuL"
"Accept: application/json"
"Content-Type: application/json"
"Authorization: Bearer BQBYkFUy0rFYFTodDCMx2uiFDfo7F0XRQuBs8s6xrfsaUJC2-DZWJSRYvS6TyY9PpB7MtcKzcWzri3fNvwK_2w-xWjuVqfC42Bi5jpjAweyr2YaoooPhr3JesJCM9O7qhgVKcbanyF_SlZRV7PNpj9cBDkE_5IJkC4IS5yk" { "external_urls": { "spotify": "https://open.spotify.com/artist/4kj2gMXV13rrCyDkmjuuuL"}, 
"followers": { "href": null, "total": 13 }, "genres": [], "href": "https://api.spotify.com/v1/artists/4kj2gMXV13rrCyDkmjuuuL", 
"id": "4kj2gMXV13rrCyDkmjuuuL", "images": [ { "height": 640, "url": "https://i.scdn.co/image/ab6761610000e5eb7095fa3b883fa42598e39de9", 
"width": 640 }, { "height": 320, "url":"https://i.scdn.co/image/ab676161000051747095fa3b883fa42598e39de9", "width": 320 }, { "height": 160, "url": "https://i.scdn.co/image/ab6761610000f1787095fa3b883fa42598e39de9", "width": 160 } ], "name": "Adi RHBJ", "popularity": 10, "type": "artist", "uri": "spotify:artist:4kj2gMXV13rrCyDkmjuuuL" }}
} )
