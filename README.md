# brainfeed

Feature: Extract Links from a Twitter Feed

Given my Twitter handle @yeehaa
And no further arguments
Then I will receive the latest 10 urls that I posted

Given my Twitter handle @yeehaa
and the argument {:history 5}
Then I will receive the latest 5 urls that I posted

Given my Twitter handle @yeehaa
and the argument {:history :all}
Then I will receive all urls that I ever posted
