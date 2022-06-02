# Purpose

Roots is a microservice that provides the root of each Arabic word along with their meanings from the Quran. The MVP of this service will have a frontend view and an api service that can be used with other applications.


## High-Level Architecture 

Below is the high-level architecture diagram. The process begins by scraping root words from resourceful websites and designated Excel sheets. We parse and organize that content then store it in our database so that Node can retrieve that data. Node then communicates information from the database to Next.js so that it's interactively displayed on the frontend. 

![Roots Architecture Diagram](https://user-images.githubusercontent.com/35634011/171741358-d166ae19-2262-47f4-98fc-906e06bc23ab.png)



