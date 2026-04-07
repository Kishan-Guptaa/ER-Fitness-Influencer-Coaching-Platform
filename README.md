# ER-Fitness-Influencer-Coaching-Platform
This repository contains the ER Diagram for a Fitness Influencer Coaching Platform designed as part of the Web Dev Cohort 2026 – Database Assignment.

The purpose of this database design is to support an online coaching system where trainers manage clients, sell plans, schedule sessions, track progress, and review check-ins.

📌 Project Overview

A fitness influencer starts coaching clients through Instagram and video calls. As the number of clients increases, they need a proper system to manage:

trainers and clients
coaching plans
subscriptions
consultation and live workout sessions
weekly check-ins
progress tracking
trainer feedback
payments

This ER diagram represents the database structure for such a platform.

🗂 Entities Included

The diagram contains the following main entities:

Users – stores login details for trainers and clients
Trainer – trainer specialization and experience
Client – client fitness details and goals
Plan – coaching or consultation programs
Subscription – which client purchased which plan
Session – scheduled consultation or live workout
Payment – payment details for subscriptions
CheckIn – client progress submissions
Progress – body measurements like weight, waist, chest, etc.
TrainerNotes – trainer feedback on check-ins
WorkoutPlan – workout routines linked to plans
DietPlan – diet guidance linked to plans
🔗 Relationships Supported

This database design allows:

one trainer to manage multiple clients
one trainer to create multiple plans
one plan to be purchased by many clients
one client to buy multiple plans over time
sessions between trainer and client
weekly check-ins from clients
progress tracking after each check-in
trainer feedback storage
payment tracking per subscription
🎯 What This Model Solves

Using this schema, the platform can answer:

who are the trainers and clients?
which plans are available?
which client purchased which plan?
when does a subscription start and end?
are sessions scheduled?
are clients submitting check-ins?
how is progress tracked?
how are payments recorded?

Author

Kishan Gupta-

Web Dev Cohort 2026 🚀

