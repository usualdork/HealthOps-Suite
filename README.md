# HealthOps Suite: Inventory & Hospital Management Systems 🎉

*Crafted with love (and a sprinkle of sibling mischief) to help my younger brother impress at his coding exhibition and, who knows, maybe even sweep a few ladies off their feet with his impeccable management skills! 💻❤️*

## Introduction

Welcome to **HealthOps Suite**, a dynamic duo of Python applications designed to turn my younger brother into the ultimate gentleman with impeccable organizational prowess. Move over, James Bond - there's a new charmer in town, and he's armed with Python scripts! 🕴️💼

Whether he's managing a bustling medicine inventory or orchestrating hospital operations like a maestro, these programs are his secret weapons to impress and inspire. Who knew that behind every charming smile lies a robust management system?💖📊

## Features

### 🏥 Hospital Management System
- **Patient Management:** Seamlessly add, update, and delete patient records. Because nothing says "I care" like meticulous record-keeping!
- **Doctor Management:** Maintain comprehensive profiles of doctors, including specialties and contact details. It's like LinkedIn, but for saving lives!
- **Appointment Scheduling:** Effortlessly schedule, update, and cancel appointments. No more double-booking dates... err, doctor visits!
- **AI-Powered Chatbot:** Engage with a medical chatbot powered by the HuggingChat API for instant assistance. It's like having a really smart, really fast-typing nurse at your fingertips!
- **Responsive UI:** Enjoy a user-friendly interface with a modern and sleek design. Because even hospital software deserves to look good!

#### Hospital Management System Screenshots
*Dashboard showcasing patient, doctor, and appointment management*

![image](https://github.com/user-attachments/assets/3739386d-11e9-4215-83f8-a951a31e9dbc)

*The AI-powered chatbot interface for instant assistance*

![image](https://github.com/user-attachments/assets/d276427d-2c7d-47fc-b221-1f325dce3e9e)

### 💊 Medicine Inventory Management System
- **Add & Manage Medicines:** Easily add, update, and delete medicine records. Keeping track of pills has never been this thrilling!
- **Categorization:** Organize medicines by predefined categories and manufacturers. It's like a wardrobe organizer, but for drugs (the legal kind)!
- **Low Stock Alerts:** Receive warnings when stock levels fall below the set threshold. No more "Oops, we're out of aspirin" moments!
- **Expiry Notifications:** Get notified about expired medicines to ensure inventory quality. Because nobody likes stale pills!
- **Analytics Dashboard:** Visualize inventory data with insightful charts and graphs. Impress everyone with your data-driven decision-making skills!
- **GitHub Integration:** Quick access to project updates via a clickable GitHub logo. Show off your tech-savviness with just one click!

*Dashboard for managing medicines and tracking inventory analytics*
![image](https://github.com/user-attachments/assets/cdbbac50-b027-4b05-b5c2-2199f04bccd0)

![image](https://github.com/user-attachments/assets/40a9c0fe-7bc9-4292-ab0f-8d31e060050d)

*Example of low stock and expiry notifications for inventory management*
![image](https://github.com/user-attachments/assets/3abac362-d610-4ef0-ba51-54caac8ca02e)

*Realtime analytics of inventory*
![image](https://github.com/user-attachments/assets/d8ed1d9a-ee44-4b04-ae66-6db5f2c21983)

## Installation

Set up both applications on your local machine by following these simple steps:

### Prerequisites
- **Python 3.x**: Ensure Python is installed on your system. Download it [here](https://www.python.org/downloads/).
- **Git**: Required for cloning the repository. Download it [here](https://git-scm.com/downloads).

### Clone the Repository
```bash
git clone https://github.com/usualdork/HealthOps-Suite
cd HealthOps-Suite
```

### Set Up a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### Install Required Libraries
Install all necessary dependencies using the provided `requirements.txt`:
```bash
pip install -r requirements.txt
```

**Dependencies:**
- `tkinter` (usually comes pre-installed with Python)
- `sqlite3` (standard library)
- `matplotlib`
- `Pillow`
- `requests`
- `hugchat`
- `re`

Alternatively, install them individually:
pip install matplotlib Pillow requests hugchat

## Usage

### 🏥 Hospital Management System
Navigate to the `hospital_management` directory and run:
```bash
python hospital_management.py
```

This will launch the Hospital Management System GUI, allowing you to manage patients, doctors, and appointments effortlessly.

### 💊 Medicine Inventory Management System
Navigate to the `inventory_management` directory and run: 
```bash
python inventory_management.py
```

This will open the Medicine Inventory Management System interface, where you can start organizing and tracking your medicine inventory with ease.

## Libraries Used

- **Tkinter:** For creating the graphical user interface. Because CLI is so last century!
- **SQLite3:** Lightweight database for managing data. Small but mighty, just like my brother!
- **Matplotlib:** Generating analytics and visualizations. Because a picture is worth a thousand SQL queries!
- **Pillow:** Image processing and handling. No, it's not for napping - though coding might make you want to!
- **Requests:** Handling HTTP requests for fetching external resources. It's like a digital courier service!
- **HuggingChat API:** Integrating AI-powered chatbot functionalities. It's like having a really smart sidekick!
- **Re:** Regular expressions for data validation. Because sometimes, you just need to get a little regex-y!

## Credits

A special shoutout to the amazing tools and resources that made these projects possible:

- **ChatGPT-4 & Claude:** Assisted in generating various parts of the program code and documentation.
- **[HuggingChat API by Soulter](https://github.com/Soulter/hugging-chat-api):** Utilized for integrating the chatbot feature.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use it!

## Acknowledgements

Creating these applications not only helped my brother manage his tasks more efficiently but also added a touch of impressiveness to his repertoire. Here's to many more lines of code, countless admirers, and hopefully, a few less bugs in both the software and his love life! 🚀💘

---

*Feel free to contribute, suggest improvements, or just drop a star if you found these tools useful! After all, every star here is like a Tinder right-swipe for the repo! ⭐*

## A Final Note

Remember, dear brother, while these tools might help you manage inventories and hospitals, they can't manage matters of the heart. But hey, at least you'll have perfectly organized data to cry into if things don't work out! 😉

Now go forth and conquer, you code-savvy Casanova!

## Troubleshooting

### "Why isn't my charm working?"
1. Check if you've actually run the program. Talking about code isn't the same as running it!
2. Ensure you're not confusing SQL statements with pickup lines. "SELECT * FROM your_number" isn't as smooth as you think.
3. If all else fails, try turning yourself off and on again. Works for computers, might work for you!

### "The program crashed when I tried to schedule a date... I mean, appointment!"
1. Make sure you're using the Hospital Management System for actual hospital appointments.
2. Check if you've entered a valid date. "Someday" is not a recognized datetime format.
3. If the issue persists, consider that maybe the program is trying to tell you something about your scheduling skills.


## Testimonials

> "Thanks to this software, I can now manage a hospital AND my love life! Though I'm still not sure which is more complicated." - My Brother

> "I was impressed by his database skills, but I stayed for his perfectly organized medicine cabinet." - Anonymous Admirer

> "I thought I was going on a date, but somehow ended up learning about inventory management. Strangely, I wasn't disappointed." - Confused But Intrigued

## Disclaimer

While this software has been tested extensively on various systems, we cannot guarantee its effectiveness on actual human interactions. Side effects may include uncontrollable urges to organize things, speaking in SQL queries, and an inexplicable attraction to well-structured code. Use with caution!

---

Remember, with great power comes great responsibility. Use this software wisely, and may your relationships be as stable as your database connections!

Now go out there and show the world that love and logistics can indeed go hand in hand! 💖💻
