# The subreddit r/AskAChinese isn't a chinese speaking QnA subreddit. It's a polarized subreddit that only wants to confirm their own bias.
---
### Just note that there will be alot of methodology, if you want to skip it feel free to or just scroll and read fast
---

> **METHODOLOGY: Vibe check** 
> The investigation of r/AskAChinese isn't about going inside the subreddit to check out. We will be using VADER (Valence Aware Dictionary and sEntiment Reasoner) and common tankie (extreme left) word terms they used such as, "western propaganda", "cia propaganda", etc. Organic communities typically display a "Normal Distribution" (Bell Curve) of sentiment—most people are neutral or mildly opinionated. An engineered or radicalized community will display a Bimodal Distribution (extreme positives and extreme negatives with no middle ground). The detection of a "Twin Peak" polarization confirmed the subreddit functions as an ideological battleground rather than a discussion forum.

> **Methodology: Network Topology & User Migration (The "Pipeline")**
> The task for network Topology & User Migration we constructed Bipartite Network Graph to overlap between r/AskAChinese with r/Sino, r/TankieTheDeprogram (originally there was a subreddit r/TheDeprogram but it was suspended)
> If the community were organic, user overlaps would be distributed randomly across various interests (gaming, hobbies, news). If the community is "captured," the connections will cluster around a single ideological hub. The visualization revealed a distinct "Funnel Structure," proving that the primary recruitment pipeline originates directly from r/Sino and its satellite communities.

> **Methodology: Circadian Rhythm Analysis (The "Geographic Test")**
> To verify that there are chinese users communicating in the subreddit, we would be using UTC+8 timezone
> Every human population follows a biological sleep cycle. If the users are in China, activity should drop to near-zero between 02:00 and 06:00 Beijing time.

> **METHODOLOGY: Latency & Queue Analysis (The "Racing" Metric)**
> We wrote a script to measure the Time-To-First-Comment on new threads. We specifically tracked how often a known "Tankie" affiliate was the first to respond within the first 4 minutes of a post's life.
>  In a natural community, the first responder is random. In a manipulated community, activists monitor the RSS feed to exploit "Anchoring Bias" commenting instantly to set the political frame before others arrive.

> Metodology: Agent Cross-Reference (The "Identity Match")**
> To prove that the "Radicals" in r/Sino and the "Moderators/Citizens" in r/AskAChinese are the same entities.
> We cross-referenced the "Racing" users from the radical subreddits against the comment history of the target subreddit.
> This establishes the "Bridge." It confirms that the hostility isn't coming from outside brigaders, but from the subreddit's own power users.

Thanks to:
Gemini
Grok
https://arctic-shift.photon-reddit.com/
https://ihsoyct.github.io/
https://github.com/ihsoyCT/ctarchive

----------------
Before we get started, I wanted to explain why in the world I would want to start doing this is because whenever you browse on r/AskChina and/or r/AskAChinese, you would be meeting chinese people there. In reality, this is probably what happens when tankie subreddit starts taking neutral conversation subreddit where chinese people can meet to make the subreddit themselves. Also, if you look at r/AskChina via stats in arctic shift's data (reddit archive):

