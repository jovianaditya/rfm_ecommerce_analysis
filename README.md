# RFM E-commerc Analysis

New e-commerce is not too sure about the purchase behavior of its customers. They want to be familiar with customer’s purchase behavior. Knowing the customer's purchase behavior is important because by knowing it the e-commerce company can apply the right business strategy. In this project to know the customer's purchase behavior RFM analysis will be performed followed by clustering using K-Means algorithm.

Explanation of RFM :

![image](https://user-images.githubusercontent.com/113236791/208079119-c5fad554-c103-4886-9942-46e5948e6f8e.png)

RFM Data Frame preview :

![image](https://user-images.githubusercontent.com/113236791/208080129-3e30fc92-7aef-4f8a-83bb-9ded815dc16c.png)

* This data frame is obtained after perform several steps like cleaning, preprocessing, transformation and standardization.


To define the number of cluster will be used for K-Means algorithm several evaluation like elbow method & silhouette chart will be performed :

![image](https://user-images.githubusercontent.com/113236791/208079278-895fce17-089e-4480-82ca-2cf1d35dd0ce.png)

![image](https://user-images.githubusercontent.com/113236791/208079315-fda7d99e-b270-417d-919a-caa11164d11b.png)

![image](https://user-images.githubusercontent.com/113236791/208079342-d90c0984-6458-48e4-a982-e2ee561974be.png)

* From looking the result from evaluation above, it looks k = 3 is the best fit for this project.

Clustering Result 3D View :

![image](https://user-images.githubusercontent.com/113236791/208079548-e28c9460-e933-4f98-b72d-f463c004eec8.png)

Clustering result can be visualize in 2D view because the frequency of each customer is always equal to 1.

![image](https://user-images.githubusercontent.com/113236791/208079745-e51592fa-258b-482a-a3b7-a521dbd1bc4c.png)

Clustering Interpretation :

![image](https://user-images.githubusercontent.com/113236791/208079834-d904752a-488e-4d66-8609-6fa6783a8f9e.png)

Recommendation :

![image](https://user-images.githubusercontent.com/113236791/208079893-bd242d2e-85c2-485f-bfda-ffe6242ab820.png)
