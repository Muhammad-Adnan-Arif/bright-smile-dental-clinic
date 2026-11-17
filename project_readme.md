# BrightSmile Dental Assistant

An AI receptionist for a dental clinic. Patients chat on the clinic's website, and the assistant books, reschedules and cancels appointments for them, answers questions about the clinic, and keeps everyone on track with email reminders.

BrightSmile is a fictional clinic in Lahore. I made it up so I could build something that feels like a real client project without touching real patient data.



## Why I built this

Small clinics lose a lot of time to the same few messages: "Are you open on Saturday?", "How much is a cleaning?", "Can I move my appointment?". I wanted to see how far a single assistant could go in handling all of that properly, not just answering questions but actually changing the schedule and leaving a clean record behind.

## What it does

### Answers questions

Services, prices, durations, opening hours and so on. It only says what the clinic has told it, and if it doesn't know something it says so instead of guessing.



### Books appointments

It asks for what it needs, checks what's actually free, shows a summary, and only books after the patient says yes.



### Reschedules and cancels

Same idea: it finds the patient's appointment, repeats what will change, and waits for a clear yes. The calendar and the records always change together, so nothing gets out of sync.



### Recognizes returning patients

If someone comes back from a different phone or browser, they can give the number they booked with and the assistant picks up their existing appointment instead of treating them as a stranger.

### Sends reminders and follow-ups

Patients get an email before their visit. After the visit there's a thank-you note, or a friendly "we missed you" if they didn't show up.

## What the clinic sees

Every booking shows up on the clinic's calendar and in a simple appointments table, so the front desk can see the day without opening the chat.

## Built with

n8n, OpenAI, Google Calendar, Airtable, Gmail, and a plain HTML/CSS/JavaScript front end (the chat widget on the landing page).

> The chat is connected to my own backend, which isn't part of this repository. The workflow itself isn't published.

## Things I'd improve

* Identifying a returning patient by phone number alone is fine for a demo, but a real clinic would want a verification step (like a one-time code) before showing anyone's appointment details.
* Right now it only handles one clinic. Supporting several branches or doctors would be the next step.
* WhatsApp would be a more natural channel for patients here than a website chat.

## About

Built by Muhammad Adnan Arif as part of my automation portfolio. If you're a clinic or business that wants something like this, feel free to reach out.

Email: madnanarif174@gmail.com

## Project Screenshots

### Website Homepage

!\[Homepage](screenshots/Homepage.jpg)

### n8n Workflow

!\[Workflow](screenshots/Workflow.jpg)

### Appointment Booking

!\[Appointment Booking](screenshots/Appointment%20Booking.jpg)

### Details Confirmation

!\[Details Confirmaion](screenshots/Details%20Confirmaion.jpg)

### Rescheduling Appointment

!\[Rescheduling appointment (2)](screenshots/Rescheduling%20appointment%20(2).jpg)

### Appointment Rescheduled

!\[Appointment Rescheduled](screenshots/Appointment%20Rescheduled.jpg)

### Appointment Cancellation

!\[Appointment Cancellation,Cancelled](screenshots/Appointment%20Cancellation,Cancelled.jpg)

### Airtable Appointments Table

!\[Airtable Appointments Table](screenshots/Airtable%20Appointments%20Table.jpg)

### Airtable Conversations Table

!\[Airtable Conversations Table](screenshots/Airtable%20Conversations%20Table.jpg)

### Airtable Customers Table

!\[Airtable Customers Table](screenshots/Airtable%20Customers%20Table.jpg)

