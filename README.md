<h3>Flashcard Application</h3>
<p>This code creates a flashcard application using Tkinter and pandas. Here's a brief overview and a few suggestions to enhance the code:</p>

<h4>Overview</h4>

<h5>Libraries Used</h5>
<ul>
    <li><strong>tkinter</strong>: For the GUI.</li>
    <li><strong>pandas</strong>: For handling CSV data.</li>
    <li><strong>random</strong>: For selecting random flashcards.</li>
</ul>

<h5>Main Functionalities</h5>
<ul>
    <li>Displays French words with an option to flip to see the English translation.</li>
    <li>Marks words as known or unknown.</li>
    <li>Saves the known words to a CSV file.</li>
</ul>

<h4>Code Structure</h4>

<h5>Function Definitions</h5>
<ul>
    <li><strong>flip_card()</strong>: Flips the card to show the English translation.</li>
    <li><strong>next_card()</strong>: Displays the next French word.</li>
    <li><strong>is_known()</strong>: Removes the current word from the learning list and updates the CSV file.</li>
</ul>

<h5>Tkinter Setup</h5>
<ul>
    <li>Configures the main window.</li>
    <li>Sets up the canvas for the flashcards.</li>
    <li>Creates buttons for user interaction (known/unknown).</li>
</ul>

<h5>CSV Handling</h5>
<ul>
    <li>Loads words from a CSV file, and updates it based on user interactions.</li>
</ul>
