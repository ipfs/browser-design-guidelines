# IPFS Browser Design Guidelines
Guidelines and recommendations for browser vendor design and implementation of IPFS

[Discussion and documentation living here for now on HackMD][1]

## Research

Background

Methodology and approaches

Examine and explore the use-cases for IPFS in browsers, and publish design guidelines and recommendations for browser vendor implementation

[ Survey of browser URL bar implementation ][2]

### Non-expert research

We conducted research with seven participants, spread geographically and across genders and occupations to determine their conceptions, concerns and ideas about addressing conventions and P2P technologies in modern browsers. 

#### Nina

Nina is a woman with a family concerned about privacy but confused and not sure where to start.

Key findings:

- The location or address bar is mainly for search
- Tries to pay attention to the URL because it is describing what is going on with the web page and could possibly indicate privacy concerns
- The URL tells here where she is, and is a good backup even though she’s not entirely clear on it’s convention that she is on the right site
- The padlock icon indicates it’s a secure connection and nobody can get into her connection to it. Likewise HTTPS is important and looks for it but sure what it does.

[Interview notes][3]

#### Charlotte

Charlotte has background and training in public sector work and is thus fairly versed as well as highly concerned about tracking and malicious actors on the Web.

Key findings:

- Is familiar with many browsers and using proprietary, secure browsers and pays attention to URLs, especially in regards to domains and suffixes for countries
- Looks for HTTPS and subtle differences in addresses to make sure not being redirected
- She has a friend at ICANN so knows how addresses are signed but otherwise would have no idea
- Shortened URLs don’t seem to have any logic
- There should be a topic, author and/or title in the URL to help you know it’s the right thing and you’re in the right place
- Has a good, cursory understanding of P2P but not sure that it’s worth all the effort or time

[Interview notes][4]

#### Aleks

Aleks is an academic and social scientist and uses a browser non-stop for accessing and working on data for research and administration. 

Key findings:

- Uses bookmarks especially for links that look long or convoluted and doesn’t understand what they do
- Never looks for the padlock icon and generally doesn’t have any trust issues with URLs or the address bar, especially if the domain is from a trusted company or organisation
- He’s warned constantly by his university about links and internet safety
- Doesn’t necessarily know or understand what P2P is

[Interview notes][5]

#### Dom

Dom works in personal and business finance and almost all of his professional practice work is in a browser. He is interested in seeing context around what he is finding and where he is on the Web.

Key findings:

- Uses bookmarks a lot and when he doesn’t have one he searches with the address bar
- Doesn’t generally pay attention to the address bar except when autocomplete goes wrong
- He tries to find ‘clean’ addresses when he needs to send a link to someone and will even copy and paste and edit it to try and figure out which is the best one to send
- If there is a very long URL he trusts it less
- Feels that he is quite secure with using lots of banking websites and having a password manager and two factor authentication but needs to pay more attention to if its a secure website or not

[Interview notes][6]

#### Basil

Basil is an entrepreneur in the sports and entertainment sector and very interested in data. He has a wide and varied experience with many browsers and the Internet in many countries.

Key findings:

- Actively looks for HTTPS in the URL
- Pays attention to the URL in particular for codes or affiliate links that might be in them and understands roughly how they work
- Believes URLs or the browser should be more specific and tell the user what is going on with them
- Would like to understand more about P2P but thinks there needs to be first an agreed and common definition of what it means that people can understand
- Warning can be too intrusive and annoying and ruin things even with good intentions, such as the GDPR warnings for cookies

[Interview notes][7]

#### Jon

Jon is a writer who works on many collaborative platforms throughout the day and constantly uses speciality writing websites as a power user. He is interested in the Web primarily for getting work done and for entertainment.

Key findings:

- Doesn’t really pay attention to URLs
- Never types addresses in, just uses search and hopes it translates that into taking him to the right website
- Only notices anything with a website when there is a big warning
- Has some understanding of URL structures from having to write for blogs and use Wordpress
- Doesn’t understand why some addresses have HTTP and other HTTPS
- Thinks of P2P as something would not expect to see or even know if using and generally used for pirating media

[Interview notes][8]

#### Matthew

Matthew is a designer familiar and comfortable with working on and working to put things on the Web. He has many concerns about privacy and doing the right thing with his web browsing but like many, sometimes forgets or lets it fall by the wayside.

Key findings:

