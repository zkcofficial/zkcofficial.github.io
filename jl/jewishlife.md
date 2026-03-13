<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jewish Life</title>
    <style>
        /* Center the search container */
        .search-container {
            text-align: center;
            margin-top: 20px;
        }

        /* Style the search input */
        input[type=text] {
            padding: 10px;
            font-size: 16px;
            border: 1px solid #ccc;
            border-radius: 4px;
            width: 300px;
        }

        /* Style the results container */
        .results {
            margin-top: 20px;
            text-align: left;
            font-size: 18px;
            max-width: 600px;
            margin: auto;
        }

        /* Style each result item */
        .result-item {
            padding: 10px;
            border-bottom: 1px solid #ccc;
        }
    </style>
</head>
<body>

<h1>Jewish life</h1>

    <!-- Search bar structure -->
    <div class="search-container">
        <input type="text" id="search-input" placeholder="Search here..." onkeyup="performSearch()">
    </div>

    <!-- Search results container -->
    <div id="search-results" class="results"></div>

    <script>
        // Sample data that users can search through
        const sampleData = [
            "Apple",
            "Banana",
            "Cherry",
            "Date",
            "Elderberry",
            "Fig",
            "Grapes",
            "Honeydew Melon",
            "Indian Fig",
            "Jackfruit",
            "Kiwi",
            "Lemon",
            "Mango",
            "Nectarine",
            "Orange",
            "Papaya",
            "Quince",
            "Raspberry",
            "Strawberry",
            "Tomato",
            "Ugli Fruit",
            "Vanilla",
            "Watermelon",
            "Xigua",
            "Yellow Passion Fruit",
            "Zucchini"
        ];

        // Function to perform the search
        function performSearch() {
            const searchInput = document.getElementById('search-input').value.toLowerCase();
            const searchResults = document.getElementById('search-results');
            searchResults.innerHTML = ''; // Clear previous results

            // Filter the data based on the search input
            const filteredData = sampleData.filter(item => item.toLowerCase().includes(searchInput));

            // Display the results
            filteredData.forEach(item => {
                const resultItem = document.createElement('div');
                resultItem.classList.add('result-item');
                resultItem.textContent = item;
                searchResults.appendChild(resultItem);
            });

            // If no results found, show a message
            if (filteredData.length === 0 && searchInput !== '') {
                searchResults.innerHTML = '<p>No results found</p>';
            }
        }
    </script>

</body>
</html>
