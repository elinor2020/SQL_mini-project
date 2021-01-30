# SQL_mini-project
SQL_mini-project: Use SQL commands to study the country_club database. There are three tables: Bookings, Facilities, Members. The following questions were posed:
Q1: Some of the facilities charge a fee to members, but some do not. Write a SQL query to produce a list of the names of the facilities that do.
Q2: How many facilities do not charge a fee to members?
Q3: Write an SQL query to show a list of facilities that charge a fee to members, where the fee is less than 20% of the facility's monthly maintenance cost. Return the facid (facility ID), facility name, member cost, and monthly maintenance of the facilities in question.
Q4: Write an SQL query to retrieve the details of facilities with ID 1 and 5. Try writing the query without using the OR operator.
Q5: Produce a list of facilities, with each labelled as 'cheap' or 'expensive', depending on if their monthly maintenance cost is more than $100. Return the name and monthly maintenance of the facilities in question. 
Q6: You'd like to get the first and last name of the last member(s) who signed up. Try not to use the LIMIT clause for your solution.
Q7: Produce a list of all members who have used a tennis court. Include in your output the name of the court, and the name of the member formatted as a single column. Ensure no duplicate data, and order by the member name.
Q8: Produce a list of bookings on the day of 2012-09-14 which will cost the member (or guest) more than $30. Remember that guests have different costs to members (the listed costs are per half-hour 'slot'), and the guest user's ID is always 0. Include in your output the name of the facility, the name of the member formatted as a single column, and the cost. Order by descending cost, and do not use any subqueries. 
Q9: This time, produce the same result as in Q8, but using a subquery.
Q10: Produce a list of facilities with a total revenue less than 1000. The output of facility name and total revenue, sorted by revenue. Remember that there is a different cost for guests and members! 
Q11: Produce a report of members and who recommended them in alphabetic surname,firstname order.
Q12: Find the facilities with their usage by member, but not guests.
Q13: Find the facilities usage by month, but not guests 
