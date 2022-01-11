# budget-tracker

### Description
*Giving users a fast and easy way to track their money is important, but allowing them to access that information at any time is even more important. Having offline functionality is paramount to the success of an application that handles users’ financial information*



### app screenshot
![Screen Shot 2022-01-11 at 4 27 26 PM](https://user-images.githubusercontent.com/88847604/149024363-f21cb847-084d-4d21-84e4-1689b8712c82.png)

### App deployed to Heroku
https://polar-earth-36189.herokuapp.com/

### Application Functionalities

- The ability to enter deposits offline.
- The ability to enter expenses offline.
- Offline entries should be added to the tracker when the application is brought back online

### User Story
```text
AS AN avid traveler
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling 
```

### Acceptance Criteria
```text
GIVEN a budget tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated
```
