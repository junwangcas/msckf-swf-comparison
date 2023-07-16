# The Battle for Filter Supremacy: A Comparative Study of the Multi-State Constraint Kalman Filter and the Sliding Window Filter

### Abstract

SWF更准确，MSCKF计算成本更低

MSCKF状态量中并不维护landmark。SWF是需要维护landmark的。

### Background

### III. SLIDING WINDOW FILTER

Slides表示ppt，表示的就是一个滑动的意思。Window就说明后面有墙，墙是不管的，只管窗户上的东西。人生就是一个sliding window, 过去的是不管的，未来的也是不管的，今天就是那个window。pose是自己，landkmark是其他人。

为什么叫filter呢，预测的时候，使用imu的数据往前推，修正的时候，使用视觉的信息。在做高斯牛顿的时候，并没有使用imu的信息。





