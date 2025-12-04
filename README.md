Instructions

1. Once the zipfile is downloaded from gitub, note the location of the folder. 
2. Open terminal, and navigate to that folder in terminal
3. Once in that folder in terminal, type "npx expo start"
4. From here the app should give you a QR code, scan the barcode on your phone and open using the the "Expo Go" app


CoPilot Reflection

For this project I chose option a, and added a chart to the previous project, the following is a summary of my prompts I used to get the app to function properly

1. Initial request: "Now let's add a collapsible chart section. In this section let's add a pie chart that shows spend and category"

2. Legend and label formatting: "Let's focus on the pie chart, can you remove the total from the legend, leave only the name of the category and put the spend labels on the chart itself. Make it so it has 'category: $spend' and round to 2 decimal places"

3. Clean up legend display: "I need you to remove the total that displays before 'Category: 
$XX.XX'. The legend still displays the spend amount before 'Category: $XX.XX' and I need it to be gone. Remove the legend entirely."

4. Add custom legend: "Add a legend with this specific format 'category: $spend' rounded to 2 decimal places"

5. Reposition elements: "Can you make the legend next to the pie chart"

6. Adjust chart positioning: "The pie chart gets cut off on the left side, can we move it slightly. Just a little more to the right"

Copilot suggested that I add a separate screen or page for the pie chart but it did not function well or look clean. I instead decided on a collapsible section.

One area copilot saved me time was it was able to reduce the time spent on the actual coding needed to implement and format the pie chart, this allowed me to focus on the visual aspect. I also was able to add a scrolling element to the entire page making it easier to view. 