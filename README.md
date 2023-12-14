# Inventory_management_using_Reinforcement_Learning-Q-Learning-
A major concern of a warehouse owner is how much stock to order from the supplier to meet the customer demand and, at the same time, minimize the costs. The warehouse owner needs to learn the demand pattern and order accordingly. 
This notebook has solution the inventory management problem. It predicts the optimum number of items to be ordered everyday evening (order arrives in 24 hours) to reduce costs and maximize the profit. State is the no. of items in the inventory. action is the number of items to be ordered. If the number of items ordered is less than the next days demand, the shopkeeper incurrs an opportunity cost (due to no. of customers turned away due to unavailability of the item). If the no. of items ordered is more then the capacity of inventory, he has to incur the return cost to return the items.
there are basically two code files: 
Environment (MDP) code
Agent's Q-Learning code
The environment is imported as a class in the agent's code and the agent interacts with the environment by calling the functions of the environment class.
