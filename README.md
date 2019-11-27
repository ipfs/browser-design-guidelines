
# IPFS Browser Design Guidelines

In preparation for a 2020 expansion of Protocol Lab’s IPFS browser integrations and standardization efforts, there needs to be guidelines and recommendations on hand in order to get to our first billion users.

### What the guidelines are

The IPFS Browser Design Guidelines will be an implementation kit for browser security and design teams and for standards groups such as the W3C and IETF. It will contain research, use-cases, UX patterns, and examples of iconography. This implementation kit for IPFS will be specifically tailored to how browser URL bars are implemented today.

### How the guidelines will be used

Initially this material will guide Protocol Labs’s own projects (Desktop, Companion). Additionally, it will help guide the smaller and more experimental browser implementations where we can learn, test and iterate. That will set us up for working with larger browser vendors and the standards groups later in 2020, putting this material to use in broader ways.

## Research

While the browser landscape has never been bigger, with increased specialisation in terms of privacy or blockchain, there doesn’t seem to be any investigation or development in terms of P2P or distributed enabled browsers. 

The intent of the research phase is to examine and explore the use-cases for IPFS in browsers, P2P usage in browsers at large in order to create and publish design guidelines and recommendations for browser vendor implementation and standards bodies.

The research was split into three parts. The first was an [exploratory and scoping workshop][1] with three key developers of IPFS to look at where the leading developmental issues may lie. Afterwards, the second phase was [non-expert research][2] with average users, in this case defined as non-developers or people working on internet protocol level issues. This covered their browser use, their understanding of location and addressing in the browser and knowledge and opinion on P2P in general. Lastly, a small cohort of [expert users][3] involved directly with P2P or IPFS development, cryptography or browser development were interviewed to gather specialist knowledge and opinions on the domain and technological and user landscape.

### Non-expert research

We conducted research with seven participants, spread geographically and across genders and occupations to determine their conceptions, concerns and ideas about addressing conventions and P2P technologies in modern browsers. 

In depth interviews with notes and findings are found in the [wiki][4].

1. [Nina][5]
2. [Charlotte][6]
3. [Aleks][7]
4. [Dom][8]
5. [Basil][9]
6. [Jon][10]
7. [Matthew][11]

### Expert research

An expert/stakeholder workshop was conducted in conjunction to the ongoing expert interviews to explore the problem space, relevant technology and possible solutions.

In depth interviews with notes and findings are found in the [wiki][12].

1. [Ed1][13]
2. [T][14]
3. [Ed2][15]
4. [James][16]
5. [Yiannis][17]
6. [Tiff][18]

## Design hypothesis

#### Initial assumptions

- The URL as a mechanism and way to understand location on the Internet is fairly well understood and usable
- Privacy and encryption is a concern for the majority of users
- P2P in a browser is largely only understood by developers
- P2P (and IPFS) is easy to understand
- The use cases of P2P in terms of a browser are clearly understood

#### Key research findings

- The URL is only important as a backup and source of credibility that the right things are happening in the browser
- Privacy and security are a great concern to users, both expert and non-expert, however, it is not greatly understood by non-experts and they often have misconceptions and are thus largely left feeling hopeless about it
- Although the URL or what is happening in the URL bar may not be widely understood, nobody wants it to go away as it serves as a semi-readable source of authenticity, for instance at a domain level
- P2P is largely understood to be about files that are in many places at the same time by many people, but is largely thought of by non-experts as a tool for media piracy
- Most assume P2P makes things faster and somehow more secure
- There are potential opportunities with P2P in terms of lowering CDN costs and lessening or eliminating the need for invasive advertising
- Incentivisation needs to be thought out in great depth

#### Key design and user context questions and issues to be explored in the design phase

- In order for P2P (ex. IPFS) to be used by the wider browser or Internet user base it needs to accomplish typical user tasks easier than they do now
- Clearly communicating the benefits of using P2P technologies
- Setting context both for range of users and for use in quickly orienting people as to what they are doing
- The user should know they are using P2P, but not overwhelmingly so
- The enabling of and participating in a P2P scenario needs to be stepped through the first few times and then disappear into the background
- The actual working of the protocol should not be apparent to the user
- Identifying the set of visual components present, what they communicate and future work

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

[1]:	https://github.com/ipfs/browser-design-guidelines/wiki/Stakeholders-workshop
[2]:	https://github.com/ipfs/browser-design-guidelines/wiki
[3]:	https://github.com/ipfs/browser-design-guidelines/wiki
[4]:	https://github.com/ipfs/browser-design-guidelines/wiki#non-expert-interviews
[5]:	https://github.com/ipfs/browser-design-guidelines/wiki/Interview-Nina
[6]:	https://github.com/ipfs/browser-design-guidelines/wiki/Interview-Charlotte
[7]:	https://github.com/ipfs/browser-design-guidelines/wiki/Interview-Aleks
[8]:	https://github.com/ipfs/browser-design-guidelines/wiki/Interview-Dom
[9]:	https://github.com/ipfs/browser-design-guidelines/wiki/Interview-Basil
[10]:	https://github.com/ipfs/browser-design-guidelines/wiki/Interview-Jon
[11]:	https://github.com/ipfs/browser-design-guidelines/wiki/Interview-Matthew
[12]:	https://github.com/ipfs/browser-design-guidelines/wiki#expert-interviews
[13]:	https://github.com/ipfs/browser-design-guidelines/wiki/Interview-Ed1
[14]:	https://github.com/ipfs/browser-design-guidelines/wiki/Interview-T
[15]:	https://github.com/ipfs/browser-design-guidelines/wiki/Interview-Ed2
[16]:	https://github.com/ipfs/browser-design-guidelines/wiki/Interview-James
[17]:	https://github.com/ipfs/browser-design-guidelines/wiki/Interview-Yiannis
[18]:	https://github.com/ipfs/browser-design-guidelines/wiki/Interview-Tiff
