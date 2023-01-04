# What is ML?

The answer to the question "What is ML?" will undoubtedly depend on who you ask. Instead of trying to provide a completely coherent language or ontology for ML, I will merely attempt to provide a descriptive one that gives you a mental framework for mapping tools to problems. If you find yourself observing that certain things that I have described as different are really special cases of each other - congratulations and your welcome. These are after all my favorite type of observations.

## Three tasks

I will describe machine learning as falling into three tasks:

1. Describing a labelled structure in data (supervised learning - SL).
2. Describing an unlabelled structure in data (unsupervised learning - UL).
3. Building agents that learn from experience (reinforcement learning - RL).

Before diving into more formal definitions - let's consider (lots of) examples. Imagine that you run a website dedicated to a two player board game you invented called snorg. Your website has it all - articles that are monitized by ads, the ability for users to play against a computer player, and a premium learning mode that gives players snorg problems that match their ability. Here are some problems you might encounter:

### Looking for bots.

While your site gets some great users, there are also a lot of bots that crawl your site doing various things. How can you identify these we sessions even if there is no explicit "bot label" in the data? (UL)

### Looking for fraud.

Some users sign up for your premium service only to pay with stolen credit cards that are later marked as fraudulent transactions by the bank. Can you flag these sign-ups as they happen so as not to be party to this bad behavior?

### Recommending ads.

Part of your site's revenue is from advertisements, where you are payed for each click. Which ad should you show to each user to maximize ad revenue? (RL)

### Recommending articles.

Since ads are shown alongside articles on your site, more articles read in each session translates into more revenue. At the bottom of each article you would like to recommend the three most similar articles. Given an article, what are the three most similar articles? (UL)

### Predicting churn.

What's the point of getting new premium service customers if you can't keep the ones you have? You would like to identify which customers are at risk of unsubscribing from the premium service so that you can offer them a discount to keep their business. Given a customer, what is the probability they will unsubscribe in the next 30 days without intervention? (SL)

### Playing snorg.

Since snorg is a bit of a rare game, it can be difficult to find a partner to play with. You need to create a snorg playing agent (with various difficulty levels) so that your users can play the game online at your site. (RL)

### Representing a user.

Each user at your site comes with a wealth of information - technographic data like device type and browser, temporal data like the date and time of their visits to the site, contextual data like what articles they read on the site or their snorg game details - can you represent users with a single vector of real numbers in an information dense way so that your models have a consistent and valuable feature set? (UL)

### Creating an audience.

Your advertisers will sometimes make ad buys based on audiences you create for them. They will upload a spreadsheet of known customers' email addresses. Your job is to identify these users within your site traffic and deliver users with similar interests or behaviors. (SL)

### Selecting problems for a student.

Your premium users have access to "snorg tutor" - a computor tutor that will choose snorg problems from a large pool. You need to design an agent that will select appropriate problems so that the user stays on the site as long as possible. (RL)

## Supervised learning

Sometimes the universe grants us partial and noisy access to a function:

$$f: X \to Y$$



## Unsupervised learning

### Clustering

### Learning generating distributions

### Topological data analysis

## Reinforcement learning

### The MDP setup

### Bandit problems

### Success in game playing