- Splits browser use between a home and a work browser
- Looking at structure of URL, or if clicked something and has tracking stuff in it conscious of
- If not HTTPS very conscious of that
- Sometimes have a splurge about privacy and take precautions and then forget about it for a while
- Like to see the URL for sure and if didn’t would be slightly worried
- Like to see the hierarchy of information and doesn’t want the browser to be just delivering the page
 - He thinks everything is where it should and fine be in terms of how you see security and location

[Interview notes][9]

### Expert research

An expert/stakeholder workshop was conducted in conjunction to the ongoing expert interviews to explore the problem space, relevant technology and possible solutions.

#### Ed1

Ed is an experienced developer working on archival systems for cultural heritage institutions and museums and very involved in working with P2P protocols and file stores. While working heavily in the sector Ed is very skeptical about user uptake for P2P technologies and think efforts should be instead concentrated on the academic and scientific sectors.

Key findings:

- Average users don’t care about URLs and find them confusing as their structure was never meant to be human-readable necessarily
- Browsers, besides Chrome, are very bad at explaining what is going on with addresses and security
- URLs and the address bar should probably stay just the way it is as users hardly use them but still needs to be there
- The average person doesn’t care where the data actually is
- P2P has very high barrier to entry as many average users don’t understand the advantages and why it may be worthwhile for them

[Interview notes][10]

#### T

T is working on cryptography and protocol level development.

Key findings

- Things with security and encryptions should be mostly transparent to the user. It should be secret and quick
- The lock is in a lot of unnecessary places even though there is no exchange data or info and this can be misleading
- The Web getting more and more encrypted in general
- P2P for most people is a layer on top of the Internet, just like Tor, and would not give you the same security as Tor but more decentralised. This is good and bad.
- A company that wants to make P2P cool needs to think about what is the selling point to the user. People shouldn’t have to get it, it should be just good and usable. But if you need to differentiate yourself in the market and it’s complicated what you’re doing, how do you sell that?
- P2P is just content delivery, it should just work.

#### Ed2

Ed is a principal designer at a large and longstanding software company and been working on browsers for the past ten years. He is wary of how p2p will be accepted and keen for it to be well thought out in terms of context and use.

Key findings

- URLs now have tokens and strings interpreted by the website with content, making them not hierarchal anymore. Therefore any design around this should reflect it being non-hierarchal.
- The URLs is largely not that useful for most users, but simplifying it doesn’t get your anywhere and just breaks things for people who actually use it
- The main barrier to entry with p2p is how do they get there how does it work with people’s existing work flows and patterns
- P2P if it’s going to be useable for people needs to not rely on regular browser conventions and probably look and feel drastically different

[Interview notes][11]

#### James

James works as a browser design for a new and innovative software company focused on privacy and new web business models. He feels that security around where you are with whom you’re connected on the web is generally not well understood by most users but there are also new opportunities for designing around data control.

## Key findings
- There is currently a lot more narrative around taking control and the protection your data but many users aren’t likely to necessarily sacrifice convenience
- There is an opportunity to reinvent what is going on with URLs and the address bar and what it means - nobody really has nailed it down
- P2P adoption requires thinking about how do you make it interesting to your friends. Put these common occurrences together for them, that maybe this makes it safer - just turn this on and get rid of all the ads. You need to present a very clear and very direct solution to a problem they have
- From the dev side the value proposition of P2P is huge with speed and privacy but with speed you need to incentivise more and more people to share to make it faster

## Design hypothesis

Initial assumptions

Research findings

Key wider landscape questions

‘Pulling it all together’ questions

Survey review used for setting context both for range of users (i.e. turbo onramp) and for use in quickly orienting people in future reports, presentations, etc. This could help identify the set of visual components present, what they communicate and future work.

[1]:	https://hackmd.io/BC4VXCr4TW6tUXnYZKOO0A?view
[2]:	https://hackmd.io/LnKfUUM_TAqw4JfRw_XmdA
[3]:	https://hackmd.io/@jkosem/rk7hPmWnS
[4]:	https://hackmd.io/@jkosem/S1wEA9ZnS
[5]:	https://hackmd.io/@jkosem/SJvt0cZ3B
[6]:	https://hackmd.io/@jkosem/ryngA2z2B
[7]:	https://hackmd.io/@jkosem/Hkq2p5-nr
[8]:	https://hackmd.io/@jkosem/S18v9vHhH
[9]:	https://hackmd.io/@jkosem/S1K6ZcB2B
[10]:	https://hackmd.io/@jkosem/S1ydrQZnH
[11]:	https://hackmd.io/@jkosem/B1Gevrc2S