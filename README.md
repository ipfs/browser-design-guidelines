
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

Lastly, a small cohort of [expert users][12] involved directly with P2P or IPFS development, cryptography or browser development were interviewed to gather specialist knowledge and opinions on the domain and technological and user landscape. In depth interviews with notes and findings are found in the [wiki][8].

## Design hypothesis

#### Initial assumptions

- The URL as a mechanism and way to understand location on the Internet is fairly well understood and usable
- A URL is at least partially human-readable by most people
- Privacy and encryption is a concern for the majority of users but many if not most don’t explicitly care where the data comes from, just as long as it’s authentic or credible
- What is going on in a browser with privacy and a secure connection is largely understood
- Domains are signs of trust and at least partially comprehended in terms of what is going on, for instance .com, .org, etc.
- P2P in a browser is largely only understood by developers
- P2P (and IPFS) is easy to understand
- The use cases of P2P in terms of a browser are clearly understood

#### Research findings

- The URL is only important as a backup and source of credibility that the right things are happening in the browser
- The URL bar as it is presented now is probably fine just the way it is
- Almost across the board between non-experts and experts, URLs are rarely typed in and the URL bar is used for search as a primary means of navigation
- A few research participants use autocomplete with domains and finding URLs via history and bookmark functions in their browser
- HTTPS is something all users are aware of although they might not fully understand it’s implications
- Privacy and security are a great concern to users, both expert and non-expert, however, it is not greatly understood by non-experts and they often have misconceptions and are thus largely left feeling hopeless about it
- People have issues with long URLs and in particular ones that seem to have what are perceived to have codes or tracking things in them
- Wordpress and blogs have given people a better understanding of URLs
- The time is right to look at new modes of privacy, use and control on the Web
- There have been attempts in browsers, particularly with Microsoft and Internet Explorer, to bring a clickable interface to the URL
- Although the URL or what is happening in the URL bar may not be widely understood, nobody wants it to go away as it serves as a semi-readable source of authenticity, for instance at a domain level
- The URL is perceived to be potentially very useful if it had certain standard conventions or features such as having topic, author or title included
- P2P is largely understood to be about files that are in many places at the same time by many people, but is largely thought of by non-experts as a tool for media piracy which could have potentially given a good technology a bad name
- How files and folders work in P2P, especially in terms of the URL isn’t greatly understood by non-experts and experts
- Most assume P2P makes things faster and somehow more secure
- Users at large are overwhelmed if not defeated by ads, tracking, surveillance and privacy concerns
- Privacy as a concept on the Internet is understood differently in different parts of the worlds
- When in P2P ‘mode’, it may be very beneficial to the user to have a drastically user or visual experience to differentiate the mode of use
- There are potential opportunities with P2P in terms of lowering CDN costs and lessening or eliminating the need for invasive advertising
- P2P might be better suited to use that is more niche and not mass scale, such as scientific and academic publishing
- Incentivisation and participation models need to be explored much more and better communicated

#### Key design and user context questions and issues to be explored in the design phase

- In order for P2P (ex. IPFS) to be used by the wider browser or Internet user base it needs to accomplish typical user tasks easier than they do now, for instance sharing photos
- Clearly communicating the benefits of using P2P technologies
- Setting context both for range of users and for use in quickly orienting people as to what they are doing
- The user should know they are using P2P, but not overwhelmingly so
- The enabling of and participating in a P2P scenario needs to be stepped through the first few times and then disappear into the background
- The actual working of the protocol should not be apparent to the user
- Identifying the set of visual components present, what they communicate and future work
- Which niche use cases can be explored
- Where context and location and culture is important in perceptions of privacy, participation and P2P
 - P2P might be better use or explained with public folders like with Dropbox
- Repository thinking with check-in and check-out
- Trust and verification of content ownership and security when connecting to other people’s computers and devices
 - Incentivised with some reward, some page will give you. Maybe you won’t have to see an ad because you’re helping the network?
 - Could have incentives if someone gave to you and you needed to pay them somehow. Like FileCoin you stored it and delivered it. You replied to a request and it needs to be recorded.

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
[2]:	https://github.com/ipfs/browser-design-guidelines/wiki#competitive-landscape-survey
[3]:	https://github.com/ipfs/browser-design-guidelines/wiki/Stakeholders-workshop
[4]:	https://github.com/ipfs/browser-design-guidelines/wiki/Stakeholders-workshop
[5]:	https://github.com/ipfs/browser-design-guidelines/wiki#non-expert-interviews
[6]:	https://github.com/ipfs/browser-design-guidelines/wiki
[7]:	https://github.com/ipfs/browser-design-guidelines/wiki#expert-interviews
[8]:	https://github.com/ipfs/browser-design-guidelines/wiki
[9]:	https://fontawesome.com/