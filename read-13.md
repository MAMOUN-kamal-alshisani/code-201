# ~~Read:13 - Local Storage~~

__-what is local storage: Simply put, it’s a way for web pages to store named key/value pairs locally, within the client web browser.
Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you.
Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually).
Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.-__

***HTML Storage” is a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons.
Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.*** 

## TRACKING CHANGES TO THE HTML5 STORAGE AREA :
***keep track programmatically of when the storage area changes, you can trap the storage event.
The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something. 
For example, if you set an item to its existing value or call clear() when there are no named keys, the storage event will not fire, because nothing actually changed in the storage area.***

***the present condition of HTML5 Storage is surprisingly rosy. A new API has been standardize***d and implemented across all major browsers, platforms, and devices.
As a web developer, that’s just not something you see every day, is it? But there is more to life than “5 megabytes of named key/value pairs,”***

## LIMITATIONS IN CURRENT BROWSERS:
***5 megabytes” is how much storage space each origin gets by default. This is surprisingly consistent across browsers, although it is phrased as no more than a suggestion in the HTML5 Storage specification.
One thing to keep in mind is that you’re storing strings, not data in its original format. 
If you’re storing a lot of integers or floats, the difference in representation can really add up. Each digit in that float is being stored as a character,
not in the usual representation of a floating point number.***

## HTML5 STORAGE IN ACTION :
***if you close the browser window mid-game, you’ll lose your progress. But with HTML5 Storage, we can save the progress locally, within the browser itself. Here is a live demonstration. Make a few moves, then close the browser tab, then re-open it. If your browser supports HTML5 Storage, the demonstration page should magically remember your exact position within the game, including the number of moves you’ve made, the position of each of the pieces on the board, and even whether a particular piece is selected.***
