# 📦 Email-to-SharePoint Order Automation with Teams Notification | Power Automate

This project demonstrates how to automate the processing of customer orders received via email using **Power Automate**.  
The flow parses the email body to extract order information, creates a new item in a **SharePoint List**, and sends a real-time confirmation message to a **Microsoft Teams** channel.

---

## 🚀 Features

- 📥 Automatically detects new order emails.
- 🧠 Extracts structured data from email body using Power Automate expressions.
- 💾 Creates an entry in a SharePoint List for easy record management.
- 💬 Sends an instant notification to a Microsoft Teams channel after successful creation.

---

## 💡 Use Case

This flow is perfect for businesses or teams who receive orders or structured requests via email and want to eliminate manual data entry, reduce errors, and enable real-time team collaboration.

---

## 🧰 Prerequisites

- Microsoft Power Automate account.
- A SharePoint List with the following columns:
    - `Customer Name` (Text)
    - `Order Number` (Text)
    - `Item` (Text)
    - `Quantity` (Number)
    - `Total` (Number or Currency)
    - `Delivery Date` (Date)
    - `Customer Email` (Text)
    - `Phone Number` (Text)
    - `Status` (Choice/Text)
- Access to Microsoft Teams for notifications.

---

## ⚙️ Flow Structure

```plaintext
Trigger: When a new email is received  
    ↓  
Extract order information from email body using expressions  
    ↓  
Create a new item in SharePoint List  
    ↓  
Post confirmation message to Microsoft Teams channel
```

## Email Format Example

Customer Name: John Doe  
Order Number: 4567  
Item: Wireless Mouse  
Quantity: 3  
Total: $59.99  
Delivery Date: April 20, 2025  
Customer Email: johndoe@example.com  
Phone Number: +1-234-567-8901  

## 💡 Flow Structure

![Power Automate Flow Structure](https://github.com/nandan2003/Email-to-SharePoint-Order-Automation-with-Teams-Notification-Power-Automate/blob/0d503020fe946dbdbcc06c5abcfc0ffc19ac0f46/Email-to-SharePoint%20Order%20Automation%20Flow.png)

## 🧾 Deployment

1. Export the flow from Power Automate as a `.zip` package.
2. Upload the `.zip` package to this GitHub repository.
3. Document any configuration details (email trigger filter, SharePoint site URL, Teams channel) in a `SETUP.md` file or within this `README.md`.
4. To import the flow:
    - Go to **Power Automate → Import → Select Package (.zip)**.
    - Map your connections.
    - Click **Import**.

---

## 👨‍💻 Author

**Nandan Vallamdasu**  
- 💼 [LinkedIn](https://www.linkedin.com/in/nandan-vallamdasu)

