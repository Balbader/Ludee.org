# Ludee.org
[The Hacking Project](https://www.thehackingproject.org/) Bootcamp Final Project Presentation

Welcome and thank you for taking the time to check us out ^^ <br>

The following is our final project presentation for what we believe is an amazing idea. <br>

We truly hope that this presentation will create in you the desire to follow us in crafting an amazing solution <br>
to one of the greatest problems ever encountered by students, specially in the actual health crisis: STUDENT LOANS! <br>

## Problem
Following a study by [l'Unef](https://unef.fr/) and [l'Observatoire National de la Vie Etudiante](http://www.ove-national.education.fr/situation-economique-et-financiere-des-etudiant%c2%b7e%c2%b7s-de-nouvelles-donnees-disponibles-2/), there is between 200 and 300 thousands students that seeks a student loan to finance their post-bac studies. This amounts to about 10% of the student population of the country. <br>
Adding to that the current economic crisis due to the pandemic, earning money is harder than ever. <br>

## Our Solution
Welcome to Ludee.org <br>
The Crowdfunding Quiz Game to help students pay off their student loan and <br>
earn some cash on the side. <br>
Ludee.org is a not for profit organization created with the sole purpose of helping students pay off<br>
their student loans while playing a fun quizz game and win weekly awards. 90% of the generated income on Ludee goes directly to our users,<br>
while 10% is used to operate the Ludee platform, less banking and process charges.<br>

## Our Team
* Janaina Figueira
* Youssef Annabi
* Charles Campet
* Basil Albader
* Yann Rannou (TBC)

## Mentor
We are currently actively looking for a Knowledgable mentor to join our team. <br>
If you like our project and would like to get in on the fun, drop me a message on discord you are a Corsair or Alumni @Basil#2377<br>
Or reach me @: basilalbapro@gmail.com

# The Idea

## Description of the game
Like life, Ludee is a team game.

1. At the beginning of each game, you get matched with 2 random player.
2. You independently answer general-purpose trivia statements True or False within a 10-second time limit.
3. Rack up as many points as you can. The game is over after three incorrect answers.
4. A game lasts 7 days. This is called the inner cycle.
5. At the end of each inner cycle, the team with the highest points count wins the weeky money prize.
<br>
How do we pay off student loans?<br>

1. Every student that signs up on Ludee has the oportunity to enter the Student Loan Fund.
2. For that, simply fill in the justification form and once your form is validated by out staff, you will be added to the queue.
3. The loans are added in chronological order, this means that the loans with the shortest dead line gets on top of the list.
4. A loan is paid off completely if it is under 25k else, your loan will receive a maximum of 25k before switching to the following.
<br>

How do you pay off loans?<br>
There is a 10 euros/month subscription fee to use Ludee. The money is split as follow: <br>

For the following example, we will take a base of 10,000 euros: <br>
1. Every month, the money is split 3 ways.
2. 50% goes to the Student Loan Fund, 40% goes to the weekly prizes and the remaining 10% goes to Ludee (in order to run the platform..
3. The Student Loan Fund is filled up every month until it either reaches the amount of the student loan in the current funding cycle or 25k.
4. Once one of both cases is met, the loan on the current funding cycle is payed.
5. After payment of the current student loan, a new funding cycle is launched and the next student loan on the list becomes takes the top spot. 

# Structure of the platform
The structure of the platform is still in R&D state but here are the big lines: <br>
Ludee will be comprised of 3 main models: <br>
* Users
* Game
* Payment

# Main Features
## Users
* Sign Up / Login 
* User profile/User logged in (profile picture, User basic info, Inner Cycle Dashboard, Settings Dashboard)

## Game
* Game page (user logged in): same for all users
* Game status (User team score, User game status)

## Payment

* Implementation of Stripe connect for every user in order to pay them
* Implementation of Student Loan Fund

# Optional
* Implementation of "Pay to Play" feature for non logged in Users

# Tech (in progress and to be confirmed)
* Rails 6
* Ruby
* Devise
* PostgreSQL
* Mailer
* Stripe
* Bootstrap
* html
* CSS
* JS...

# Mockup
![Mockup](Mocup/Ludee\ Home\ Page.png)
