# socialmedia

Social media ideas.

## General

### Free Speech and Content Moderation

#### Free Speech

Speech is being policed on the current crop of social media sites based upon political
viewpoint.

I don't think I need to defend this point, but I'll give a few examples
- People have lost their accounts for making jokes about topics of which certain people of
  certain political persuasions are hypersensitive.
- Discussion of Hunter Biden's laptop was supressed
- Discussion of the person Eric who was called a "whistleblower" was blocked, even though this
  was a public person and his name was already known and leaked.
- Alternate medical views about COVID were supressed and accounts of highly decorated doctors were cancelled.

#### Legally Forbidden Speech

Free Speech absolutism is not allowed anywhere, AFAIK. Speech that violates the law is to be
handled appropriately. Usually a platform is not required to find and remove such speech until
a court order comes upon them. At that point, they are required by law to remove the offending
material. A social media platform must have the ability to remove posts that are required to
be removed by law. Each distributed node can take whatever action they are legally obligated
to take. Nodes in other countries, for example, may not have the same legal requirements.

#### Minimal account cancellations

The current crop of social media sites bans accounts temporarily or permanently based upon
violations of community guidelines. That is not acceptable. If a person makes a mistake, they
should not be unpersoned.

However, if an account is clearly used for repeated abuse such as high volume spam, account
cancellations in those sorts of sitautions are reasonable, so long as the account is not
strongly tied to an individual human who is banned from getting another account. Humans must
always have a path to forgiveness and reconciliation.

Even in that extreme case, throttling might be a better solution. The more they spam, the longer
the wait time to create another post. As the exponential backoff increases, they choke their
own account.

#### Content Filtering

Rather than having censors censor material that violates some set of guidelines, users should
be able to subscribe to content filtering services. Each user can choose who they trust to
filter their content (or indeed to trust no one and see everything).  This is similar to how
we handle email spam today.

### User Accounts

#### Anonymity

People behave better when they are exposing their true legal identity.

However anonymity has in the past been invaluable. The Federalist Papers were written anonymously
under the pseudonum Publius. Benjamin Franklin published anonymously under the pseudonym
Silence Dogood. Whistleblowers and those whose lives are threatned need anonymity.

Furthermore, there is no practical way to enforce a one to one mapping to a real-life identity.

#### Universal Identity

If identities are tied to a specific server instance, moving away from that server causes
a loss of your entire audience. The system should have universal identities, yet without
centralization.  This can be done e.g. with a large identity space (random snowflakes or
public keys)

#### Self Registration


### Decentralized and Uncancellable

Parler was cancelled by Amazon, Joyent, GoDaddy, and other service providers in a simultaneous
takedown under the specious claim that the platform was being used to organize violence and
the company was not taking down threats of violence fast enough. When looked into deeply, it
was clear that nearly 100% of the Jan 6 capitol riot organisation was happening on Facebook.
Yet Facebook was not taken down. I carefully watched the legal case of Parler versus Amazon
and was dismayed at how bad the legal system is and how wrong they got this.

The solution so this cannot therefore be legal. The technology must be decentralized and
uncancellable.

### Aggregatable

Nobody wants to check 17 different social media sites to keep up with the news and their
tribe. Aggregation is essential. While we don't need to aggregate, we need to be aggregatable.

### Standards Based

The protocols and standards should make up the system, not specific software nor specific
services. Competing implementations will improve the system. Lock-in will be prevented.

### FOSS implementation

There should be a reference FOSS implementation.

## Posts

### Kinds of Posts

Blog posts. Forum entries. Replies. Chat (expiring posts). Private messages.

Posts can contain links to multimedia, but that is stored in another service.

The feature set should circumscribe the major features of Twitter/Mastodon, Slack, Youtube, Forums, Hacker News, and Reddit.


### Downvotes?

Rather than downvotes, I'm imagining
- You can upvote/agree with a single click
- To downvote/disagree you need to provide a 'disagreement' reply. Often people don't understand
  why they are downvoted and it leads to bad feelings. Having an explanation, even if it's mean,
  is better than people making up wrong reasons in their heads.
- You can also mark replies with 'agree' if you want to explain your agreement.
- You should be able to mark a post as 'final' meaning it allows no votes or replies.

### Editing?

You should be able to edit posts, but only up until they are voted on or replied to.
Otherwise it would invalidate the meaning of the votes and replies.

In case one needs to edit a post that was already voted/replied, they can respond to it
with a special kind of response which causes a link to appear in the original post
indicating that the post has an update, and pointing to the updated version.  Once done,
the edited post cannot be further replied to, but the reply (via the link) can.

If you regret a post, you can mark it retracted, but you cannot delete it if it has been
replied to (you can delete if it was only voted on).  If you seriously regret a post,
you can abandon it. It still won't be deleted, but your name will be disassociated and
it will be authored by "Abandoned".

The reason we don't like deleting posts is that posts thread, more like Hacker News or
Reddit, less like Twitter. And conversations become hard to read with missing posts.







