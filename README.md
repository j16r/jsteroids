# jsteroids

Play it live [here](http://jsteroids.heroku.com/).

## Background
While at Railscamp #8, I decided it was about time I learnt a bit of basic javascript with some jQuery and Raphael. So I ended up making a very basic asteroids simulation in a couple of hours.

### Controls
Controls are standard wasd or arrow keys for movement and either q or spacebar to fire missiles.

### Bugs
* Wrapping is a simple repositioning of the path so doesn't look very good
* Explosions don't get cleaned up sometimes, i suspect this is because i'm modifying a collection inside an iterator.
