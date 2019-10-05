OrderDatabaseLayoutDraft.xlsx	
    draft for holding ALL orders at the given restaurant for analytics and recordkeeping.

restaurantinfodbdraft.xlsx	
restaurantinfodbdraft.png	
    This is the draft for how we would hold information for each of our clients(restaurants)
    The PNG file is just a snapshot i took in case anyone didn't want to open it in Excel.

sampleOrder.json
    draft for how each Order information will be created and stored for daily operations.
    
    
For now, restaurantinfodbdraft and OrderDatabaseLayout is not connected. I'm thinking this can easily be fixed
if we format it as (restaurantid).(restaurantbranchid).(orderID).

First and 2nd would be from restaurantinfodb and the orderID stuff would be from the orderdatabaselayout.
