1. The problem is that the Second Harvest Bank in Silicon Valley has to package food multiple times a day. Leads to human error and no knowledge of what food survives in which climate. As well as how fresh the food is.
2. We have used Claude and Colab to help make the code, as we were familiar with its resources and knew it could create a code that could handle inventory management.
3. Based on the foods you input to the AI, it can help you determine whether the food can survive in that climate, how fresh the food is, and how much food you have in your inventory. Leads to fewer mistakes and more efficiency from your workers. The employees act on it and the code is below:
   <img width="529" height="696" alt="Screenshot 2026-05-10 at 2 35 50 PM" src="https://github.com/user-attachments/assets/20c88ea5-2897-4560-956d-51aa5e5187c4" />
   <img width="529" height="696" alt="Screenshot 2026-05-10 at 2 42 46 PM" src="https://github.com/user-attachments/assets/a297c2ca-a158-477a-890b-35b3c54a5a46" />
<img width="529" height="696" alt="Screenshot 2026-05-10 at 2 43 28 PM" src="https://github.com/user-attachments/assets/6135200b-67c1-4664-b9de-903e9c340f25" />
<img width="529" height="696" alt="Screenshot 2026-05-10 at 2 43 39 PM" src="https://github.com/user-attachments/assets/cf2c53ac-7409-43cd-bc73-25b0db05f19d" />
<img width="529" height="570" alt="Screenshot 2026-05-10 at 2 43 54 PM" src="https://github.com/user-attachments/assets/bde25168-05fa-457b-bec2-aa9bd4fc45bc" />
<img width="529" height="654" alt="Screenshot 2026-05-10 at 2 44 06 PM" src="https://github.com/user-attachments/assets/2eb3121b-19c6-449d-96a9-08af9ec29378" />
<img width="529" height="696" alt="Screenshot 2026-05-10 at 2 44 27 PM" src="https://github.com/user-attachments/assets/494a5493-8d12-4a34-942b-7c1f10c7398b" />
<img width="529" height="696" alt="Screenshot 2026-05-10 at 2 44 43 PM" src="https://github.com/user-attachments/assets/15e3a106-6bcd-4be8-8756-1c4c21f6aafb" />
<img width="529" height="696" alt="Screenshot 2026-05-10 at 2 47 05 PM" src="https://github.com/user-attachments/assets/d20b61f5-0a41-46ae-bb0d-8ea0d8ab45d5" />
<img width="529" height="696" alt="Screenshot 2026-05-10 at 2 47 15 PM" src="https://github.com/user-attachments/assets/6a06d502-4824-403d-b864-ee4b8c7c4dce" />
<img width="529" height="696" alt="Screenshot 2026-05-10 at 2 47 37 PM" src="https://github.com/user-attachments/assets/b30f7464-2127-4acc-8b17-947ece62c175" />
<img width="529" height="696" alt="Screenshot 2026-05-10 at 2 48 13 PM" src="https://github.com/user-attachments/assets/62920ab3-d44b-4d93-838b-724eda312a3c" />
<img width="529" height="696" alt="Screenshot 2026-05-10 at 2 48 20 PM" src="https://github.com/user-attachments/assets/4b0d53e4-30a2-4cdc-bd46-c238a421188f" />
<img width="529" height="396" alt="Screenshot 2026-05-10 at 2 48 57 PM" src="https://github.com/user-attachments/assets/4eda2394-ce6c-477d-adee-e280f0a2b854" />
<img width="529" height="612" alt="Screenshot 2026-05-10 at 2 49 13 PM" src="https://github.com/user-attachments/assets/4085e3f2-b26d-43e8-9338-5dc443b886dc" />


   
   
5. To start things off, you input the food into the search bar of the AI, which the AI would then compute how much you have of that item and what condition the food is in. The AI computes potential errors at the beginning of the output, what foods won't survive and a detailed explanation of the destination of the food item, priority of the food item and the confidence of how well the food would survive. The pictures of how it looks are down below:

6. One failure case is the AI not listing the warnings of the products in danger of losing their freshness or quality. To a user, they wouldn't be able to identify what product is good or bad quality.
7. We decided to add scoring helpers that would help with detecting warnings, the screenshots of the code is listed below:
<img width="764" height="503" alt="Screen Shot 2026-05-10 at 1 21 23 PM" src="https://github.com/user-attachments/assets/e91487bb-db69-4082-b325-d4477b83ecbc" />
<img width="703" height="646" alt="Screen Shot 2026-05-10 at 1 22 32 PM" src="https://github.com/user-attachments/assets/da711654-3936-4574-93c9-347a4a73f9cf" />
