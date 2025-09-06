## Checkout Flow Optimization Analysis with SQL and Tableau

### Overview
This project analyzes the **checkout funnel** of an e-commerce platform to identify drop-offs, errors, and device-specific issues. Using **SQL** for data preparation and **Tableau** for visualization, the goal is to uncover reasons for cart abandonment and suggest actionable improvements.
<img width="552" height="867" alt="image" src="https://github.com/user-attachments/assets/526eca3f-d4ac-4bf5-a149-4f4c4ebc00d5" />

***Tableau story URL:*** https://public.tableau.com/views/CheckoutFlowOptimizationAnalysiswithSQLandTableauProject_17566395281580/Story1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

### Key Objectives
- Identify where customers drop off in the checkout funnel  
- Analyze frequent error messages and device-specific issues  
- Understand how cart creation translates into successful checkouts  

### Insights & Recommendations

**Insights:**  
- Average checkout success rate: ~11%, abandonment: ~78%  
- Mobile users had slightly higher failure rates  
- 29 distinct error messages, some device-specific (e.g., "Session Expired" on mobile)  
- February–March 2023 had missing successful checkouts, inflating abandonment

**Recommendations:**  
- Prioritize fixing recurring errors like `"Year field is required"` and `"Number field is required"`  
- Simplify payment workflows and offer multiple options  
- Implement auto-save carts and persistent sessions  
- Track abandonment separately per device  
- Build a real-time error dashboard to detect spikes  

### Tools Used
- Mysql Workbench 
- Tableau Desktop  
- Excel (optional preprocessing)