![image alt](https://i.imgur.com/mCYUj0F.png)
You will be suspicious on the datagraph. AskChina the range is 10 years and for AskAChinese is 12 years and 1 month. If you look at mid end of 2024, you would see it began to spike even before 2025, I would assume because Trump became a winner during the election in 2024 + tiktok people moving to xiaohongshu.

---

![eETO78p](https://i.imgur.com/o81xdgQ.png)

Looking at this data that we have gotten from reddit api library, PRAW and the graph from matplotlib, you would see a curve in the negative while the curve on the positive are lower. Between -0.75 and -1.0, massive spike in comments with scores with heavy negatives. While +0.50 and +0.75, it shows heavy positive sentiment. The Center is very much steady. 

Overall, this looks high polarization. Since we used VADER (Valence Aware Dictionary and sEntiment Reasoner), if the tankie uses phrase like "The US is an evil imperialist empire destroying the world," its highly negative or the critic "The CCP is a genocidal regime oppressing its people" is also negative.

The conclusion, the fact that the "Tankie" subset is more negative (-0.062) than the overall average suggests that discussions involving these keywords trigger hostility.

![bbe54c29-80ee-44d1-bba1-7a022a643593](https://i.imgur.com/Vl0he9W.png)

> WARNING: MAKE SURE TO IGNORE AUTOMODERATOR. 
> Why?
> AutoModerator are used in every subreddit as the subreddit owner can configure what automod usually behaves. 

## A. The "Missionary" Profile (One_Long_996, Key-Needleworker-702)

These users are more active in r/AskAChinese than in the Tankie subs within this dataset.


We would point out that 2 reddit users "One_Long_996" and "Key-Needleworker-702" are more active in r/AskAChinese than in the tankie subs. 

| One_Long_996 | Key-Needleworker-702 
| -------- | -------- 
| 14 posts/comments in r/AskAChinese; 4 in Sino     | 12 in r/AskAChinese vs. 4 in Sino.

This behavioral pattern suggests these users treat the Tankie subs as a "home base" to consume content, but their primary action is exporting those views into r/AskAChinese. They are likely the ones driving the narratives you noticed in the sentiment analysis.

The tankie_subs column confirms the ideological source of the brigade.

``Sino``: The most frequent connector (appears in 6 out of the top user rows). This is the strongest indicator of CCP-aligned brigading. Sino is known for strict moderation and a hardline pro-China stance.

``TankieTheDeprogram`` & ``ShitLiberalsSay``: These indicate a more general Marxist-Leninist alignment, often hostile to Western narratives.

``Hasan_Piker``: This indicates a younger, "Streamer Left" demographic. While not always strictly "Tankie" in the historical sense, there is often overlap in anti-western sentiment.

Conclusion:
The sample size is small (12 users), but the impact is likely high.

In data science, we look for "Superusers."
Even though you only found a handful of overlapping users, One_Long_996 and Key-Needleworker-702 combined for 26 interactions. In a bigger subreddit like r/AskAChinese, 26 comments/posts from highly ideologically motivated users can easily shift the sentiment distribution (creating that "Negative Peak" we saw in your previous graph).

![bd04b455-a8bf-4970-baa6-11fa2c27ee3d](https://i.imgur.com/3S2JGWi.png)
![7f17a440-dd98-456c-994d-05fbc632cdf3](https://i.ibb.co/MyvVcKzd/upload-57ac713deef454d5036e4330fda68507.png))
![2604f519-599d-4e64-8b25-0e082f572a7f](https://hackmd.io/_uploads/HJzofo--bg.png)
![4fbfcfe0-de1f-4d32-a21c-54cead25a78a](https://hackmd.io/_uploads/ryUizsbb-l.png)
![98725ad4-bb40-4760-bde6-671227f6fdf3](https://hackmd.io/_uploads/SJx3MjbZWg.png)

> Note: Automoderator is the cause of the huge influx of comments. I forgot to clean the dataset but I would shave my colab and you can tweak it a little or more so we can gather more data about it.

1. The "Sino" Pipeline is Confirmed

Looking at the top-left screenshot:
r/Sino is the dominant source node. It has the highest "degree centrality" (most connections) among the subreddit nodes on the left.
r/TankieTheDeprogram and r/ShitLiberalsSay are secondary hubs.
Interpretation: This confirms that the "brigade" is not coming from general economic leftism (like r/antiwork), but specifically from the Authoritarian/Pro-CCP side of the spectrum (Sino and Deprogram).

2. User Analysis: The "Power Users" (Zoomed-In Image)

The center screenshot is the most revealing part of the dataset. It gives us the specific names and activity levels of the "Bridge" users.
A. The Primary Agitators:
One_Long_996 (14 comments): This is your most significant actor. They are highly active in the Tankie sphere and are the most active human bridge into r/AskAChinese.
Key-Needleworker-702 (12 comments): The second most active agent.
thinking_velasquez (8 comments): The third key agent.

3. The "Funnel" Structure

The full-view graph (bottom image) demonstrates a Funnel Topology.
Left Side (Wide): Users originate from a distributed network of ideological subs.
Right Side (Narrow): They converge on a single target (r/askachinese).
This is the visual definition of "Targeted Migration" (or brigading). If this were natural organic overlap, you would expect the lines to be messy and crisscrossed with other random subreddits. Instead, the lines are laser-focused from the "Red" ideological cluster directly to the target.

Now, if you are wondering how I got that evidence is that those two power users are really known to jump into the topic the first minute or two. Normally, if you post something, you would only get random users but in this subreddit, those two user heavily influence subreddit.

![image](https://hackmd.io/_uploads/HJgKSIsZZbe.png)
![image](https://hackmd.io/_uploads/rJwv8s-WZx.png)

Reference: This user posted this comment hours later heavily influence the comment to stop endorsing sepratism

![image](https://hackmd.io/_uploads/rye1Psb-We.png)

While others didn't really accept that, meaning this user doesn't want any opinions into the subreddit.

Some red comments, meaning its deleted:
![image](https://hackmd.io/_uploads/SJwrDjZZ-g.png)
![image](https://hackmd.io/_uploads/H1HUvibWZl.png)
![image](https://hackmd.io/_uploads/BkQDDsZWWe.png)
![image](https://hackmd.io/_uploads/SkE_vobZWx.png)
![image](https://hackmd.io/_uploads/HyEYDoZZbx.png)
![image](https://hackmd.io/_uploads/BJV5woZ--l.png)
![image](https://hackmd.io/_uploads/BJXjDsZbWe.png)
![image](https://hackmd.io/_uploads/Sk7hvj-Wbg.png)
![image](https://hackmd.io/_uploads/ByT3Pi--bg.png)
![image](https://hackmd.io/_uploads/HJopDiZZZl.png)
https://ihsoyct.github.io/index.html?comments=1p4mcc0&id=nqd2llt&backend=artic_shift

---

![ada63fa4-5368-4be1-b24c-e77e9c0bfa60](https://hackmd.io/_uploads/ryzGOj-bbe.png)

> Note: This again might be automoderator having alot of hairballs meaning alot of subreddit who have the bot might actually thing that it influence the data. Again, you can clean it out or tweak it using my colab.

1. The Strongest Signal: The "Sino" Axis

The most critical feature of this graph is the thick vertical line connecting r/askachinese directly to r/Sino.
What this means: In a projected graph, edge thickness (weight) represents the number of shared users. The fact that this line is the thickest and darkest connecting to your target subreddit confirms that r/Sino is the primary "parent" community for the users migrating to r/AskAChinese.
Secondary Links: There is also a notable connection to r/LateStageCapitalism, suggesting a secondary stream of users coming from general anti-capitalist subs, but the Sino connection is the dominant one.

2. The "Antiwork" Outlier

Look at r/antiwork floating alone in the bottom right corner.
Interpretation: The layout algorithm (likely Fruchterman-Reingold or similar spring-embedded layout) pushed it away because its connection strength to the main cluster is very weak.
Conclusion: This validates that the "Brigade" is not coming from the general dissatisfied labor movement. It is strictly coming from the Ideological/Political cluster on the left.

## Moderator influenced as user also went to r/Sino

![00359034-d36d-4d2d-a3bc-bd6a4fc21eca](https://hackmd.io/_uploads/Hk0gKsb-Wg.png)

If the Moderators of r/AskAChinese are also active users/mods in r/Sino, and the statistic in your image indicates that 99.0% of the time, the "First Comment" on a thread comes from this overlap group, the diagnosis shifts from "Brigading" to "Institutional Capture."

1. The "First Comment" Metric (99.0%) = Narrative Priming

In social media analysis, the "First Mover Advantage" is massive. The first comment on a thread sets the tone, frames the debate, and anchors the sentiment for all subsequent replies.
The Data Point: First comment by tankie-overlap user: 99.0%
Interpretation: This suggests that this specific group of users (or moderators) is camping the "New" queue.
The Strategy: As soon as a question is asked in r/AskAChinese, these users engage immediately. By commenting first, they ensure the "correct" (pro-CCP/Tankie) viewpoint is the first thing readers see.
The Result: This explains the Bimodal Sentiment we saw earlier. Anyone arriving later to offer a different viewpoint is fighting against the established frame, leading to conflict (negativity) rather than discussion.

If the users identified in your network graph (One_Long_996, Key-Needleworker-702, etc.) are actually Moderators, then r/AskAChinese is not being "raided." It is a Satellite Subreddit.

This explains the network topology perfectly:
Why the "Funnel" shape? Because the moderators act as a bridge, importing the culture of r/Sino directly into r/AskAChinese.
Why the "Sino" connection is strongest? Because the management team likely shares the same ideological ruleset as r/Sino.

---
![5c29f9fc-a5f0-46e8-a683-f0b1e01380ec](https://hackmd.io/_uploads/HJljFobZ-g.png)

1. The "Entrenchment" Signal (The Downward Trend)

The most important feature of this graph is the steady, smooth decline from 90% (2018) to ~45% (2025).
What a "Bot Raid" looks like: If r/AskAChinese were being attacked by fresh bot farms or 4chan trolls today, you would see a massive spike at the end of the graph (suddenly 80% of comments coming from accounts < 1 month old).
What this graph shows: The exact opposite. The active user base is getting older (in terms of Reddit account age).
Interpretation: The "Tankie" users controlling the subreddit (the "Old Guard") are not new, throwaway accounts. They are established, veteran Reddit users. They have been on the platform for years (likely actively posting in r/Sino and any tankie subreddit). They have "tenure."

2. The 2018 "Genesis" Peak

The "Takeover Peak" annotation at 2018 (90%) likely represents the founding or revitalization of the subreddit.
When a subreddit is small/new, everyone looks relatively new, or the initial seed users created accounts specifically to populate it.
This sets the baseline.

3. The "Closed Circle" Phenomenon (2023-2025)

Look at the flatline in the last two years (hovering around 50%).
The Metric: Only ~50% of the top commenters have accounts younger than 2 years.
The Inverse: This means 50% of the conversation is dominated by accounts older than 2 years.
Why this matters: In a healthy, growing "Ask" subreddit (like r/AskReddit or r/NoStupidQuestions), you expect a constant influx of new users asking questions, keeping the "Young Account" metric high.
The Diagnosis: The fact that the "Old Account" percentage is so high indicates that the subreddit is insular. New users aren't driving the conversation; the "Veterans" (the identified r/Sino brigade) are just talking to each other or policing the threads.

4. Integrating with Previous Findings

This graph validates the "Moderator/Superuser" theory from the previous steps.
Step 1 (Sentiment): The sub is hostile/polarized.
Step 2 (Network): The hostility comes from r/Sino users.
Step 3 (Timing): The r/Sino users comment first (99%).
Step 4 (Account Age): These users are not bots. They are dedicated, long-term ideological activists.

# posting times
---
![455baf6f-e45b-4eb1-a5dd-d352ec7e2c53](https://hackmd.io/_uploads/Bkzv5ibWWe.png)

1. The "Vampire" Peak (02:00 – 04:00 Beijing Time)

If these were local Chinese users: This is deep sleep. Activity should be near zero.
The Reality: This is the busiest time for the subreddit.
The Translation:
02:00 Beijing = 13:00 (1 PM) New York (EST)
02:00 Beijing = 10:00 (10 AM) Los Angeles (PST)
02:00 Beijing = 18:00 (6 PM) London (GMT)

Conclusion: The peak activity aligns perfectly with Lunchtime/Afternoon in North America and Evening in Europe.

2. The "Missing" Evening Peak (19:00 – 22:00 Beijing Time)

Look at the dip on the right side of the graph (hours 19-22).
Organic Behavior: In almost every country, social media usage peaks in the evening (after work/dinner), roughly 7 PM to 10 PM.
The Anomaly: In your graph, this timeframe is a low point.
The Translation:
20:00 (8 PM) Beijing = 07:00 (7 AM) New York.
Why it dips: The "Chinese" users aren't posting at 8 PM Beijing time because they are Americans who are asleep or commuting to work.

3. The Secondary Peak (13:00 Beijing Time)

There is a smaller spike around 1:00 PM Beijing time.
Translation: This is Midnight (00:00) in New York or 9:00 PM in California.
This represents the "Night Owl" Americans or the West Coast evening users.

![e504331e-5d3e-4476-9c91-ae8b8220413b](https://hackmd.io/_uploads/Hy0C9j-Z-e.png)

1. The "3 AM" Spike (The Afternoon Lunch Break)

Look closely at the bar corresponding to 03:00 (3 AM) inside the blue zone.
The Data: There is a distinct spike in activity at 3 AM, significantly higher than at 1 AM or 4 AM.
Biological Reality: In a purely local population, 3 AM is the deepest phase of the sleep cycle. Activity should be effectively zero (or at its absolute minimum).
The Translation:
03:00 Beijing = 15:00 (3 PM) New York (EST).
03:00 Beijing = 12:00 (Noon) Los Angeles (PST).
03:00 Beijing = 20:00 (8 PM) London (GMT).
Interpretation: This spike is perfectly timed with the American lunch break/afternoon and the British prime time. It is a clear signal of Western activity leaking into the dataset.

2. The High "Noise Floor" During Sleep

In a geographically localized subreddit (e.g., a city subreddit like r/London or r/Tokyo), the "Sleep Valley" is usually very deep—often dropping to <5% of peak volume.
The Data: In your graph, the activity during the "Sleep Zone" (00:00–08:00) never truly bottoms out. It maintains a volume of roughly 30–40% of the peak volume.
Interpretation: This implies a Global/Diaspora user base. The "sun never sets" on this subreddit.
If the user base were truly "Chinese nationals in China" (as the subreddit name implies), the blue zone would be nearly empty due to the Great Firewall and the time of day. The sustained activity proves that a significant portion of the user base is accessing the site from outside the UTC+8 timezone.

3. Reconciling with Previous Data

The Previous Graph (KDE Plot): Showed a massive peak at 02:00 Beijing time. That likely analyzed the historical aggregate or specific "Tankie" keywords.
This Graph (2025 Recent): Shows a peak at 22:00 Beijing time.
The Synthesis: The subreddit likely has a mix of two populations:
The "Lurkers/Casuals": A diaspora audience (Asian-Americans or Chinese expats) who post in their evenings (creating the 22:00 Beijing peak, which is morning in the US).
The "Activists/Tankies" (The 3 AM Spike): The hardcore ideological users (identified in your previous steps) who are active during US daytime/China nighttime.

Overall, it shows that the subreddit people go to isn't a normal or average-joe subreddit. I would bet its the same thing as r/askchina. It's the subreddit that never sleeps which could be a big sign its chinese diaspora and tankies who are active. Not chinese users in china.

# Racing Users & Brigade
![a031d55b-876a-4cc0-b0db-acc3951ee3a4](https://hackmd.io/_uploads/B1mFijWWWg.png)
> Note: Again, Automoderator is there so ignore that. I forgot to clean the data.

1. The "High-Frequency Trading" of Ideology

In finance, "High-Frequency Trading" (HFT) relies on being microseconds faster than the market to secure a profit. Your script reveals an ideological version of this.
The Data Point: Coverage: 99.0% of new threads are raced by the same brigade.
The Implication: If you post in these subreddits (or the target r/AskAChinese), there is a 99% chance that the very first notification you receive, and the first thing other readers see, comes from a pre-approved "Racer" or AutoMod.
Psychological Effect (Anchoring Bias): Cognitive science tells us the first piece of information (the "Anchor") heavily biases all subsequent decision-making. By racing to be Comment #1, these users force the entire thread to debate on their terms.

2. The "Sino" Bunker (The AutoMod Wall)

Looking at your TANKIE_RACING_FULL_2025.csv specifically for r/Sino:
Pattern: Almost every single entry is AutoModerator → AutoModerator.
Fastest Time: Often 1 second.
Analysis: r/Sino is running a "Walled Garden." They don't even trust their own human superusers to set the tone. They use automation to instantly flood the thread with disclaimers or pre-written narratives, effectively "freezing" the thread until the approved framing is established.

3. The Human Racers (The "Deprogram" & "SLS" Cluster)

In r/TankieTheDeprogram and r/ShitLiberalsSay, the pattern shifts from Bots to Super-Activists.
Top Racers: ilir_kycb (6), melissamcard (5), saymaz (3).
The "Key-Needleworker-702" Connection:
In your CSV: ShitLiberalsSay, 1p1vx46 ... comradeda → Key-Needleworker-702, 111s.
Recall: Key-Needleworker-702 was one of the Top 3 Bridge Users in your earlier Network Graph connecting r/Sino to r/AskAChinese.
Conclusion: This confirms that the users "racing" in the radical subs are the exact same specific individuals exporting that behavior to r/AskAChinese.

4. The 99% Stranglehold

The statistic 97/98 posts having a known racer in the top 3 is statistically absurd for an organic community.
Organic Community: In a normal sub (e.g., r/movies), the first commenter is random. It depends on who is browsing "New" at that moment.
This Community: The first commenter is deterministic. It is always the same small clique.
Diagnosis: This indicates "Queue Camping." These users (or their scripts) are monitoring the RSS feed of the subreddit and reacting instantly.

What user taken:
The Base: Western-based activists (Timezone Analysis).
The HQ: r/Sino (Network Graph).
The Tactic: They use "First Comment Racing" to exploit Anchoring Bias (Racing Script).
The Execution: A small squad of veteran users (Account Age) camps the "New" queue.
The Result: r/AskAChinese is effectively a puppet state. While the subreddit name implies a broad cultural Q&A, the 99% First-Mover Dominance ensures that no "wrong" opinion ever gains traction before the "correct" opinion is planted.

What actually happens is that normally in subreddits, the commenter is always random but this subreddit, the known users are more likely to wait and quickly ensure there is no other bias ever gains traction before the correct bias is sent.

![4c0f6584-19b5-4a7e-8862-87fd8939dc02](https://hackmd.io/_uploads/By9t2jbW-e.png)

> Note
> ignore the red thing, GenZdong subreddit is banned so apparently its using other subreddits.

If we look at 24 known tankie racing accounts, only 54.2% of users are active in r/askachinese.

1. The "Conversion Rate" (54.2%)

In user analytics, an overlap of 54.2% between a radical niche community (r/Sino) and a "general interest" community (r/AskAChinese) is statistically overwhelming.
Normal Behavior: Power users usually stick to their "home" subreddit because that is where they get the most karma and validation.
Observed Behavior: More than half of the "Sino Racers" are expending significant energy in r/AskAChinese.
Conclusion: This is not casual browsing. This is deployed activity. These users are treating r/AskAChinese as an extension of their ideological territory.

2. The "5mao" Signature

The presence of the user 5mao (ranked #3 with 14 comments) is a distinct data artifact.
The Term: "5mao" (wumao) refers to the "50 Cent Army"—state-sponsored internet commentators.
The Behavior: Looking at the timestamps (First Seen: 2025-11-23, Last Seen: 2025-11-23), this account dropped 14 comments in a single day.
Interpretation: This is a "Burner" or "Campaign" account used for rapid-fire narrative control, likely activated to swarm specific threads.

3. The 403 Error (li123456)

The user li123456 returned a 403 HTTP Response.
Meaning: This usually means the account has been Suspended by Reddit Admins or Shadowbanned.
Significance: High rates of admin bans are common in "brigading" clusters because their behavior (vote manipulation, harassment) triggers Reddit's automated defense systems. The fact that your list includes banned users validates that this group engages in rule-breaking behavior.


---
# overall?
The Motive (Sentiment Analysis):
The discourse is Bimodal (Extreme Love / Extreme Hate), characteristic of ideological warfare, not cultural exchange.
The Source (Network Topology):
The user base does not connect to random subs; it connects strictly to the Authoritarian Left (r/Sino, r/Deprogram) cluster.
The Location (Timezone Forensics):
The "Chinese" users are most active at 3:00 AM Beijing Time (US Afternoon), proving they are physically located in the West.
The Method (First-Comment Racing):
99% of new threads are instantly commented on by a small clique of "Racers" to anchor the narrative before anyone else arrives.
The Agents (Crossover Analysis):
54% of the "Racers" from r/Sino are the exact same people controlling the conversation in r/AskAChinese.

In my thoughts, this whole data collection is very interesting to say the least because it open my eyes alot to see the subreddit influenced by pro-CCP or extreme left subreddit. Knowing there is probably teenagers happened to be in this subreddit is very concerning, if you actually read it through by putting three username we gave earlier and put it here -> https://ihsoyct.github.io/

You can copy this doc and run it yourself via google colab
https://colab.research.google.com/drive/153dAF75M0LrSVZ-1IGFPR7lfALwOKx5_?usp=sharing

Data compiled: https://drive.google.com/drive/folders/1Br6QgVCH62I9Q2CNSXM0GUbPchu1Goyi?usp=sharing
