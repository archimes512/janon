# janon
anonymous moderation for the 'craft

Works with EssentialsX Vanish and LuckPerms to enforce anonymous server moderation and prevent players from knowing who server moderators are, while logging vanish activity. Should prevent moderation abuse and conspiracies by players.

This plugin is designed to work with a rule wherein moderators are not allowed to reveal themselves under the threat of being fired.

Name comes from pejorative imageboard slang "Janny", used to refer to moderators, and an abbreviation of "Anonymous"
## why do this instead of luckperms contexts
The goal of this project is to construct an "iron curtain" between the two modes of interacting with the game in a single package.

We classify being in Vanish as a separate mode of play, with no permission overlap with ordinary survival mode. Moderators in vanish mode are not intended to have any abilities survival mode provides, restricting their functionality solely to moderation actions; as such, they can travel to anywhere in the world when vanished, but they can't use this to rapidly travel as a player. Access to moderation should be entirely concealed to a moderator acting as a player, so they could present a point-of-view without being revealed to be a moderator, thus leaving the decision of whether or not to break the rule entirely up to their own volition, reducing accidents. This mode of play would also record all moderation activity, yet no acts of ordinary gameplay, drastically easing attempts to discover abuse.

Overall, a server using this plugin would require far less configuration than a server using an entire suite of plugins for the same function.

This is my first plugin; as such, (you)r contribution and criticism would be very much appreciated!
## features 
- [ ] prevent moderators from moderating unless they are in vanish
- [ ] prevent moderators in vanish from playing the game as normal
  - [ ] save moderator positions before entry into vanish
  - [ ] ensure they are, for all intents and purposes, treated as offline when in vanish 
  - [ ] alternative means of interacting with the world entirely undetectable to players
- [ ] separately log commands submitted through vanish and related playernames
- [ ] configuration options based on demands
