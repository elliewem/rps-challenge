# RPS Challenge

Approach
-------
This time round I gave myself way more time to plan and diagram. It turns out it's super helpful (who knew, right?). I diagrammed, storyboarded, and designed interfaces which ended up making the whole process a lot smoother than last weekend ヽ༼ಠل͜ಠ༽ﾉ

![evidence of diagramming](https://github.com/elliewem/rps-challenge/blob/master/IMG_0382.PNG)

My main direction in this task was to have three classes; the computer, the player, and the game. The player would be responsible for maintaining their 'wins' and name, the computer would be responsible for their weapon choice and 'wins', and the game essentially did everything else. In hindsight, it would have been a good move to pass some of the actual game logic into a separate class as I found that it got a little messy juggling all the private methods.

How to use
-------
* Clone this repo
* Direct your terminal to the repo and:

```
$ git clone https://github.com/elliewem/rps-challenge.git
$ cd rps-challenge
$ bundle
$ rackup
```
* Direct your browser to the server
* Enjoy

In case you don't want to do that
-------
Here are two videos showing a win and a lose. (My laptop really hated screen recording and running the programme at the same time, sorry for the lag).

<a href="https://youtu.be/tRXEF5BzXAw
" target="_blank"><img src="http://img.youtube.com/vi/tRXEF5BzXAw/0.jpg"
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

<a href="https://youtu.be/J36VoLHBmxE
" target="_blank"><img src="http://img.youtube.com/vi/J36VoLHBmxE/0.jpg"
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

