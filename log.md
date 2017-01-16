# 100 Days Of Code - Log

### Day 6: January 16, 2017

**Today's Progress**: FINALLY got submitting multiple records on a single form working in Rails.

**Thoughts:** Note to self: slow down. Think. Try to UNDERSTAND! Not just copy/paste

**Link to work:**

### Day 5: January 15, 2017

**Today's Progress**: Good progress....getting close

**Thoughts:** Went back and read the various posts/tutorials again to try to get an understanding. SLOWED DOWN and tried to think through exactly what was happening in the code. This helps :)

**Link to work:** N/A

### Day 4: January 5, 2017

**Today's Progress**: Lots of time. Still not working

**Thoughts:** Went back to trying to submit multiple records on a single form....still can't get it to work. The 'name' attributes need to be unique....but then if I do that it messes up the params :()

**Link to work:**

### Day 3: January 4, 2017

**Today's Progress**: Felt better about my progess. A new day, a new perspective.

**Thoughts:** Trying to use the gon gem and code in the create action in the controller to
check when each form is saved, then notify the view that it can now submit the next form. Also thinking that overall the multiform on a single page is maybe not the best strategy.
Maybe I should switch to figuring out how to submit all in a single form.

**Link to work:** It's proprietary work that I can't share yet, but here's a link to the [tweet](https://twitter.com/cockerhamAndrew/status/816644858068746240).

### Day 2: January 3, 2017

**Today's Progress**: Same as yesterday....using jQuery to submit multiple forms on one page in Rails.

**Thoughts:** Tried multiple different things....not working yet. Got an InvalidAuthenticityToken error, so maybe submitting forms via xhr is not the best way to go. :( Also created an infinite Javascript loop (twice!), so that was fun. Force close Chrome tabs [like this](https://css-tricks.com/force-quit-tab-google-chrome/), although it worked for one tab, but not for another. Didn't get a full hour, but I'm counting it anyway ;)

**Link to work:** It's proprietary work that I can't share yet, but here's a link to the [tweet](https://twitter.com/cockerhamAndrew/status/816281346054258688).

### Day 1: January 2, 2017

**Today's Progress**: Worked on submitting multiple forms on a single Rails page.

**Thoughts:** This is a harder problem than it should be. I tried implementing solutions people suggested [here](http://vicfriedman.github.io/blog/2015/07/18/create-multiple-objects-from-single-form-in-rails/) and on Stack Overflow [here](http://stackoverflow.com/questions/972857/multiple-objects-in-a-rails-form) and [here](http://stackoverflow.com/questions/23791761/creating-multiple-objects-in-a-form-rails/23791879#23791879), but couldn't get them to work with what I was doing. I tried using the [Surveyor gem](https://github.com/NUBIC/surveyor), but its not in development anymore and I couldn't get it working with Rails 5. If someone knows of a good way to do this, please share! Finally made the most progress implementing my own solution of using Javascript to iterate through the forms, submitting each one. Made progress, but not working yet. I need to be coding more regularly, and need a better and deeper understanding of how Rails works, and then I think I could implement these things so much faster!

**Link to work:** It's proprietary work that I can't share yet, but here's a link to the [tweet](https://twitter.com/cockerhamAndrew/status/816115630365691904).
