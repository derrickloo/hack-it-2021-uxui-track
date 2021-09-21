# ocbc-hackit2021-uxui-track
This repository contains my proposed solution for the UX/UI track of OCBC HACK-IT challenge 2021.

**Scope of Assignment**
- Create Hi-fi mockups of a mobile application that allows users to book a seat in a movie theatre, with authentication required (email and password) before finalising the booking.
- This assignment aims to create a fully functional mobile app mockup.

**App Functionality (expected but not limited to)**
A work in progress design is what we are looking for here; however, the idea of this challenge is to get some insight on how you work, your design ability and see how you realise your ideas.

**User Flow Steps:**
- A user selects a movie to book;
- A user chooses a seat(s);
- A user finalises the purchases;
- A user provides personal/ booking details ( You don't need to gather
payment details);
- A user completes the transaction and gets confirmation.

**Solution:** 
- From Loading: 
https://www.figma.com/proto/1SJzxxOeD2Atf3iFE5Oxoy/Mighty-Movie-Booking-App?page-id=1%3A2&node-id=616%3A9535&viewport=241%2C48%2C0.22&scaling=scale-down&starting-point-node-id=616%3A9521&show-proto-sidebar=1

- From Sign-In to Order Confirmation:
https://www.figma.com/proto/1SJzxxOeD2Atf3iFE5Oxoy/Mighty-Movie-Booking-App?page-id=1%3A2&node-id=652%3A17268&viewport=241%2C48%2C0.22&scaling=scale-down&starting-point-node-id=652%3A17268&show-proto-sidebar=1

**Key Points of my Solution**
- My solution allows users quick movie selection based on the 3 criteria: movie name, cinema and date. System will bring user to the timing page directly according to the user's selections. This is for users who already know what to watch, where to watch it and probably when. It can detect the user's location and suggest the nearest cinema.
- After selecting a timing, system will automatically select the best available seats for the users, thus saving time for the users. They can change the selection if necessary. The seating arrangement is a section that allows users to pan left/right & up/down. Most of the app will display the seating for the entire cinema, making them very small and prone to accidental tapping of the wrong seating.
- When logging in, if the user forgets their password, instead of resetting the password, the system allows users to use a 6-digit one-time code to login. Reducing time to complete the booking process.
- At the homepage, the users may filter the movies granularly by their rating (PG, M18, R21, etc), genre (action, adventure, romance, etc) and language (English, Chinese, Korean, etc...)
