This table in the database has one row per city where a totality is going to happen. Naturally, some rows will pertain to past totalities as time moves beyond them.

The columns:

Date: The date on which the totality will happen. People planning a trip during totality can know one what day they need to be in that city. Note that this column can be used as a unique identifier of the eclipse since two eclipses can never happen on the same day. Type: datetime.
City: The city where the totality is happening. Even if only a part of the city is going to be inside the totality shadow, it qualifies. Once in the city, its relatively easy to move around and get to the right spot. The date and city together uniquely identify a record. Type: string.
State: The state in which the city lies (example: Dallas lies in Texas). Type: string.
Country: Self explanatory. Type: string.
Comments: Some subjective comments about the event. For example, some cities are listed as having the location of the longest totality in that specific eclipse month. Type: string.
Reference: The source for the data. For instance, I found an article detailing the 2026 and 2027 eclipses in Spain and schematized a bunch of the information there. I'm hoping others can do the same as they find articles online since most data on the different totalities tends to appear in this unstructured form online. Type: string.
TotalitySecs: The duration of the totality in seconds. Type: integer.
TotalityStart: The start time of the totality. Type: datetime.
TotalityEnd: The end time of the totality. Type: datetime.
ClearProbability: The subjective probability the sky will be clear at the time of the totality (at the time of data entry). This is the subjective opinion of the person entering the data, supposed to be grounded in various weather models. For totalities in the past, we already know if it was clear enough or not. And this number should ideally be updated once that happens. Type: integer.
WeatherScore: Another subjective score. On a scale of 1 to 10, how cooperative the weather is. Note that this is distinct from weather or not the totality will be visible. A great example is Dallas 2024. Most weather models were showing a mostly cloudy sky at the time of the totality. And indeed, on the day of the eclipse, it was overcast all morning. And then, around the time of the totality (about 2:50 PM), the clouds magically cleared and people were able to see it. So even though it worked out in the end and the probability of seeing the totality is now 100%, it could have played out differently far too easily. For that reason, I gave it a weather score of 6 out of 10. Type: integer.
DateLogged: The date on which the entry was logged. Type: datetime
AddedBy: The Github username of the person logging the entry. We'll get into why Github later. Type: string.
