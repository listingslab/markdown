---
slug: "/api"
title: "RESTful API"
book: "Growspy"
description: "Node JS with Google Firestore"
keywords: "api, RESTful, node, google cloud, roadmap, GraphQL, serverless, firestore"
icon: "code"
image: "/png/og/pi.png"
order: 55
---
### Growspy's Node RESTful API lives on Google Cloud

It's a Node JS app with Google Firestore as th DB. It has a serverless functional architecture using functions and Google’s powerful, cloud-based nosql database; Firestore. Roadmap is to offer this as GraphQL too. To add auth to a request, add the header **GROWSPY** and your **API Key**. Data on each **Spy** will start to replace itself after a week so each collection doesn’t get too big

And it's name... is airwolf. Just kidding. It isn't

## Usage

api.growspy.app

- /{spy_id}  
	POST  
	GET (authed)  
	GET (public)  
	DELETE  

- /spies  
	GET (authed)  
	GET (public)  

- /locations  
	GET (public)  

- /users  
	GET (authed)  

