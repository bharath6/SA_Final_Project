# SA_Final_Project
Team 23
Observer Functionality

Estimation:
We estimated that it would take 20 hours to meet the requirements and make the observer functionality more generic.
Requirements:
We are required to make the observer functionality more generic so as to be able to add other types of observers and we are also needed to move the PartObservers to be in a better library location. 
We are required to put all core Observer services in Libcore. Application specific portions of observer should be in appropriate libraries other than libcore. It should have a High-Level Session object so that the application specific observers are not registered on Coresession. A second use case for observers needs to be implemented to show that core functionality is isolated but can be extensible.
![image](https://user-images.githubusercontent.com/40848709/161410611-6af2bdd7-47b4-4b2f-ae50-0a91c1451a2a.png)
