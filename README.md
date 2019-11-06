# [Exam Timer][url]

## [https://exam-timer.com][url]

Puts a timer on top of a Google Doc. That's all. :smile:

Shamelessly stolen from, most recently, [@CS61C](/cs61c). However, this is the product of many TAs.

## Directions
* Go to exam-timer.com
* Put in a Google Doc URL and a time
* Share the URL with your team

### Tips
* It's easiest if the Doc is public, but it doesn't need to be.
* Keep the doc in the "edit" mode so it receives updates
* The time is draggable.



### Code & Features
* Two very simple html files, index, and timer/index.
* All functionality is controlled via query parameters.
* We only support modern browsers. `let` is aswesome, and `var` is very passé.

#### Nice to Haves (Maybe?)
* A bigger timer option
* Optionally Hide seconds on time
* A refresh button?
    * This could let you use a doc in "viewing" mode.
    * Maintain the timer state by dynamically calcuating RTT
        * This is stupid, but sounds fun.
    * Smarter way to maintain state: Store start time in local storage.

[url]: https://exam-timer.com
