1. The problem is that the Second Harvest Bank in Silicon Valley has to package food multiple times a day. Leads to human error and no knowledge of what food survives in which climate. As well as how fresh the food is.
2. We have used Claude and Colab to help make the code, as we were familiar with its resources and knew it could create a code that could handle inventory management.
3. Based on the foods you input to the AI, it can help you determine whether the food can survive in that climate, how fresh the food is, and how much food you have in your inventory. Leads to fewer mistakes and more efficiency from your workers. The employees act on it and the code is below:
   
4. To start things off, you input the food into the search bar of the AI, which the AI would then compute how much you have of that item and what condition the food is in. The AI computes potential errors at the beginning of the output, what foods won't survive and a detailed explanation of the destination of the food item, priority of the food item and the confidence of how well the food would survive. The pictures of how it looks are down below:

5. One failure case is the AI not listing the warnings of the products in danger of losing their freshness or quality.
6. We decided to add scoring helpers that would help with detecting warnings, the screenshots of the code is listed below:
<img width="764" height="503" alt="Screen Shot 2026-05-10 at 1 21 23 PM" src="https://github.com/user-attachments/assets/e91487bb-db69-4082-b325-d4477b83ecbc" />
<img width="703" height="646" alt="Screen Shot 2026-05-10 at 1 22 32 PM" src="https://github.com/user-attachments/assets/da711654-3936-4574-93c9-347a4a73f9cf" />
