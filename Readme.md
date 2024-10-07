
<h1>1. Navbar</h1>
•	Implement the navbar as per the Figma design.
•	Ensure it is responsive across Desktop, Tablet, and Mobile devices.
•	The navbar should collapse into a mobile menu on smaller screens.
2. Banner Section
•	Design the banner section as per Figma design.
•	Include a "View More" button that, when clicked, scrolls down to the “Adopt Your Best Friend” section.
•	Ensure the banner is fully responsive.
3. Adopt Your Best Friend Section
•	Left Side:
o	Display 4 dynamic categories below the section title and subtitle, fetched from the provided API.
o	Add a "Sort By Price" button on the right, with a subtitle on the left, as per the design.
o	By default, show all available pets, with the active category styled according to Figma.
o	After clicking on a category, fetch and display pets from that category in a grid layout.
o	If no pets are available for a category, show a meaningful message.
o	Each card must display the following:
	Thumbnail/Image
	Pet Name
	Breed
	Birth Date
	Gender
	Price
	Buttons: "Like", "Adopt", and "Details"
o	If any field is missing from the API response, handle it by displaying a placeholder or meaningful message.
•	Right Side:
o	Clicking the "Like" button should add the pet's thumbnail to the right-side grid.
o	Display a 2-column layout for liked pet thumbnails.
4. Modal Window
•	When the "Details" button is clicked, open a modal that displays all pet information like figma
•	The modal should close when the user clicks close button.
5. Footer
•	Implement the footer as per the Figma design.
•	Ensure it is responsive.
6. Responsive Design
•	The entire platform must be responsive and functional on Desktop, Tablet, and Mobile devices.
•	Use Tailwind CSS breakpoints for responsiveness.
Challenges
1. Loading Spinner
•	Display a loading spinner for at least 2 seconds when fetching data from the API.
2. Sort by Price
•	Implement sorting functionality for pets. When the "Sort by Price" button is clicked, sort pets in descending order based on price . sorting on active category is recommended but if you can sort all the data you will get full mark for this requirement.
3. Adopt Button Behavior
•	Implement an adoption process. When the "Adopt" button is clicked, show a countdown (3, 2, 1) and then change the button text to "Adopted."
4. Handle Null or Undefined Values
•	If any values from the API (e.g., pet breed, birth date) are null or undefined, display a placeholder or relevant message instead of leaving it blank.
5. A Beautyfull README.md File
Ensure the final project includes a README.md file with the following details:
•	Project name.
•	Short description of the project.
•	5 key features of the project.
•	ES6 features used.
•	Live link to the deployed project.
What to Submit
•	Your Private Github Repo Link
•	Your Live Link
Best of Luck
https://github.com/programming-hero-web-course2/b10a6-pet-adoption-kobirul5

pet adoption

This project is made for pet adoption. This page is made so that anyone can adopt their favorite pet from now on. The aim of this project is to make it easy for anyone to adopt a pet.

1.The category button can be used to select specific categories of pets
2. By clicking on View More button, the Mines section can be taken out
3. Sort by price button can be used to extract cards according to price
4. The details button will bring out the details of the pet
5. Click the like button to add a pet thumbnail

1 . Array function
2. setTimeOut  function
3. setIntervel function
4. sort function
5. forEach Loop 
6. back tic (``)
7
