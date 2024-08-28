# MARL-A-1

**Optimal Value Function:**

Value Iteration:
Hostel: 19.70
Academic Building: 21.65
Canteen: 20.78


**Optimal Policy:**

Policy Iteration:
Hostel: Eat Food
Academic Building: Attend Class
Canteen: Attend Class


Both value iteration and policy iteration have provided optimal solutions, but they may slightly differ due to the convergence patterns of the algorithms.
The optimal value function obtained from both methods indicates the expected cumulative rewards from each state, with Academic Building having the highest value followed by Canteen and then Hostel.
The optimal policy derived from policy iteration suggests that the student should Eat Food in Hostel, Attend Class in the Academic Building, and Attend Class in the Canteen.
The results indicate that attending class in the Academic Building and Canteen is more beneficial compared to staying in the Hostel, which aligns with the rewards assigned to each action and state.
The differences in the optimal value function and policy obtained from the two methods can be attributed to the iterative nature of policy iteration and the direct computation approach of value iteration.
In conclusion, both policy iteration and value iteration have provided effective solutions to the MDP problem, offering insights into the optimal values and policies for each state. The discrepancies in the results highlight the nuances in the convergence paths of the algorithms, but both approaches have successfully identified the best actions for the student in each location on the campus.
