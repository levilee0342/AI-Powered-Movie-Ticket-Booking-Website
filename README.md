# Movie Ticket Booking Website and Chatbot

## Project Description

The "Movie Ticket Booking Website" project is an online platform that allows users to easily book movie tickets. In addition to the booking functionality, the system also integrates an **intelligent chatbot** that assists users with movie schedules, film details, and special offers.

### **Demo** : 
    You can check out the project demo at:
#### **Screenshots**

##### 1. Homepage
![image](https://github.com/user-attachments/assets/0a88b697-958f-4849-b83a-0e50be4c6ec8)

##### 2. Ticket Booking Feature
![image](https://github.com/user-attachments/assets/f4bcfcc8-f2f1-468d-a2a2-2b7ff98b9bb5)

##### 3. Chatbot Assistant 
![image](https://github.com/user-attachments/assets/e49ac3f7-5e5e-4776-b7f8-5c8d48d5cbe8)

##### 4. Movie Management (Manager)
![image](https://github.com/user-attachments/assets/c9099e97-166a-4a88-8f51-24c31a088638)

##### 5. Schedule Management (Manager)
![image](https://github.com/user-attachments/assets/63b1d2b0-62a6-43c8-b0a8-11a8a67c80ae)

### Key Features:

**For Customers:**

- **Online ticket booking**: Users can select a movie, showtime, and seat, then proceed to payment and receive their tickets.
- **View movie information**: Displays detailed information about currently showing and upcoming movies.
- **View schedule**: Shows the movie schedule for a given period.
- **Chatbot support**: The AI-integrated chatbot answers frequently asked questions about movies, schedules, usage instructions, and customer support. It can also recommend popular movies based on user preferences.

**For Administrators:**

- **Manage general information:** Edit basic information about the cinema.
- **Manage movies and schedules:** Add new movies and create showtimes for the cinema.
- **Manage tickets:** Issue various types of tickets and adjust prices.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Java
- **Chatbot**: Python, ChromaDB
- **Database**: SQL Server
- **Chatbot Framework**: Flask, TensorFlow & Keras
- **Others**: Apache Tomcat, NLTK, Pickle, NumPy
- **Tools**:
  - **Eclipse IDE**: Used for developing the movie ticket booking website.
  - **PyCharm**: Used for developing the chatbot.
  - **SQL Server Management Studio**: For data queries, transactions, and enforcing constraints.
## Installation and Usage

Clone the project from GitHub:

```bash
https://github.com/levilee0342/AI-Powered-Movie-Ticket-Booking-Website
```
### Website Setup

Using Eclipse

1. **Install required libraries**:
    - The libraries are already integrated into the project.
    - Use jdk 17.0.11 and Tomcat 9.
2. **Configure the database** in: `TicketBookingWebsite/src/main/webapp/WEB-INF/configs/spring-config-hibernate.xml`
3. **Run the website application**:
    - Run using the Eclipse interface.

### Chatbot

1. **Install required libraries**:
    - Using Python 3.9 
    - Install libraries such as `ChromaDB`, `Flask`
    - [requirements.txt](https://github.com/user-attachments/files/18357355/requirements.txt)
    ```bash
    pip install -r requirements.txt
    ```

3. **Configure the database** in:
    `TicketBookingWebsite/src/main/webapp/WEB-INF/configs/spring-config-hibernate.xml`

4. **Run the backend application**:

    ```bash
    python app.py
    ```

## Example Usage

1. Open the website and search for the available movies.
2. Choose a movie and book a ticket based on the schedule.
3. If you have any questions about usage, chat with the chatbot via the chat window.

## Try It Out

1. Visit the website at [Home](http://localhost:9999/DoAnWebCinema/).
2. Search for a movie, select a schedule, and proceed with booking.
3. Use the chatbot to ask for movie schedule details.

## Thank You!

Thank you for your interest in my project. Please feel free to reach out to me via email at [leetuan0342@gmail.com](mailto:leetuan0342@gmail.com) if you have any questions regarding this project.
