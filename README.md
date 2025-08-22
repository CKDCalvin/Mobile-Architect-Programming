# Mobile-Architect-Programming

## Summary of Requirements and Goals  
The Inventory App was designed to help users easily manage items in a personal or small business inventory. The goal was to create a mobile application that allows users to add, view, and delete items while maintaining a clean, intuitive interface. This app addresses the user's need for simple, reliable inventory tracking without the complexity of larger enterprise systems.  

## Screens and Features for User Needs  
The app includes three primary screens:  
1. **Login Screen** – Ensures secure access by requiring a username and password.  
2. **Inventory Display Screen** – Displays a list/grid of inventory items, each with a delete button for quick management, and an add button for adding new items.  
3. **SMS Notification Screen** – Handles SMS permissions and sends notifications to confirm user actions.  

The UI design followed user-centered principles by using logical grouping, clear focus order, and smooth transitions. Elements were placed in an intuitive order to reflect the natural steps a user would take when interacting with the app. These designs were successful because they minimized confusion, supported accessibility, and kept tasks simple.  

## Coding Approach and Strategies  
During development, I used modular coding practices by organizing UI, logic, and data handling into separate components. I relied on Android’s Activity lifecycle management, proper use of intents, and permissions handling for SMS features. My approach emphasized iterative designing, coding, and testing in cycles. These techniques can be applied in future projects to maintain clarity, scalability, and efficiency.  

## Testing Process  
I tested functionality using the Android Emulator and step-by-step validation of each screen. Each feature-login, item management, and notifications was tested independently and together in sequence. Testing revealed small issues, such as missing the `Inventory` declaration in the `AndroidManifest.xml`, which I corrected. This process was essential to ensuring stability and usability before considering deployment.  

## Innovation and Problem-Solving  
One challenge was handling permissions for SMS notifications, which required not only manifest declarations but also runtime permission requests. Another was designing the inventory list layout to balance clarity with flexibility. Overcoming these challenges required researching Android documentation and adjusting the design until it was both functional and user-friendly.  

## Key Success  
I was particularly successful in demonstrating skills in UI design and user-centered development. The smooth flow between screens and the intuitive inventory management features highlight my ability to create applications that address real user needs while following Android development best practices.  
