![Screenshot 2025-06-14 at 12.08.52.png](attachment:26312b96-a2c2-4522-9b57-71c4aa72b3d0:Screenshot_2025-06-14_at_12.08.52.png)

first simulate many St and then calculate payoff that is → Max( St - k , 0 ) and then calculte Call option price = np.exp( -r * t ) * np.mean(payoffs)
