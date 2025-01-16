/* styles.css */
body {
    font-family: "Arial", sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f7f7f7;
    color: #333;
}

header {
    background-color: #4a90e2;
    color: white;
    text-align: center;
    padding: 20px;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    background-color: #333;
    margin: 0;
    padding: 10px 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: white;
    font-size: 18px;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #4a90e2;
}

main {
    padding: 20px;
}

.era {
    background-color: white;
    margin: 20px auto;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    max-width: 800px;
    text-align: center;
}

.more-info {
    background-color: #4a90e2;
    color: white;
    border: none;
    padding: 10px 20px;
    margin-top: 10px;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
}

.more-info:hover {
    background-color: #357abd;
}

footer {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 10px;
    margin-top: 20px;
}
