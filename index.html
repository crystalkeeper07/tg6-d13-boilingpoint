<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Global Clicker</title>
    <script src="https://www.gstatic.com/firebasejs/9.6.1/firebase-app.js"></script>
    <script src="https://www.gstatic.com/firebasejs/9.6.1/firebase-database.js"></script>
</head>
<body>
    <h1>Global Clicker</h1>
    <h2>Clicks: <span id="counter">0</span></h2>
    <button onclick="increaseCount()">Click Me!</button>

    <script>
        // 🔹 Firebase configuration
        const firebaseConfig = {
            apiKey: "",  // No API key needed for just database interactions
            authDomain: "tg6-d13-boiling-point.firebaseapp.com",
            databaseURL: "https://tg6-d13-boiling-point-default-rtdb.asia-southeast1.firebasedatabase.app/",
            projectId: "tg6-d13-boiling-point",
            storageBucket: "tg6-d13-boiling-point.appspot.com",
            messagingSenderId: "",
            appId: ""
        };

        // 🔹 Initialize Firebase
        firebase.initializeApp(firebaseConfig);
        const database = firebase.database();
        const counterRef = database.ref("clickCounter");

        // 🔹 Update counter in real-time
        counterRef.on("value", (snapshot) => {
            document.getElementById("counter").innerText = snapshot.val() || 0;
        });

        // 🔹 Increase counter when button is clicked
        function increaseCount() {
            counterRef.transaction((currentValue) => {
                return (currentValue || 0) + 1;
            });
        }
    </script>
</body>
</html>

