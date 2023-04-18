# Project Specifications

Definition of the problem and solution idea from the user's perspective. It is composed by the definition of the personas diagram, user stories, functional and non-functional requirements in addition to the project constraints.

## Personas

Personas are examples of users of websites and streaming applications that were used to gather information about the problem in question. Introducing four examples of different ages and occupations in order to try to cover the widest possible spectrum of Streaming users and consumers of audio-visual content.

+ ### Rafaela Andrade

	![Representative Photo](https://user-images.githubusercontent.com/13721147/194158525-bbc9cf21-13af-47a7-ba23-97f21870d676.png) 

	+ **Age**: 21 years

	+ **Occupation**:  
	University student on a part-time course. She shares an apartment with friends from the same university

	+ **Apps**:  
Youtube; Netflix; Amazon Prime;

	+ **Motivations**:  
		+ Passionate about movies and series.
		+  Likes to discuss movie content with friends and family.

	+ **Frustrations**:  
		+ Few free time to search for new content.
		+  Lack of information about movies and series and you cannot leave an opinion or see the opinion of others.
		
	+ **Hobbies, History**:  
		+ Marathoning series with friends and/or family.
		+  Being able to use free time with more quality.
		


+ ### João Arruda Jr.

	![Representative Photo](https://user-images.githubusercontent.com/13721147/194162795-998632ec-3ce9-4959-bd37-d89d362249cf.png) 

	+ **Age**: 32 years

	+ **Occupation**:  
	Administrator. Store sales manager at Shopping Iguatemi. It also works in team training for this store's network.

	+ **Apps**:  
Youtube; Netflix; Amazon Prime; HBO Prime, Globo Play; Digital TV;

	+ **Motivation**:  
		+ Likes to receive title recommendations.
		+  Likes recommendations made by people.

	+ **Frustration**:  
		+ Gets home late and waste a lot of time finding movies you like.
		+  Even after a lot of wasted time, it disappoints with the movies I watched on the recommendation of streaming.
		
	+ **Hobbies, History**:  
		+ It was most accomplished with recommendations from the DVD store clerk, rental stores, and conversations with friends.
	
 
 
 + ### Graça Silva Dias

	![Representative Photo](https://user-images.githubusercontent.com/13721147/194163415-1477a5d7-7985-4c97-bee3-3177eb849e86.png) 

	+ **Age**: 43 years

	+ **Occupation**:  
	Graduated in Social Sciences. Long career as a Social Worker in the referral of children at family risk.

	+ **Apps**:  
Netflix; Amazon Prime; NET On Demand; Globo Play; Digital TV.

	+ **Motivation**:  
		+ Find people who have similar tastes.
		+  Some real stories can be used at work.

	+ **Frustrações**:  
		+ You cannot exchange information about the contents with other users in the stream.
		+  I don't have the freedom to filter the search results as I want
		
	+ **Hobbies, História**:  
		+ Movies based on real stories to inspire myself and others.



+ ### Emídio Conceição
	![Representative Photo](https://user-images.githubusercontent.com/13721147/194163883-11e63444-74da-4499-884e-13bbf5f50c07.png) 

	+ **Age**: 67 years

	+ **Occupation**:  
	Mechanical Engineer, PHD in Astrophysics and Post Doctorate in Quantum Physics.
Senior Engineer at the National Institute for Space Research INPE.
Currently retired.

	+ **Apps**:  
Netflix; Disney; NET on Demand; Digital TV.

	+ **Motivation**:  
		+ See places I couldn't see in person.
		+  Find movies that marked my life and similar titles.

	+ **Frustration**:  
		+ I won't know if I like a movie until I see it. The engine understands that: why I saw it, I liked it. And recommends similar on my list. And I don't like...

		
	+ **Hobbies, History**:  
		+ When I was young, very few films were produced. Nowadays my children and grandchildren comment on so many films and series to be produced that I get excited.


## User Histories

Based on the information that the Personas presented, the following user stories relevant to the identified problem were concluded.

|I'm as a... `Persona`| Want/Need ... `Funcionalidade` |to/for ... `Motivo/Valor`                 |
|--------------------|------------------------------------|----------------------------------------|
|Rafaela Andrade  | Easily find movies and series that match your personal preferences. | Receive more assertive results according to the suggestion (title, actor, author, etc..) selected by the user.           |
|Rafaela Andrade  | View the poster and information about the movies and series (datasheet) and also see comments from people who have already watched this content. | Watch content based on the opinion of other users. |
|João Arruda Jr.  | Personalized recommendations. | Pick features important to the selection of preference title similarities. |
| João Arruda Jr. | Recommendations made by people. | Increase the chances of finding content in line with user expectations. |
|Graça Silva Dias | Having a streaming user profile that allows you to exchange experiences and information with other users. | Give and receive personal recommendations. |
|Graça Silva Dias | New genre options (categories or subcategories) - content-based movie (tags) | Use important content discussed in movies and series at work. |
|Emídio Conceição | Contents that you have already seen, but did not like, are discarded, not being used in the data to recommend new content. | Actively participate in the data used by security recommendation engines.
|Emídio Conceição | Have a space where the movies and series that you have seen and liked the most are kept. | A list of previously viewed and preferred content is even more important than a wish list of unseen content.

## Requirements

The requirements of a project are its intentions and needs. In general, the requirements of a project are properties that reflect the utilities and functionalities of the project, expectations of its creators and seek to meet the needs of its future users. The requirements are a fundamental part in the structuring of a software project, they are used as abstractions of resources and applicability, helping to form a solid project, creating well-defined purposes and clear objectives. 

### Functional Requirements

The idea of a functional requirement comes from requirements that meet functionality. Functional requirements are actions presented by the project created to meet its requirements.

The following table presents the list of functional requirements for this project, sorted by priority.


|     ID       |     Description                                                                                                                                                                     |     Priority    |
|--------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------|
|     RF-01    |     The site must feature a feature to search for recommended films based on a title (actor, author, director, TAG, etc.) at the user's discretion. | High          |
|     RF-02    |     The user will be able to select TAGS to classify the movies he has already seen. | High        |
|     RF-03    |     The website must obligatorily request the user to register on the platform. | High         |
|     RF-04    |     The site must allow commenting on movies | High |
|     RF-05    |     The site should allow assigning a personal rating to films already seen | High |
|     RF-06    |     The site must present, for each film and series, the possibility for the user to view its poster and information (technical sheet) and comments from those who have already watched it. | Medium         |
|     RF-07    |     The user must be asked whether or not he likes a content when he finishes watching. | Medium     |
|     RF-08    |     The site must allow movie correlation based on user reviews and recommendations. | Medium        |
|     RF-09    |     The site must present a catalog of titles (sites and series) obtained through an API. | Medium        |
|     RF-10    |     The site must maintain the functionality of user profiles, maintaining personalized information for each profile (for example: preferred titles). | Medium       |
|     RF-11    |     The site must present on its main page, personalized recommendations based on each user's profile | Low        |


### Non-Functional Requirements

“The way the system will perform a functional requirement”, this is usually the definition of a non-functional requirement. More broadly, non-functional requirements are functionality that cannot be met by functional requirements.

The following table presents the list of non-functional requirements of this project, scoring their priority.


|     ID        |     Descpription                                                                                                            |     Priority    |
|---------------|--------------------------------------------------------------------------------------------------------------------------|-------------------|
|     RNF-01    |     The website must be compatible with the main browsers on the market (Google Chrome, Firefox, Microsoft Edge). | High         |
|     RNF-02    |     The site must be easy to navigate between your screens | High         |
|     RNF-03    |     The site should be responsive, allowing viewing on a cell phone properly | Medium        |
|     RNF-04    |     The site must be open source | Medium        |


## Restrictions

Restrictions are clear and objective obligations of the project. The following table shows the list of project constraints.

|     ID        |     Description                                                                                           |
|---------------|---------------------------------------------------------------------------------------------------------|
|     RE-01     |     The team may not subcontract the development of the work.                                     |
|     RE-02     |     The site cannot contain knowledge beyond that learned during the semester.                 |
|     RE-03     |     The site may not be used for profit during, or after its development.   |


