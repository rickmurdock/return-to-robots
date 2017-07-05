# Return to Robots

The Iron Yard Daily Project: Return to Robots

Using the MongoDB Node library, create the LinkedIn for Robots project.

In week 1 of Back-End Fundamentals, you built [a directory site with job and skill information for robots](https://github.com/rickmurdock/Create-User-Directory).

Today, you should download the same data you used in that project. The download link is included here.

> [data.js](https://tiy-learn-content.s3.amazonaws.com/36d3402e-data.js) (23 KB)

Load this data into MongoDB and rebuild the directory site. You will have to query the database via the `MongoDB library` (mongodb) to get this data.

This time, add links at the top of the page to go to a page of robots that are currently looking for work and a page of robots that are currently employed.

### Hard mode

If you are up to it, make countries and skills into links that will take you to a page that only shows robots from that country or have that skill.

If you want to generate more or different data, you can use the following command to get 20 more robots:

```
curl "http://api.mockaroo.com/api/3126f3c0?count=20&key=310fb5e0"
```
