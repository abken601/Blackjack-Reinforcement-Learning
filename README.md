# Blackjack-Reinforcement-Learning

We try reinforcement learning method to game Blackjack. 




After train for  1000000  iterations using Q-Learning\
Out game bot fights against the dealer for  100000  rounds\
Win:  42.744 %\
Draw:  8.690000000000001 %\
Lose:  48.565999999999995 %\

After train for  1000000  iterations using Sarsa
Out game bot fights against the dealer for  100000  rounds
Win:  42.44 %
Draw:  7.5920000000000005 %
Lose:  49.968 %

After train for  1000000  iterations using Temporal Difference
Out game bot fights against the dealer for  100000  rounds
Win:  43.646 %
Draw:  8.298 %
Lose:  48.056 %

                                            Q-learning\
              player (usable ace)                            player (no usable ace)    \
          11 12 13 14 15 16 17 18 19 20 21               11 12 13 14 15 16 17 18 19 20 21 \
       1   H  S  S  H  S  S  S  S  S  S  S            1   H  H  S  H  H  H  S  S  S  S  S \ 
       2   H  H  H  H  H  H  H  S  S  S  S            2   H  S  H  S  S  S  S  S  S  S  S \ 
       3   H  H  H  H  H  H  H  S  S  S  S            3   H  H  S  S  S  S  S  S  S  S  S \ 
       4   H  H  H  H  H  H  H  S  S  S  S            4   H  S  S  S  S  S  S  S  S  S  S \ 
dealer 5   H  H  H  H  H  H  H  H  S  S  S     dealer 5   H  S  S  S  S  S  S  S  S  S  S \ 
       6   H  H  H  H  H  H  H  H  S  S  S            6   H  H  S  S  S  S  S  S  S  S  S \ 
       7   H  H  H  H  H  H  H  S  S  S  S            7   H  H  H  H  H  H  S  S  S  S  S \ 
       8   H  H  H  H  H  H  H  S  S  S  S            8   H  H  H  H  H  H  H  S  S  S  S \ 
       9   H  H  H  H  H  H  S  H  S  S  S            9   H  H  H  S  H  H  S  S  S  S  S \ 
      10   H  H  H  H  H  S  S  S  S  S  S           10   H  H  H  H  H  H  S  S  S  S  S \ 

                                              Sarsa
              player (usable ace)                            player (no usable ace)    
          11 12 13 14 15 16 17 18 19 20 21               11 12 13 14 15 16 17 18 19 20 21 
       1   H  S  S  S  S  S  S  S  S  S  S            1   H  S  S  S  S  H  S  S  S  S  S  
       2   H  H  H  H  H  H  H  S  S  S  S            2   H  S  S  S  S  S  S  S  S  S  S  
       3   H  H  H  H  H  H  H  S  S  S  S            3   H  S  S  S  S  S  S  S  S  S  S  
       4   H  H  H  H  S  H  H  S  S  S  S            4   H  H  S  S  S  S  S  S  S  S  S  
dealer 5   H  H  H  H  H  H  H  H  S  S  S     dealer 5   H  S  S  S  S  S  S  S  S  S  S  
       6   H  H  H  H  H  H  H  H  S  S  S            6   H  S  S  S  S  S  S  S  S  S  S  
       7   H  H  H  H  H  H  S  S  S  S  S            7   H  H  H  H  H  H  S  S  S  S  S  
       8   H  H  H  H  H  H  H  S  S  S  S            8   H  H  H  S  S  H  H  S  S  S  S  
       9   H  H  H  H  H  S  H  S  S  S  S            9   H  S  H  H  S  H  S  S  S  S  S  
      10   H  H  H  H  S  H  S  S  S  S  S           10   H  H  H  S  S  S  S  S  S  S  S  

                                        Temporal Difference
              player (usable ace)                            player (no usable ace)    
          11 12 13 14 15 16 17 18 19 20 21               11 12 13 14 15 16 17 18 19 20 21 
       1   H  H  H  H  H  H  H  S  S  S  S            1   H  H  H  H  H  H  S  S  S  S  S  
       2   H  H  H  H  H  H  H  S  S  S  S            2   H  S  S  S  S  S  S  S  S  S  S  
       3   H  H  H  H  H  H  H  S  S  S  S            3   H  S  S  S  S  S  S  S  S  S  S  
       4   H  H  H  H  H  H  H  S  S  S  S            4   H  S  S  S  S  S  S  S  S  S  S  
dealer 5   H  H  H  H  H  H  H  H  S  S  S     dealer 5   H  S  S  S  S  S  S  S  S  S  S  
       6   H  H  H  H  H  H  H  S  S  S  S            6   H  S  S  S  S  S  S  S  S  S  S  
       7   H  H  H  H  H  H  H  S  S  S  S            7   H  H  H  H  H  H  S  S  S  S  S  
       8   H  H  H  H  H  H  H  S  S  S  S            8   H  H  H  H  H  S  S  S  S  S  S  
       9   H  H  H  H  H  H  H  H  S  S  S            9   H  H  H  H  H  S  S  S  S  S  S  
      10   H  H  H  H  H  H  H  S  S  S  S           10   H  H  H  S  S  S  S  S  S  S  S  
      
      
