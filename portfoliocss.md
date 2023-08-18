/* Reset some default styles */

body,
h1,
h2,
h3,
p {
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
}

header {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 2rem;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    background-color: #444;
    padding: 1rem;
}

nav a {
    text-decoration: none;
    color: white;
    padding: 0.5rem 1rem;
}

section {
    padding: 2rem;
}

.project {
    border: 1px solid #ddd;
    padding: 1rem;
    margin-bottom: 1rem;
}

footer {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 1rem;
}


/* Media queries for responsiveness */

@media (max-width: 768px) {
    nav ul {
        flex-direction: column;
        align-items: center;
    }
}