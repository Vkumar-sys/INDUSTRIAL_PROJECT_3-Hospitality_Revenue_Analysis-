# INDUSTRIAL_PROJECT_3-Hospitality_Revenue_Analysis-
# Problem Statement:-
✔AtliQ team took some ineffective decision in their past and on the other hand other competetors in hospitality industry,
  getting success in market and making high revenue due to their strategic moves.AtliQ team wanted to regain their 
  revenue and market shares.
  
✔AtliQ has no inhouse data and business analyst team that provide them these insights.

✔So they planned to hire data analyst or business analyst that provide them useful insights from the historic data.

# Dataset Used:-
✔We have 5 csv files having 3 dimension and two fact tables.
1. dim_date
2. dim_hotels
3. dim_rooms
4. fact_aggregated_bookings
5. fact_bookings


Column Description for dim_date:
1. date: This column represents the dates present in May, June and July.
2. mmm yy: This column represents the date in the format of mmm yy (monthname year).
3. week no: This column represents the unique week number for that particular date.
4. day_type: This column represents whether the given day is Weekend or Weekeday.



Column Description for dim_hotels:
1. property_id: This column represents the Unique ID for each of the hotels.
2. property_name: This column represents the name of each hotel.
3. category: This column determines which class[Luxury, Business] a particular hotel/property belongs to. 
4. city: This column represents where the particular hotel/property resides in.



Column Description for dim_rooms:
1. room_id: This column represents the type of room[RT1, RT2, RT3, RT4] in a hotel.
2. room_class: This column represents to which class[Standard, Elite, Premium, Presidential] particular room type belongs.


Column Description for fact_aggregated_bookings:
1. property_id: This column represents the Unique ID for each of the hotels.
2. check_in_date: This column represents all the check_in_dates of the customers.
3. room_category: This column represents the type of room[RT1, RT2, RT3, RT4] in a hotel.
4. successful_bookings: This column represents all the successful room bookings that happen for a particular room type in that hotel on that particular date.
5. capacity: This column represents the maximum count of rooms available for a particular room type in that hotel on that particular date.



Column Description for fact_bookings:
1. booking_id: This column represents the Unique Booking ID for each customer when they booked their rooms.
2. property_id: This column represents the Unique ID for each of the hotels
3. booking_date: This column represents the date on which the customer booked their rooms.
4. check_in_date: This column represents the date on which the customer check-in(entered) at the hotel.
5. check_out_date: This column represents the date on which the customer check-out(left) of the hotel.
6. no_guests: This column represents the number of guests who stayed in a particular room in that hotel.
7. room_category: This column represents the type of room[RT1, RT2, RT3, RT4] in a hotel.
8. booking_platform: This column represents in which way the customer booked his room.
9. ratings_given: This column represents the ratings given by the customer for hotel services.
10. booking_status: This column represents whether the customer cancelled his booking[Cancelled], successfully stayed in the hotel[Checked Out] or booked his room but not stayed in the hotel[No show].
11. revenue_generated: This column represents the amount of money generated by the hotel from a particular customer.
12. revenue_realized: This column represents the final amount of money that goes to the hotel based on booking status. If the booking status is cancelled, then 40% of the revenue generated is deducted and the remaining is refunded to the customer. If the booking status is Checked Out/No show, then full revenue generated will goes to hotels.

# Tools and technique used:-
✔ Data Gathering using power bi desktop.

✔ Data Modelling and building the required relationship between the tables for effective visualisation using the power 
  bi desktop data modelling interface.

✔ Data Cleaning and Transformation using the Power Query Editor inside the power bi desktop.

✔ Building the measures and calculated columns using DAX formulaes.

✔ Building the dashboards using the Power Bi Desktop in the report view interface.

# Key Metrics Used:-

✔This dashboard attached above in the files section contains level one,level two and key level deep metric analysis .
  By this dashboard we can analyze the Revenue,Occupancy %,RevPar(Revenue per Available Room),ADR(Average Daily Rate),
  DSRN(Daily Sellable Room Nights) and Realisation.These are top level metrics which tells the revenue generated by 
  hotels.

✔ We can also cover some metrics like Checked Out Rate,Cancellation Rate,No Show Rate,DURN(Daily Utilized Room Nights),
   DBRN(Daily Booked Room Nights),Average Rate,Total Bookings which tells the booking and performance details
   of hotels.

# Key_Insights:-
✔ Level_1_Analysis:-
  ✔ In terms of Revenue by city Mumbai tops the list with  Mumbai having the most revenue at 0.67 billion and Delhi 
    being at bottom at 0.29 billion.

  ✔ In terms of Occupancy % by city Delhi tops the list with 60.55 % Occupancy and Bangalore is at the bottom among 
    the four available cities with 55.77 % Occupancy.

  ✔ In terms of Average rating by the city Delhi receives the highest rating of 3.8 on an average out of 5.

  ✔ In terms of total bookings Weekdays have more bookings standing at 69.41 % and weekends have 30.59 % it indicates 
     there is more occupancy on Weekdays as apart from commercial customers we have professional customers too
     who take the accomodation when they are on a work tour.

  ✔ In terms of Occupancy % Weekends has more Occupancy compared to Weekdays but slighty on a lower note.

  ✔ In terms of Cancellation % there is a fifty % share in both the day type on approx.

✔ Level 2 Analysis:-

  ✔ In level 2 analysis we will dive a bit deep on the detailed metrics for the hospitality domain and see its 
     performance.
  
  ✔ In terms of revenue share we can see that luxury category contributes more to the revenue as compared to the 
     business category so we can tweak the areas lacking performance and look for better performance to get a better
     share on market.

  ✔ If we see our key metrics RevPar,ADR,Occupancy % trend of 3 months on weekly basis we see that occupancy is 
     fluctuating which might be possible but the ADR is fixed so we can assume that hotels have fixed or flat pricing.

  ✔  In hospitality Industry average rating and occupancy % are directly dependent upon each other so not much more         pricing so we have to focus on our services,hotel management and employees behaviour to get better and higher 
      ratings.
      
  ✔  In terms of few more metrics like DBRN(Daily Booked Room Nights) which tells how many rooms are booked for a day 
      considering a given time period,DSRN(Daily Sellable Room Nights) which tells how many rooms are ready to sell 
      for a day considering the time period,DURN(Daily utilized Room Nights) tells that how many rooms are utilized
      for a day considering the given time period we see that there is a dip in DURN as compared to DSRN and DBRN for 
      each week of various months so this is an important insight that needs to be looked into from the hospitality 
      domain to make it at par level.

  # Acknowledgements:-

  ✔ A very sincere and humble thanks to entire codebasics team for providing such a good challenge as part of their
    resume project challenge 1 where we get to understand the thorough life cycle of a data analytics project and the 
    key steps involved at each level and enhancing the domain knowledge too of our hospitality industry.

  # Codebasics Team # Resume Project challenge.



  


  

