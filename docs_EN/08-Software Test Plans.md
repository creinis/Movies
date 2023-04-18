# Software Test Plan

The requirements for carrying out software testing are:
- Website published on the Internet
- Internet browser - Chrome, Firefox or Edge
- Internet connectivity to access platforms (APISs)


## Navigability Tests

Its purpose is to verify that all links are navigable, correct and take the user to another existing screen in the application.

Automated tests and manual tests were performed, as follows the results below.

Automated Tests were performed through: https://datayze.com/site-navigability-analyzer

Result:
![Datayze](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e1-proj-web-t4-filmes/blob/main/docs/img/Teste_Navegabilidade_Pipoco.png)

A manual test was also carried out, navigating through the application only to exemplify the manual procedure, since the automated tests were positive and did not present navigability problems in the application.


## Search Screen / Search:
In the Search screen there are the following links to other screens of this application

- In the header, in the central area, there are two links: “Home”, which links the page to the homepage; and “Search” that links the application to the content search area in the application;
- In the header on the right there is an area for the photo of the user logged in with his name. Clicking on the photo opens a navigation menu with the options: “Profile” or “Exit”. When you click on logout, you are directed to the initial login screen. By clicking on “Profile” you will be directed to the user profile screen;
- Just below the header there is the “Search” area for searching content in the application. From the first letter typed in the “Search” area, the search system starts to filter the answer possibilities and automatically presents results in the central / main area of the screen. The result filter is applied to each letter typed until the user finishes typing.
- The results are presented in the form of images with the “Posters” / “Covers” of the titles of series and/or films and these images are links to the details screen of that content;
- When clicking on the image of a content, film or series, you are directed to the details screen of that title. This screen shows: Poster / Cover of the title with the ranking (in stars) just below; on the right there is a Star where the user can “favourite” that title; and in the central area is presented the synopsis of this title, with the information of the same. The “Related” area is displayed in the lower area, that is, an area dedicated to other titles that are related to the user's search result;
- On the details screen of a movie or series title, the same header as on the search screen is also displayed, containing: brand logo; user photo and name, with the possibility of browser menu for areas of: profile or logout; link to “Home” and to “Search”;
  

Result:
All links lead to the expected area or screen.


## Responsiveness Test

Responsiveness tests were automated by Google: Mobile compatibility test
https://search.google.com/test/mobile-friendly?hl=en

Link to results:
https://search.google.com/test/mobile-friendly/result?id=z2V-iNwESInPOrz9Okacew

![Google](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e1-proj-web-t4-filmes/blob/main/docs/img/Teste_Responstividade_Pipoco .png)



The functional tests to be performed on the application are described below.

## Test Plan Login

