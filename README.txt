How to use the API:
1. Download the HTMLCleaner library from http://htmlcleaner.sourceforge.net/ and add it to your project's build path.
2. Add the WikiOnThisDay.java file to your project
3. To retrieve data from Wikipedia, simply create a new object of the WikiOnThisDay class by passing the month and date (1 is for January, 2 is for February...).
4. You can then retrieve the entire data from the getEntireData() function, the birthdays from the getBirthdays() function, deaths from the getDeaths() function and events from the getEvents() function.

Credit to Colin Mitchell (http://muffinlabs.com) whose Really Simple History API (https://github.com/muffinista/really-simple-history-api/) project I used prior to developing this. 
The JSON return structure in this project is the same as his work so as to simplify porting, if required. 