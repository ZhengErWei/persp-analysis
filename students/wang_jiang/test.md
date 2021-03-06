Introduction and Research Question Ten years from now, almost nobody
believed the video game industry would develop so rapidly. Other than
enjoying a peaceful night playing video games, people can get into a
live channel in Twitch, appreciating the amazing skills of hardcore
players, or go to a League of Legends tournament, feeling the anxiety
and excitement of Esports matches. Indeed, there are far more ways to
engage players to games, and compared with the past, game communities
tend to be much larger and more vital when each player can submit and
discuss champion builds and game guides via the Internet. In this paper,
I am interested in the evolution of social networks of video games
communities. To understand system evolution as well as interpersonal
interactions, I decide to conduct this research at both macro and micro
level. At the macro level, I will focus on the vitality of a specific
gaming community. Although there are a lot of reasons that affect
community vitality, I focus on the effects of game updates. There is a
paradox of game developing. Without updates, players may get bored of
the current meta and leaves the game, and updates with new contents will
bring people back. However, updates may also drive people away. One
prominent example is nerfing. Players in games, such as League of
Legends, may leave the game if their favorite champions get nerfed.
Therefore, here comes the two competing claims: Game updates may
increase or decrease community vitality. Here I put ‘increase’ in my
hypothesis because from my own experience of playing World of Warcraft,
a good update will bring old players back. H1: Game updates will
increase community vitality. At the micro level, I am interested in how
a particular streamer becomes viral on the Internet. A well-known
example would be dasima, a streamer of League of Legends in Douyu.tv in
China, who suddenly became viral after a couple of appearances in
‘League of Legends funny moments’. His humorous style of bragging won
him tens of thousands of followers. Speaking of dasima’s success,
‘League of Legends funny moments’ must have played an important role.
From my own experience, most people, either around me, or on the
Internet, first knew dasima on that TV show. Note that ‘funny moments’
series have over a million clicks per video, I believe it is their
special position in the game community network that makes damisa viral.
H2: Continuous interaction with a central node will bring an outsider
(or a marginal position) to a central position in a social network.
Research Design Data from Weibo.com will be used in this study. Weibo is
the Chinese version of twitter, except that people can respond a post.
This yields great convenience when I record the interaction between two
nodes. If B responds to A’s post, then I can locate the anchor in A’s
post that directs to B’s homepage, including a couple of B’s posts.
Afterwards I can locate the anchor in B’s post and record people who
responds to B. It could be A or someone else. The strength of
interaction between two nodes is calculated by the number of anchors
that takes to B from A (or A from B)1. Dr. Charles Severance from the
University of Michigan introduced this method in his Coursera
Specialization “Python for everybody”2. Beautiful soup and sqlite3
package is applied in this method. I believe only some adjustment is
needed to proceed the research. Note here the homepage (post) we start
is very important. Luckily, almost all well-known online games have
their official websites, and I will choose them as the start website.
Counting things is applied in this study, and the strength of social
ties is calculated by the number of ‘responds’ between two nodes. To
measure vitality of the game community, I simply add all the number of
‘responds’. Here, the two hypotheses in section can be operated as: H1:
Game updates will increase the total number of posts in the community
(that can be traced by to the official Weibo account). H2: A significant
number of responds to/from an account with at least 10k followers will
increase an account’s followers significantly. Advantages and Weaknesses
Data from Weibo is big, which enables me to get an accurate estimate of
the ‘hotness’ of a game. Besides that, it also allows me to analyze the
player community in different regions and age groups. Since the overall
dataset is quite large, I will have enough observations to estimate an
attribute of a subgroup. However, the always-on makes Weibo data more
valuable. It enables me to understand how unexpected events affect the
vitality of the game community. For example, sometimes developers of
League of Legends would release a hotfix that immediately nerf a
champion that they think is overpowered. Weibo data would enable me to
understand how players feel about the nerf before (is the champion
overpowered?), during (is the nerf fair?), and after (is the champion
balanced?) the hotfix. Certainly, developers can discuss with players on
the forum, but without the analysis of large dataset, they would not get
the instant feedback of larger population. I believe the always-on
attribute of Weibo data offers is able to extend my research. For
example, how the release of other ‘hit’ games affect the vitality of a
game community? During 2016 and 2017, Overwatch by Blizzard and
PlayerUnknown’s Battlefield by Steam were released and posed a challenge
to Riot’s League of Legends. I remembered a lot of Lol players switch to
these two games when they were released. Even though Overwatch’s hit was
foreseeable, Battlefield’s success was unexpected. It is interesting to
see how to system structure of Lol changed as people switched to other
games, and with our large dataset, it is feasible to check which
subgroup (grouped by gender/age/etc.) are more likely to leave the
community. However, this is also a weakness of this study. Certainly,
there are certain visible variables that can help explain the change of
social networks, however, some variables are invisible, due to the
incompleteness of the data. For example, World of Warcraft has continued
to lose its players since 2010. Game updates cannot explain the trend
since Blizzard is continuing to offer new content. Due to the
incompleteness of our data, it is hard to come up with a satisfactory
answer. Perhaps people get tired of MMORPG. Perhaps Wow fails to recruit
new players, as old players are leaving the game. In either case, our
dataset fails to give out an satisfactory explanation. A key concern
using Weibo data is that it is highly non-representative. The population
may not be representative: Are Weibo users responding to Lol official
account representative of all the Lol players? Definitely not, as a
significant number of plays are too young to use Weibo. Also, I would
feel some people may prefer other places to discuss games, such as
official game forums, Tieba, and NGA.cn. Especially for Wow, most people
tend to discuss gameplays and strategies on NGA.cn. I would feel analyze
the data from Weibo only will lose all the valuable information in these
websites. Besides that, drift is also an important problem in this
study. The first problem would be population drift. The population of
Weibo users in 2010 and 2017 are definitely different. Some people may
get married and have their children during the seven years. They will
eventually spend less time on Weibo. Other people grow up, have their
first smartphone, and start to use Weibo. Also, difference in population
will lead to difference in behaviors. From my observation, users in 2010
will respond more to game updates and new contents, and users now tend
to respond to match results and streamer’s lotteries. Finally, I believe
the Weibo system has changed quite a lot from 2010. People tend to write
their own blogs in the past, while today they are more willing to
forward and respond other’s posts. This is also linked to
algorithmically confoundedness. Weibo introduced its leveling and daily
quest system after 2010. Therefore, it is not surprised to see that
people respond to others’ posts more on average after that time. It
should be cautious because more responds do not necessarily mean greater
‘hotness’. Finally, online data from sources like Weibo is very likely
to be dirty. A key problem is that when calculating responds, I should
be able to differentiate regular responds from spams. At Weibo’s early
stage, to increase popularity, Sina intentionally lowered the bar of
registration, and any people with an email account can obtain a Weibo
account from Sina. Some people registered hundreds of accounts and sent
spams to other people. A great challenge to this study, similar to the
911 research, is to separate valuable data from noises.
