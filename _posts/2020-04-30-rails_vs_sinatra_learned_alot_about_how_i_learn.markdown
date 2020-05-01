---
layout: post
title:      "Rails vs Sinatra. Learned alot about how I learn  "
date:       2020-05-01 00:53:06 +0000
permalink:  rails_vs_sinatra_learned_alot_about_how_i_learn
---

First off, be humble when learning something new because overconfidence may lead to some very surprising reality checks!
Sinatra to me was really simple, I never really felt stuck or lagged behind any of the concepts that we had learned, and I implemented an API when I didn't have to. Bragging aside, I thought rails was going to be even more nice to me and I was feeling like this prior to the project

<iframe src="https://giphy.com/embed/W9lzJDwciz6bS" width="480" height="411" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

Instead, what happened was I got too comfortable and alot of the things that are "rails magic" that are actually really helpful ended up leaving me like 
<iframe src="https://gifer.com/embed/BEAI" width=480 height=270.000 frameBorder="0" allowFullScreen></iframe>

RESTful routes are nice, but understanding when you want a resource and specific ones are going to be very helpful when it comes to your paths. Alot of times, you might be better off defining your own for special cases. hint: `rails routes` is your friend for this!

With ActiveRecord, I learned alot by using  `binding.pry` and `rails console` to play around with alot of the models and relationships I was testing, but you can also see the SQL behind the "magic." It was especially helpful for the scope method and understanding the relationships between the models I have.

Validations I kept having to go back and forward to as I was going along. I think some of these can be defined earlier and some are better off being added later. 

And finally, PLAN AHEAD! I wish I had taken the time to draw out a diagram or even write out a plan earlier. I would've been much, much more productive had I not had to keep running down the plan in my head which was being influenced or changing as I was progressing in the code. Before any code in the future, I will always make sure to plan ahead...way ahead! 
