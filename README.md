# Calorie Tracker Coding Challenge

For this coding challenge, you will be implementing the backend API for a hypothetical calorie tracking application. It is strongly recommended that you use Java with Spring to accomplish this. 

You will be turning in a list of RESTful endpoints with descriptions of each, and the code for the API.

The requirements of the API are as follows:
- The API must use JSON as a representation of resources
- As an end-user, I need to be able to retrieve a list of foods with their nutrition information, for example:
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
- As an end-user, I need to be able to search for foods within a calorie range.
- As an end-user, I need to be able to add foods to my daily total/log
- As an end-user, I need to be able to view my daily total/log with information about calorie totals, for example:
```
{
  "date": "01/01/2018",
  "total": "450",
  "foods": [{
    "id": "1",
    "name": "apple",
    "calories": 50
  },
  {
    "id": "2",
    "name": "cheeseburger",
    "calories": 400
  }]
}
```

The data for the nutrition information may be sourced from wherever you want. (an embedded database, hard-coded, a text file, or an external API like MyFitnessPal for example)  

The API spec for this challenge is intentionally left vague, so that we can see how you design/implement an API to fulfil this requirements.  


### BONUS points:

Design a simple UI that consumes the API you wrote, allowing the user to create their daily log. 
