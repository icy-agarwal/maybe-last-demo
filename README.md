# maybe-last-demo

CREATE DATABASE owner;
USE owner;

CREATE TABLE book (
    book_id INT PRIMARY KEY,
    title VARCHAR(50),
    author VARCHAR(30),
    price DECIMAL(8,2),
    availability INT
);


INSERT INTO book (book_id, title, author, price, availability) VALUES
(1001, 'Home and the World', 'Rabindranath Tagore', 150.00, 10),
(1002, 'No Mans Nightingale', 'Ruth Rendell', 450.00, 8),
(1003, 'Hind Swaraj', 'Mahatma Gandhi', 700.00, 10),
(1004, 'Trouble in Paradise', 'Robert B. Parker', 1050.00, 5),
(1005, 'Dharmayoddha Kalki', 'Kevin Missal', 700.00, 12),
(1006, 'Satyayoddha Kalki', 'Kevin Missal', 850.00, 15),
(1007, 'To Kill a Mockingbird', 'Harper Lee', 350.00, 11),
(1008, 'Atomic Habits', 'James Clear', 450.00, 15),
(1009, '1984', 'George Orwell', 850.00, 4),
(1010, 'The Alchemist', 'Paulo Coelho', 850.00, 4);

CREATE TABLE event (
    event_name VARCHAR(50),
    event_date DATE,
    no_of_tickets INT,
    author VARCHAR(50),
    timing varchar(50)
);

INSERT INTO event (event_name, event_date, no_of_tickets, author, timing) VALUES
('Art Exhibition', '2024-11-15', 100, 'Alice Smith', '10:00:00'),
('Music Concert', '2024-12-01', 250, 'The Band', '19:30:00'),
('Book Launch', '2024-11-20', 50, 'John Doe', '17:00:00'),
('Food Festival', '2024-10-10', 300, 'Culinary Masters', '12:00:00'),
('Tech Conference', '2024-11-05', 200, 'Innovate Tech', '09:00:00'),
('Theater Play', '2024-12-15', 150, 'Local Theater Group', '18:30:00'),
('Charity Gala', '2024-11-25', 75, 'Helping Hands', '20:00:00');
