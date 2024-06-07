
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SawiSaPagIbig</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            background-image: url('https://www.transparenttextures.com/patterns/hearts.png'); /* Heart pattern background */
            background-size: 400px 400px; /* Adjust the size of the hearts */
        }
        header {
            background-color: #e91e63;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            margin: 0;
            padding: 1em;
            background: #f8bbd0;
            text-align: center;
        }
        nav a {
            margin: 0 1em;
            text-decoration: none;
            color: #e91e63;
        }
        main {
            padding: 2em;
            background-color: rgba(255, 255, 255, 0.9); /* Slight white background for readability */
            margin: 1em;
            border-radius: 10px;
        }
        footer {
            text-align: center;
            padding: 1em;
            background: #e91e63;
            color: #fff;
        }
        .section {
            margin-bottom: 2em;
        }
        form {
            background-color: #fff;
            padding: 1em;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        input, textarea, button {
            width: 100%;
            padding: 0.5em;
            margin: 0.5em 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        button {
            background-color: #e91e63;
            color: #fff;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #d81b60;
        }
        .team-member {
            margin: 1em 0;
            padding: 1em;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <header>
        <h1>SawiSaPagIbig</h1>
        <p>Your partner in resolving relationship issues</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#support-ticket">Support Ticket</a>
        <a href="#chat-groups">Chat Groups</a>
        <a href="#forums">Forums</a>
        <a href="#seminars">Seminars</a>
        <a href="#team">Team</a>
    </nav>
    <main>
        <section id="home" class="section">
            <h2>Welcome to SawiSaPagIbig</h2>
            <p>We are here to help you with any relationship problems you might be facing. Whether it's misunderstandings, breakups, or other issues, our team is ready to provide you with the advice and support you need.</p>
        </section>
        <section id="support-ticket" class="section">
            <h2>Submit a Support Ticket</h2>
            <p>If you need personal advice or support, please submit a support ticket. Our team will respond to you as soon as possible.</p>
            <form>
                <label for="name">Name:</label><br>
                <input type="text" id="name" name="name" required><br>
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email" required><br>
                <label for="issue">Describe your issue:</label><br>
                <textarea id="issue" name="issue" rows="4" required></textarea><br>
                <button type="submit">Submit</button>
            </form>
        </section>
        <section id="chat-groups" class="section">
            <h2>Join Our Chat Groups</h2>
            <p>Connect with others who are going through similar experiences. Join our chat groups to share your story and get advice from peers.</p>
            <button onclick="alert('Chat Group feature coming soon!')">Join Chat Group</button>
        </section>
        <section id="forums" class="section">
            <h2>Forums</h2>
            <p>Participate in our forums to discuss various relationship topics. Ask questions, share your experiences, and learn from others.</p>
            <button onclick="alert('Forums feature coming soon!')">Visit Forums</button>
        </section>
        <section id="seminars" class="section">
            <h2>Upcoming Seminars</h2>
            <p>Attend our seminars to learn about relationship problems and solutions. Our experts provide insights and practical advice to help you navigate your relationship issues.</p>
            <button onclick="alert('Seminars feature coming soon!')">View Seminar Schedule</button>
        </section>
        <section id="team" class="section">
            <h2>Meet Our Team</h2>
            <div class="team-member">
                <h3>Marc jm Pontila</h3>
                <p>Founder & Relationship Advisor</p>
            </div>
            <div class="team-member">
                <h3>Alaiza Antonio</h3>
                <p>Relationship Counselor</p>
            </div>
            <div class="team-member">
                <h3>Reynard Canen</h3>
                <p>Support Specialist</p>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 SawiSaPagIbig. All rights reserved.</p>
    </footer>
</body>
</html>
