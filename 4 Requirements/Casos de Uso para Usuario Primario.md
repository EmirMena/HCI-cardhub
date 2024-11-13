# Primary User Uses Cases


## Use Case 1: Register and Configure Credit Cards

**Business Event Name:** User registers and configures their credit cards.

**Business Use Case Name and ID:** UC-01 Register and Configure Credit Cards

**Trigger:** Francisco opens the application for the first time after downloading it and wants to add his credit cards.

**Preconditions:**

* Francisco has installed the app on his device.
* Francisco has an active email account to register in the app.

**Interested Stakeholders:**

* Francisco (primary user)
* Credit card issuing banks (to provide updated information, if connected)

**Active Stakeholders:**

* Francisco (primary user)

**Normal Case Steps:**

1. Francisco opens the application and selects "Register" to create a new account.
2. Francisco enters his name, email, and password to complete the registration process.
3. The system authenticates Francisco's email and creates his account.
4. Francisco logs in to his account using his email and password.
5. The system provides an option to add credit cards.
6. Francisco selects the "Add Credit Card" option and chooses his bank from a list.}
7. Francisco enters information for each of his credit cards, including the card name, cut-off date, payment due date, and any other relevant details.
8. The system saves the information and displays a summary of each card in a virtual cardholder.
  
**Alternatives:**
  Alternative step 2.1: If Francisco already has an account, he can log in directly.

**Exceptions:**
  Exception step 3.1: If Francisco's email is already registered, the system prompts him to log in instead of creating a new account.
  Exception step 6.1: If Francisco’s bank is not listed, he can manually enter the bank name and card details.
  
**Outcome:** Francisco successfully registers and configures his credit cards, allowing him to view all his card details in one place within the app.


## Use Case 2: Receive Payment Reminders and Make Payments

**Business Event Name:** User receives payment reminders and completes credit card payments.

**Business Use Case Name and ID:** UC-02 Receive Payment Reminders and Make Payments

**Trigger:** Francisco receives a notification reminding him of an upcoming credit card payment.

**Preconditions:**

* Francisco has successfully registered and configured his credit cards in the app.
* Francisco has enabled notifications for payment reminders.

**Interested Stakeholders:**

Francisco (primary user)
Credit card issuing banks (to verify payments made, if integrated)

**Active Stakeholders:**

Francisco (primary user)

**Normal Case Steps:**

1. The system detects an upcoming payment due date for one of Francisco's credit cards (7 days prior).
2. The system sends a notification to Francisco’s device, reminding him of the upcoming payment and showing the amount needed to avoid interest.
3. Francisco opens the app to view the payment reminder details.
4. The system displays the card summary, including the due date, minimum payment, and total payment required to avoid interest.
5. Francisco reviews the details and proceeds to make a payment using his bank’s app or website.
6. After making the payment, Francisco marks the card as “Paid” within the app.
7. The system records the payment status and removes any remaining notifications for that payment cycle.

**Alternatives:**
  Alternative step 2.1: If Francisco dismisses the initial notification, the system will send a follow-up reminder 2 days before the due date.

**Exceptions:**
  Exception step 3.1: If Francisco has not enabled notifications, he will need to manually check his app dashboard for payment due dates.

**Outcome:** Francisco receives timely reminders, reviews the payment information, completes his credit card payment on time, and avoids interest charges.
