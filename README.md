While I was working on Harding Township NJ, Historic Preservation Committee, there were many new homeoners that were unaware 
of the rules govening modifications to houses that are classified as historic. There were many peple that arrived to the 
committee very upset. I was tasked with creating a program that would locate the historic properties for sale in Harding so
that we could inform real estate agents and the listing agent of the historical nature of the property.

Finding a reliable and inexpensive source for the properties for sale in Harding sounds somewhat easy but it turns out it's not. 
There are many sources of free information about a specific property for SOLD properties but only multiple listing service (MLS) data 
has information about properties for sale. I found out that there is not one but many MLS sources that are owned by many different organizations. 
After much searching, I found https://rapidapi.com/apidojo/api/realtor. It’s well supported and the price is free for a low volume of API calls. 
You need to sign up here https://rapidapi.com. I picked the free option (<= 500 API calls/month) since I’ll be making less than 500 API 
calls/week in production. 

This programs finds the historic houses in Harding then sends email to the appropiate people and posts this to a web site as a dated blog.

