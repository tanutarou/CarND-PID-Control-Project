## Effect of PID
### P component
P component means propotional to the current error. This is important component to close to target position.
In `movie/P_control.wmv`, the vehicle use only P component. It looks vibrating.

### D component 
D component means differencial of the current error. This is important component to prevent vibrating.
In `movie/PD_control.wmv`, the vehicle use P and D components. It looks good controler. I think this is enought to complete this project.

### I component
I component means integral of the current error. This is important component to decrease bias.
But I haven't seen the bias in this project.

## hyperparameter tuning
I used twiddle to tune hyperparameters. I could see the decreasing the total error by using it.
My best parameter are Kp = 0.111000, Ki = 0.001210, Kd = 1.100000. 
