
# IPFS Browser Design Guidelines

In preparation for a 2020 expansion of Protocol Lab’s IPFS browser integrations and standardisation efforts, there needs to be guidelines and recommendations on hand in order to get to our first billion users.

### What the guidelines are

The IPFS Browser Design Guidelines will be an implementation kit for browser security and design teams and for standards groups such as the W3C and IETF. It will contain research, use-cases, UX patterns, and examples of iconography. This implementation kit for IPFS will be specifically tailored to how browser URL bars are implemented today.

### How the guidelines will be used

Initially this material will guide Protocol Labs’s own projects (Desktop, Companion). Additionally, it will help guide the smaller and more experimental browser implementations where we can learn, test and iterate. That will set us up for working with larger browser vendors and the standards groups later in 2020, putting this material to use in broader ways.

## Research

While the browser landscape has never been bigger, with increased specialisation in terms of privacy or blockchain, there doesn’t seem to be any investigation or development in terms of P2P or distributed enabled browsers. 

The intent of the research phase is to examine and explore the use-cases for IPFS in browsers, P2P usage in browsers at large in order to create and publish design guidelines and recommendations for browser vendor implementation and standards bodies.

### [Survey review][1]

One of the first things to research was the [existing browser landscape][2], in this case concentrating primarily on current (2019-Nov) releases of Mozilla Firefox, Apple Safari, Google Chrome and Microsoft Edge, the aim of which was to establish the commonalities and baselines between the current browser stack. From this we could continue into exploring in detail through user research what works and what doesn’t with that.

### [Exploratory workshop][3]

An expert/stakeholder workshop was conducted in conjunction to the ongoing expert interviews to explore the problem space, relevant technology and possible solutions.

The user research was split into three parts. The first was an [exploratory and scoping workshop][4] with three key developers of IPFS to look at where the leading developmental issues may lay.

### [Non-expert research][5]

Afterwards, the second phase was non-expert research with average users, in this case defined as non-developers or people working on internet protocol level issues. This covered their browser use, their understanding of location and addressing in the browser and knowledge and opinion on P2P in general.
99
We conducted research with seven participants, spread geographically and across genders and occupations to determine their conceptions, concerns and ideas about addressing conventions and P2P technologies in modern browsers. In depth interviews with notes and findings are found in the [wiki][6].

### [Expert research][7]

Lastly, a small cohort of expert users involved directly with P2P or IPFS development, cryptography or browser development were interviewed to gather specialist knowledge and opinions on the domain and technological and user landscape. In depth interviews with notes and findings are found in the [wiki][8].

## Research findings

### Initial assumptions

- The URL as a mechanism and way to understand location on the Internet is fairly well understood and usable
- A URL is at least partially human-readable by most people
- Privacy and encryption is a concern for the majority of users but many if not most don’t explicitly care where the data comes from, just as long as it’s authentic or credible
- What is going on in a browser with privacy and a secure connection is largely understood
- Domains are signs of trust and at least partially comprehended in terms of what is going on, for instance .com, .org, etc.
- P2P in a browser is largely only understood by developers
- P2P is easy to understand
- The use cases of P2P in terms of a browser are clearly understood

### Research findings and themes

- The URL is only important as a backup and source of credibility that the right things are happening in the browser, thus although not always entirely understood is found to be likely fine the way it is
- The URL is understood as an address and pointing to a location, with content at that location
- URLs are rarely typed in and the URL bar is used for search as a primary means of navigation
- HTTPS is something all users are aware of although they might not fully understand it’s implications or understand why, but trust that it means “secure”
- Privacy and security are a great concern to users. However, ad tracking and surveillance is not greatly understood by non-experts and they often have misconceptions and are thus largely left feeling hopeless and defeated.
- Very long URLs are generally regarded as suspicious, such as having tracking in them, and shorted URLs are likewise not very trusted as they lack context with a domain
- Blogs have created a better understanding of URLs with non-expert users as they are quite readable. Likewise the URL is perceived to be potentially very useful if it had certain standard conventions or features such as having topic, author or title included
- P2P is largely understood to be about files that are in many places at the same time by many people
- Most assume P2P makes things faster and somehow more secure
- P2P is largely thought of by non-experts and some expert participants as a tool for media piracy which could have potentially given a good technology a bad name
- How files and folders work in P2P, especially in terms of the URL isn’t understood
- Privacy on the Internet is understood differently in different parts of the world
- When in P2P mode, it may be very beneficial to the user to have a drastically user or visual experience to differentiate
- There are potential opportunities with P2P in terms of lowering (CDN) costs and lessening or potentially eliminating the need for invasive advertising
- Expert users believe P2P participation models and value propositions need to be explored much more and better communicated
- P2P might be initially suited to use that is more niche, such as scientific and academic publishing

#### Key design questions

How might we best communicate in interaction and design that P2P is about in terms of being distributed and about files being in many places at the same time with many people?

- How best do we show this is the key value of P2P?
- Showing users what is going on (ie. how many people, who can see what, what I'm sharing)
- Graphical, quick and largely in the background

How might we replicate users's vague but useful understanding that HTTPS is secure with P2P without them having to know all the implications?

- Can we explore what "safe" means in the context of IPFS?
- Can we communicate that "S" goes with a control indication like the padlock?

How might we help users not feel defeated and hopeless amongst an internet full of ad tracking and surveillance?

- Can we show the core benefit of P2P (IPFS) is privacy without being bogged down in technical details?
- Can we show that external threat actors can not track them when they use P2P?

How might we show P2P is not only more secure, but that in some cases, is faster than HTTP?

- Can we indicate the transfer is encrypted, but your activity is visible?
- Can we display when it will be faster/slower to the user?

How might we communicate P2P is not just a tool for piracy?

- Can we replace language to describe how P2P works so it's not "it's like bittorrent"?

How might we make P2P addresses trustable?

- Can we make them not too long or looking as if they're hiding something?
- Could addresses be made more human-readable through things like IPNS?
- We are adding something new to the location bar, which changes it's name even.

How might we utilise the current convention of using the URL bar for search as a primary means of navigation for P2P?

- Is there a way to get around search not being good for IPFS?
- Is there an interaction design opportunity around autocomplete?

How might we show that P2P can lessen CDN costs and also lessen the need for advertising and tracking-bsed business content models?


## Design

The intent of the design phase of the IPFS Browser Design Guidelines is to examine and explore the use-cases for IPFS in browsers, and publish design guidelines and recommendations for browser vendor implementation

### Programme of work

- Interaction and user experience design work to solve the researched issues, mapping out user flows, design patterns and use cases
- Interface design

### Deliverables

- Screen designs including recommendations, iconographic and design treatments for existing browser URL bars
- User experience flows
- Design guidelines and component design to inform and help further development efforts
- Recommendations for further work

---- 

#### Credits

Free stuff used in this repo

Icons: [Font Awesome][9]

[1]:	https://github.com/ipfs/browser-design-guidelines/wiki#browser-survey
[2]:	https://github.com/ipfs/browser-design-guidelines/wiki#browser-survey
[3]:	https://github.com/ipfs/browser-design-guidelines/wiki/Stakeholders-workshop
[4]:	https://github.com/ipfs/browser-design-guidelines/wiki/Stakeholders-workshop
[5]:	https://github.com/ipfs/browser-design-guidelines/wiki#non-expert-interviews
[6]:	https://github.com/ipfs/browser-design-guidelines/wiki
[7]:	https://github.com/ipfs/browser-design-guidelines/wiki#expert-interviews
[8]:	https://github.com/ipfs/browser-design-guidelines/wiki
[9]:	https://fontawesome.com/
