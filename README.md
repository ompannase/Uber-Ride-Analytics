# Uber Ride Analytics Dashboard

## Dataset
The Uber Ride Analytics Dashboard dataset contains detailed records of Uber rides booked in the NCR (National Capital Region). It captures information about ride requests, completions, cancellations, ride distances, booking values, and customer/driver behavior.

Key columns include:

Date – The date when the ride was requested.

Time – The time of the ride request.

Booking ID – Unique identifier for each ride booking.

Booking Status – Status of the ride (e.g., Completed, Cancelled, No Cars Available).

Customer ID / Driver ID – Unique identifiers for riders and drivers.

Vehicle Type – Type of vehicle requested.

Pickup Location / Drop Location – Starting and ending points of rides.

Booking Value – Price of the ride in local currency.

Ride Distance – Distance covered during the ride (in km).

Driver Ratings / Customer Ratings – Ratings given by drivers and customers.

Payment Method – Mode of payment (Cash, UPI, Card, Wallet, etc.).

Cancellation Reasons – Reason provided for ride cancellations (by customer or driver)

## Visualizations
- Bar plot: Rides per day of week
- Bar plot: Rides per hour
- Box plot: Booking value
- Violin plot: Ride distance
- KDE plot: Booking value
- Swarm plot: Payment method vs Booking value

## Insights
1. Peak demand occurs on weekdays and rush hours.
2. Booking values are skewed, with some high-value rides.
3. Ride distances mostly short-to-medium, few long trips.
4. Payment method trends show higher values for non-cash payments.

## Images
![Bar Plot](images/plot.png)
![Box Plot](images/plot3.png)
