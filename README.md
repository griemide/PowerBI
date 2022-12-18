# PowerBI
Power BI applications

## Wiki
Hints and guides for Raw Data handling, Measure examples, Used DAX fuctions, ecetera) - [Wiki in German language only](https://github.com/griemide/PowerBI/wiki)

## Measure (examples)

**New Table**  
```MeasureTable = Row("Author", "Michael Gries", "Contact","https://github.com/griemide/PowerBI")```  

**Google Lat, Lon:** 50.877044143876574, 9.691222909776272  
```Breitengrad = LEFT(Address[Google Lat, Lon],SEARCH(",",Address[Google Lat, Lon],1)-1)```    
```Längengrad = RIGHT(Address[Google Lat, Lon],LEN(Address[Google Lat, Lon])-FIND(",",Address[Google Lat, Lon]))```    

## Private Power BI reports and datasets
see [PowerBI-Berichte](https://github.com/griemide/PowerBI-Berichte)

## References  

### DAX-Referenz (Data Analysis Expressions)
Microsoft [Dokumentation](https://learn.microsoft.com/de-de/dax/) (german)  

### Blog [Connect Power BI to a Private GitHub Repo](https://smootherconsulting.com/learn/connect-power-bi-to-private-github-repo) by Mark Hoover  
**Blog Summary:**  
Connecting Power BI to a private GitHub repo is super easy. The key differences are:  
* Use the basic authentication method instead of anonymous.  
* Use the GitHub account email as the user name.  
* Use the personal access token as the password.

https://youtu.be/kP2g0D1PYqg


Video [DAX](https://learn.microsoft.com/de-de/dax/)  - by Microsoft
Video [Microsoft Power Bi Architektur](https://youtu.be/kP2g0D1PYqg)  - by consultNetwork
[]() 
[]() 
[]() 
[]() 
[]() 
