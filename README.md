TODO APPLICATION
DMA (Developing Mobile Application)
Sabina Bhandari(c7210593)


Introduction:
The given documentation will include TODO application, I have explained the method of using the given system and about the architecture of future evolutions and maintenance. TODO application is a SPA (single page application) modeling a simple todo list allowing you to add and follow your day-to-day tasks.
Requirement	Features 	Used framework	Database
Android studio 3.5 or latest 	Add, edit, delete task. View task, marked. 	Model View View Model (MVVM)	SQLite

Framework:
MVVM stands for Model, View, ViewModel.
•	Model: This holds the data of the application. It cannot directly talk to the View. Generally, it’s recommended to expose the data to the ViewModel through Observables.
•	View: It represents the UI of the application devoid of any Application Logic. It observes the ViewModel.
•	ViewModel: It acts as a link between the Model and the View. It’s responsible for transforming the data from the Model. It provides data streams to the View. It also uses hooks or callbacks to update the View. It’ll ask for the data from the Model.


https://imgur.com/FCr5Mzy
