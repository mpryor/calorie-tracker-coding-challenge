# Calorie Tracker Coding Challenge

For this coding challenge, you will be implementing the backend API for a hypothetical calorie tracking application. It is strongly recommended that you use Java with Spring to accomplish this. 

You will be turning in a list of RESTful endpoints with descriptions of each, and the code for the API.

The requirements of the API are as follows:
1. The API must use JSON as a representation of resources
2. As an end-user, I need to be able to retrieve a list of foods with their nutrition information, for example:
```
[
   {
      "id": "1",
      "name": "apple", 
      "calories": 50
   },
   {
      "id": "2",
      "name": "cheeseburger",
      "calories": 400
   }
]
```
3. As an end-user, I need to be able to search for foods within a calorie range.
4. As an end-user, I need to be able to add foods to my daily total/log
5. As an end-user, I need to be able to remove food from my daily total/log
6. As an end-user, I need to be able to view my daily total/log with information about calorie totals, for example:
```
{
  "date": "01/01/2018",
  "total": "450",
  "entries": [{
    "id": "1",
    "foodId": "1",
    "name": "apple",
    "calories": 50
  },
  {
    "id": "2"
    "foodId": "2",
    "name": "cheeseburger",
    "calories": 400
  }]
}
```
7. As an "admin", I need to be able to add new foods.
8. As an "admin", I need to be able to remove foods.

The data for the nutrition information may be sourced from wherever you want. (an embedded database, hard-coded, a text file, or an external API like MyFitnessPal for example)  

The API spec for this challenge is intentionally left vague, so that we can see how you design/implement an API to fulfill this requirements.  

## How the challenge will be graded.

The following points will be taken into consideration when grading:

- Functionality / Requirement fulfillment (does the API serve all the needs of the user / fulfill all 8 requirements?)
- Design/Architecture of the Code (OOP / patterns / best practices )
- Design of the API itself
- Code readability (variable names / comments / etc)

## How to submit 
1. Send us your GitHub ID.
2. We will create a private repository and add you as a contributor to it. 
3. Copy over the challenge-review.txt from this repository, add it to yours, and fill it out.
4. Commit your code to the repo.
5. Notify us when complete.

## BONUS points:

Design a simple UI that consumes the API you wrote, allowing the user to create their daily log. 