![Case1](https://user-images.githubusercontent.com/13721147/200649267-96756d94-8f51-4a1a-baab-fd7bb942c621.png)

![Case2](https://user-images.githubusercontent.com/13721147/200649292-b173ec8b-a78e-4df7-8ace-34e26ed9a06f.png)

![Case3](https://user-images.githubusercontent.com/13721147/200648485-7af65b80-9966-4281-8c2a-24c06deb3939.png)

![Case4](https://user-images.githubusercontent.com/13721147/200648626-4cee6164-8329-4dd6-802d-30d604e879bc.png)

![Case5](https://user-images.githubusercontent.com/13721147/200648785-e3710614-6293-4a5f-abc4-c2fbd3c897a7.png)

## Test Plan Search Screen / Search

|Test Case 6| Successful Content Search |
|--------------------|---------------------------- --------|
|Purpose of Test | Check if the search engine delivers the expected result |
|Step 1 | Access the search screen |
| | Enter the name south park, content known to exist in the database|
| | It is expected to receive as a result the title typed in the search field |
| Result | The searched title was delivered in the search result. |

No other observations to present.


|Test Case 7| Unsuccessful Content Search |
|--------------------|---------------------------- --------|
|Purpose of Test | Verify that the search engine delivers consistent results. |
|Step 1 | Access the search screen |
| | Enter the name riqui and morthy, content that is known not to exist in the database|
| | Expected to receive no title as a result. |
| Result | No results were shown. |

No other observations to present.


|Test Case 8| Successful Content Search |
|--------------------|---------------------------- --------|
|Purpose of Test | Check if the search engine delivers the expected result when text is pasted instead of typed. |
|Step 1 | Access the search screen |
| | Paste text into the Search area with the name of the south park title known to exist in the database|
| | It is expected to receive as a result the title entered by eating de liming in the search field |
| Result | The searched title was delivered in the search result. |

No other observations to present.


|Test Case 9| Unsuccessful Content Search |
|--------------------|---------------------------- --------|
|Purpose of Test | Check if the search engine delivers the expected result when text is pasted instead of typed. |
|Step 1 | Access the search screen |
| | Paste a text in the Search area with the name of the title riqui and morthi that is known not to exist in the database|
| | Expected to receive no title as a result. |
| Result | No results were shown. |

No other observations to present.


General Notes for the Search/Search Field:
  - The field has no limitation on the number of characters to be typed or pasted;
  - The field accepts alphanumeric data and special characters


## Test Plan HomePage / Movie Screen
![10](https://user-images.githubusercontent.com/69819769/202446480-9c9ae31a-2697-4f1a-a629-7cbc5340b780.png)
![11](https://user-images.githubusercontent.com/69819769/202447037-78d4d28e-5127-4421-99e1-c66183b4a3dd.png)
![12](https://user-images.githubusercontent.com/69819769/202447063-0145df36-1413-41b3-98f0-562d026f247a.png)

## Test Plan Registration Screen
|Test Case 10| Incorrect completion of the form |
|--------------------|---------------------------- --------|
|Purpose of Test | Check if, based on the data provided, the functionality of registering the user is not possible to complete |
|Step 1 | Access the register page |
|Step 2 | Fill in the data incorrectly, for example: name: vitor - email: vitor@gmail.com - password: 1234 - password confirmation: 4321 |
|Step 3 | Click on the "register" button |
| Result | When clicking on the "register" button, the program should not create a profile for the user and should indicate which field is incorrect |


|Test Case 11| Correct completion of the form |
|--------------------|---------------------------- --------|
|Purpose of Test | Check if, based on the data provided, the functionality of registering the user is possible to complete |
|Step 1 | Access the register page |
|Step 2 | Fill in the data correctly, for example: name: vitor - email: vitor@gmail.com - password: 1234 - password confirmation: 1234 |
|Step 3 | Click on the "register" button |
| Result | When clicking on the "register" button, the program should create a profile for the user and redirect him to the login page |


## Test Plan Profile Screen

|Test Case 12| Change profile picture |
|--------------------|---------------------------- --------|
|Purpose of Test | Check if the user has the possibility to change their profile picture |
|Step 1 | Access profile page |
|Step 2 | Click Profile Photo |
|Step 3 | Click on the "upload" button |
|Step 4 | Select an image from computer |
|Step 5 | Click "OK" |
| Result | The site must edit the user's profile, updating their profile picture and also the preview picture in the header |

|Test Case 13| Change profile banner |
|--------------------|---------------------------- --------|
|Purpose of Test | Check if the user has the possibility to change the banner of his profile |
|Step 1 | Access profile page |
|Step 2 | Click profile banner |
|Step 3 | Click on the "upload" button |
|Step 4 | Select an image from computer |
|Step 5 | Click "OK" |
| Result | The site must edit the user's profile, updating the page banner |


|Test Case 14| Edit Profile Name |
|--------------------|---------------------------- --------|
|Purpose of Test | Check if the user has the possibility to change his name on the user page |
|Step 1 | Access profile page |
|Step 2 | Click profile username |
|Step 3 | Enter a New Username |
|Step 5 | Click "OK" |
| Result | The site must edit the user's profile, updating the username on the page and header preview |


|Test Case 15| Edit User Bio |
|--------------------|---------------------------- --------|
|Purpose of Test | Check if the user has the possibility to change his biography on the user page |
|Step 1 | Access profile page |
|Step 2 | Click on Bio |
|Step 3 | Enter a new bio |
|Step 5 | Click "OK" |
| Result | The site must edit the user's profile, updating the user's bio on the page |
