# Scrabble-Sankey

Scrabble Sankey diagram is a multilevel network idiom that combines a node-link diagram with a derived cluster hirearchy, intending the path tracing as the main desired task.

In the sankey diagram words are considered as strings of letters (spread horizontally starting from letter index 1 to the word's length). Each node represents a letter at a specific letter index. Each link connects two adjacent letters of a word.
Click on a node to narrow down the current word list to those words that have the selected letter at that specific letter index.
Click on a link to narrow down the current word list to those words that have the selected consecutive letters at those specific letter indices.
If you click on the Reset button, the word list filteration caused by clicking node/link will be reset to none.
You can download the list of the words appearing in the Sankey diagram at whatever step you like.
You can also add your own text into the text box (ideas: baby names, place names, ...)

The histogram chart shows an overview of all the words in SOWPODS dictionary.
					
The heatmap chart helps you to find words starting with and/or ending in a specific letter.
Clicking on a letter on y-axis will select the words starting with that letter. (The result will be reflected on the heatmap and the sankey diagram.)
Clicking on a letter on x-axis will select the words enidng in that letter. (The result will be reflected on the heatmap and the sankey diagram.)
Clicking on a rectangle on the heatmap will select the words with the specified first and last letters. (The result will be reflected on the heatmap and the sankey diagram.)
You can set the lower and upper limit for words' length using the sliders. (The result will be reflected on the heatmap and the sankey diagram.)

The number appearing by each word in superscript is its score in the Scrabble game.
