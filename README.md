Some tests done on Yaskawa MA1440 executing a straight line trajectory along the Y axis

| test nr | executor                     | point amount | dist between points | speed  | done | cartesian dist |
|---------|------------------------------|--------------|---------------------|--------|------|----------------|
| t1      | follow_joint_trajectory      | 60           | 0.01                | 0.005  | x    | 0.6            |
| t2      |                              | 120          | 0.005               | 0.005  | x    | 0.6            |
| t3      |                              | 180          | 0.001               | 0.005  | x    | 0.18           |
| t4      |                              | 180          | 0.0005              | 0.005  | x    | 0.09           |
| t5      |                              | 180          | 0.0001              | 0.005  | x    | 0.018          |
| t6      | motoros2_fjt_pt_queue_proxy  | 60           | 0.01                | 0.005  | x    | 0.6            |
| t7      |                              | 120          | 0.005               | 0.005  | x    | 0.6            |
| t8      |                              | 180          | 0.001               | 0.005  | x    | 0.18           |
| t9      |                              | 180          | 0.0005              | 0.005  | x    | 0.09           |
| t10     |                              | 180          | 0.0001              | 0.005  | x    | 0.018          |
| t11     |                              | 600          | 0.001               | 0.005  | x    | 0.6            |
| t12     |                              | 600          | 0.0005              | 0.005  | x    | 0.3            |
| t13     |                              | 1000         | 0.0001              | 0.005  | x    | 0.1            |
| t14     | c++ point queue              | 60           | 0.01                | 0.005  | x    | 0.6            |
| t15     |                              | 120          | 0.005               | 0.005  | x    | 0.6            |
| t16     |                              | 180          | 0.001               | 0.005  | x    | 0.18           |
| t17     |                              | 180          | 0.0005              | 0.005  | x    | 0.09           |
| t18     |                              | 180          | 0.0001              | 0.005  | x    | 0.018          |
| t19     |                              | 600          | 0.001               | 0.005  | x    | 0.6            |
| t20     |                              | 600          | 0.0005              | 0.005  | x    | 0.3            |
| t21     |                              | 1000         | 0.0001              | 0.005  |      | 0.1            |

youtube link to videos: [Link](https://www.youtube.com/playlist?list=PLLQNCcGbjtuqyYQQJ1ArgyS5mgTRuhVYO)

