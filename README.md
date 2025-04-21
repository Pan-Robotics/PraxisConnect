# PraxisConnect


## Core Features

### User Profiles

- Citizen Profile: 
	- Praxis ID (Name, Class, Date Issued, PRX No.)
	- Present Location (City/Town, Country), 
	- Social Media links (X, Instagram, Facebook, Mobile No., Discord, Telegram).

- Administrator Profile: 
	- Administrator profile inherits from Citizen profile but allows back-end and configuration access (Class: administrator).

- Build On Praxis profile: 
	- Profile linked to citizen profile, but for company details if citizen is a company owner/team member that has it registered on the Build On Praxis Program. 
	- Fields: Org Name, Org ID, Status, People No.
	
### Social Graphing

- Citizen Directory with Search: 
	- Allow citizens to search and filter other citizen profiles based on various criteria (e.g., Class, Location).

- Social Graph: 
	- Traceable back-end link (represented via an icon) for each user profile, recording social "connectedness", via payment or matrix contacts, indicating who knows who.

- Network Graph Visualisation: 
	- Display a network graph visualising connections between citizens, 
	- potentially highlighting social and economic relationships via on-chain transactions or matrix contacts.

- Smart Citizen Connect: 
	- AI-powered recommendation tool that suggests citizens to connect with based on shared interests, skills, or location.

### Integrations

- PRX Payments Crypto Payment Integration: 
	- Enable secure peer-to-peer payments using Crypto currency
	- Enable crypto payment integration with non-custodial wallets
	- Abstract away complexities for users to send tokens using User info
	- Supported chains include EVM chains, BTC, and Solana.

- Matrix Chat Integration:
	- Integrate Matrix Server back-end for secure p2p encrypted communications, allowing citizens to create group chats and one-to-one private messages.
	- Cell Group integration [Cells](https://discord.com/channels/813494644066877460/1340076956523302963)
	- [Matrix API Docs](https://spec.matrix.org/v1.14/)

- News Feed: 
	- A feed able to display RSS Articles, Audio-Visual content, or any relevant content as deemed by administrators.
  
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

- Clean and modern typography for readability.

- Consistent and recognizable icons for navigation and features.

- Clean and intuitive layout with a focus on user experience.

- Each function should be given an appropriate segment and the app. 

- Layout should inherit from best practices of similar popular community applications
