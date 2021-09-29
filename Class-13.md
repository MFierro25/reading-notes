### THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

Cookies downsides 
- slows down website because it transmits same data over and over again
- sends data unencrypted
- are limited to 4kb of data

> before html5 userdata was used to save up to 64kb of data. Adobe came up with a feature to hold 100kb of data.
> in 2007 Google put out a plugin to do store data as well. at the end of the day there was too many different interfaces, different limitations and different experiences.

#### HTML 5 storage
(also known as local storage or DOM storage)

- key value and pairs are saved locally
- data is never transmitted to web server
- implemented natively so no third party plug in is required
- this checks if browser supports this 
``` if (Modernizr.localstorage) {
  // window.localStorage is available!
} else {
  // no native support for HTML5 storage :(
  // maybe try dojox.storage or a third-party solution
}
```
#### tracking changes 
- setItem(), removeItem(), or clear() 
- key (string)
- oldvalue (any)
- newvalue (any)
- url (string) 

#### Summary of how it works
Before if you close the browser while you are making changes or iputs you’ll lose your progress. But with HTML5 Storage, we can save the progress locally.When A browser supports HTML5 Storage, the page should magically remember your exact position including the number of moves you’ve made, the position of each of the pieces on the board, and even whether a particular piece is selected.
