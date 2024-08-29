# The Digital Mirror: AI and the Evolution of Portraiture

This repositry is the code for Digital Mirror, which is a collaboration between artist Cian McLoughlin and mathematician and neuroscientist John Butler of TU Dublin. Together, they explore the connections between art, machine learning, and neuroscience in the context of facial recognition. 
 
Cian has a series of paintings called "Tronies," where he overlays portraits of a single subject to freely explore the diverse spectrum of human appearance (click here to view). This artistic process mirrors the way machine learning is used in facial recognition. Machine learning algorithms start by defining an average face and then subtract it from individual images to identify unique features, known as eigenfaces, which help distinguish between different people.

![PHOTO-2024-08-26-18-13-29](https://github.com/user-attachments/assets/0dc1de30-04ad-4660-b982-1e9c1ac15ff9)

This method of breaking down an image and reconstructing it is akin to how our visual system works. The brain deconstructs visual information and processes it, ultimately allowing us to recognize and differentiate between faces.



The code videos a person for 10 seconds as they make different faces. 
![PHOTO-2024-08-20-18-15-43](https://github.com/user-attachments/assets/5b42515f-82e8-4629-ab13-22d861737440)


The images are then processed using Prinicipal Component Analysis to get the Meanface and Eigenfaces.
![Cian2eigenfaces](https://github.com/user-attachments/assets/6dbde16c-6ab7-408e-abf6-18b7c9c0a687)

Which can be used to reconstruct an image:

![Cian2_Recon](https://github.com/user-attachments/assets/9a370724-b49d-4dd2-af89-cd9687b453ef)\
