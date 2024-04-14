eclipse chasers have to contend with is demand inflation. On the one hand, we want to share this unique experience with others and spread awareness about it. On the other, demand for everything from flights to hotels to cars increases considerably during such events (and so do the prices) and this demand will get worse if more people know about it. In extreme cases, the thing you want to book might even become completely unavailable and this could make the whole trip infeasible. The thing I learnt is that rental cars are the most susceptible to this kind of inflation and hotel stays are the least.

I decided to share data on all of my bookings for the two totalities I've witnessed (2017 and 2024) in this second table, Eclipse_expenses. Its rows are all the bookings I made that were necessary for the trips, when I made the bookings, the prices I paid, etc.

The columns are described below:
1) EclipseDate: The date of the total solar eclipse the booking was made for. This uniquely identifies the eclipse since two can never happen on the same day. Type: datetime.
2) Location: The location where the booking originated. Type: string.
3) Item: Description of the booking. Type: string.
4) Price: Price paid for the booking. Type: float.
5) Currency: The currency in which the price was paid. Type: string.
6) Vendor: Name of the vendor who provided the service. Type: string.
7) Comment: Any comments on the booking. Type: string.
8) BookingDate: When the booking was made. This will give an idea of how far in advance bookings are typically made and how that affects prices. Type: datetime.
9) StartTime: When the booking started. Type: datetime.
10) EndTime: When the booking ended. Type: datetime.
11) DataLogged: When the data was logged. Type: datetime.
12) AddedBy: The Github username of the person adding the entries. Type: string.
