# PraxisConnect

*A Hub to Bring Praxis Nation Citizens Together*

## Core Features

### User Profiles

- Citizen Profile: 
	- Praxis ID 
		- Name 
		- Class: "Citizen", "Nomad", "Admin", etc
		- Date Issued
		- PRX No
	- Primary Location 
		- City/Town 
		- Country
	- Social Media links
		- X, 
		- Instagram
		- Facebook
		- Mobile No.
		- Discord
		- Telegram etc.

- Administrator Profile: 
	- Administrator profile inherits from Citizen profile but allows back-end and configuration access (Class: Admin).

- Build On Praxis profile: 
	- Linked to Citizen profile, but for company details if citizen is a company owner/team member that has it registered on the Build On Praxis Program. 
	- Fields: 
		- Org Name
		- Org ID
		- Status
		- No. of People etc.
	
### Social Graphing

- Citizen Directory with Search: 
	- Allow citizens to search and filter for other citizen profiles based on various criteria (e.g., Class, Location).

- Social Graph: 
	- Traceable back-end link (represented via an icon) for each user profile, recording social "connected-ness", via payment or secure chat contacts, indicating who knows who.

- Network Graph Visualisation: 
	- Display a network graph visualising connections between citizens 
	- Potentially highlighting social and economic relationships via on-chain transactions or chat contacts.

- Smart Citizen Connect: 
	- AI-powered recommendation tool that suggests citizens to connect with based on shared interests, skills, or location.

### Integrations

- PRX Payments Crypto Payment Integration: 
	- Enable secure peer-to-peer payments using Crypto currency
	- Enable crypto payment integration with non-custodial wallets
	- Abstract away complexities for users to send tokens using User info
	- Supported chains include EVM chains, BTC, and Solana.
	- [viem](https://viem.sh/)

- Secure Chat Integration:
	-  Citizens can create group chats and one-to-one private messages.
	- Integrate Matrix Server back-end for secure p2p encrypted communications, 
		- [Matrix API Docs](https://spec.matrix.org/v1.14/)
	- Possibly XMPP Secure chat implementation instead of matrix due to reduced scale and increased performance.
	- Cell Group integration [Cells](https://discord.com/channels/813494644066877460/1340076956523302963)
	
- Governance / Town Square forum
	- Possible use and integration of Fora like Discourses
	- Citizens to vote on new and suggested initiatives, rules and regulations for Praxis when needed
	- Extension to on-chain reputation and community attestation tracking mechanisms
		- Progressive token system where one can rise up the ranks receiving a new soul-bound NFTs liked to profile info. 
		- Community quality attribution mechanism, where this progression is determined by community standing 

- Research & Commercialisation Hub
	- Start co-creating and spawning innovative products, services to both serve the future of Praxis' financial sustainability and wider global markets
	-  Cell organisation where the social graph could provide suggestions of people to connect with based on technical or business compatibility
	- Ideas / Organisation launchpad
		- Smart contract mechanisms could manage IP rights and automate incentive optimisation. 
		- Citizen's seeding ideas could receive 'equity' to follow through and build their ideas - while suggested contributors could receive these aligned opportunities on the hub for smarter cell organisation


- News Feed: 
	- A feed able to display RSS Articles, Audio-Visual content, or any relevant news and community content as deemed by administrators.
  
 - Jobs Board: 
	  - feed showing active and available ecosystems projects or jobs

- Events Calendar
	- Calender showing planned community events time table
	- RSVPed Citizens

## Style Guidelines:

- Primary color: 
	- Use Praxis Nation's existing branding colours [website](https://www.praxisnation.com/) or a professional blue (#2E9AFE).

- Secondary color: 
	- Light gray (#F5F5F5) for subtle accents.
	- [Flag](https://www.praxisnation.com/flag.png) for backgrounds

- Accent: 
	- Teal (#008080) to highlight interactive elements and important information.

- Layout should inherit from best practices of similar popular community applications
	- Clean and modern typography for readability.

	- Consistent and recognisable icons for navigation and features.

	- Clean and intuitive layout with a focus on user experience.

- Each function should be given an appropriate segment in the app. 

