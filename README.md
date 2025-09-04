## How Many
This analyses how many users on Rubygems and Youtube might be malicious, but analyses the difference between Ruby Gems and Github, then comparing Rubygems and Youtube.

## Version
3.2.3 or higher

## Install
No installation, this is plug and play if you use Linux.

~~~
ruby analyze.rb
~~~

## How To Use
Note that while it presents as Rubygames compared to Github, and Rubygems to Youtube, you can use it once and infer that as for Github.

This was created to work around the lack of features that were available to normal users about the exact nature of their traffic, as I had had breaches from parts of Asia and Eastern Europe, frequently in gaming communities, this enables me to avoid using Githubs metrics for finding out who might be malicious users.

~~~ruby
require_relative "HowMany/HowMany.rb"

evaluate_malicious_users(0.633333333, 0.366666667, 0.162461546, 128)

evaluate_yt_stats(:bequest_de_cendres, 166,
                  :mochitere,           87,
                  :electrorequiem,      17,
                  
                  0.54)
                  
difference_in_traffic(128, 166)
~~~
