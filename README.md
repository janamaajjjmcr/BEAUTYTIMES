# BEAUTYTIMES
Android salon booking app built with Java and SQLite


# BeautyTimes — Salon Booking App

BeautyTimes is an Android salon booking application developed using **Java**, **Android Studio**, and **SQLite**. The app allows users to register, log in, browse salon services, book appointments, and view their upcoming bookings in a simple and user-friendly interface.

## Features

- User registration and login
- Browse salon services
- Display services using RecyclerView and CardView
- Select appointment date using DatePickerDialog
- Select appointment time using TimePickerDialog
- Save bookings locally using SQLite database
- View service details and prices
- View upcoming bookings in “My Bookings” screen
- Toast messages for user feedback
- Clean and simple mobile UI

## Technologies Used

- Java
- Android Studio
- SQLite
- RecyclerView
- RecyclerAdapter
- CardView
- ConstraintLayout
- ScrollView
- Dialog Windows
- Toast Messages

## App Screens

The application includes the following main screens:

1. Login Screen  
2. Registration Screen  
3. Main Services Screen  
4. Date Selection Dialog  
5. Time Selection Dialog  
6. About / Prices Screen  
7. My Bookings Screen  

## Database

The app uses SQLite with three main tables:

- `users` — stores user account information
- `services` — stores salon services, duration, and prices
- `appointments` — stores user bookings with date and time

## Main Services

The app currently includes these salon services:

- Haircut
- Nail Art
- Blowout
- Color
