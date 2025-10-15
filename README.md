# facadePattern
<h3>Software Engineering 1 | Lab Assignment 4</h3>
<h3>Problem Statement:</h3>

The <strong>Simplified Hotel Management System</strong> HotelApp needs to manage various hotel services for guest check-in and check-out. These services include valet parking for vehicles, room cleaning, and handling luggage carts. However, the HotelApp aims to interact with these services through a simplified, single interface provided by the FrontDesk. The FrontDesk class should delegate the client's requests to the appropriate service classes (Valet, HouseKeeping, Cart) while abstracting the service details from the client.

<strong>○ Class Definitions:</strong>
<ul>
<li>HotelService (Interface): Defines the common interface for all hotel services.</li><br>
<li>Valet: A service class implementing the HotelService interface, responsible for vehicle valet parking and pick-up. It includes the pickUpVehicle(plateNumber) method.</li><br>
<li>HouseKeeping: A service class implementing the HotelService interface, responsible for room cleaning. It includes the cleanRoom(roomNumber) method.</li><br>
<li>Cart: A service class implementing the HotelService interface, responsible for handling luggage cart requests. It includes the requestCart(numberOfCarts) method.</li><br>
<li>FrontDesk: The facade class that coordinates interactions between the client (HotelApp) and the individual hotel services.</li><br>
<li>HotelApp: The client class that uses the FrontDesk facade to access and utilize hotel services seamlessly.</li><br>
</ul>

<h3>UML Class Diagram:</h3>
<img width="2818" height="2168" alt="SHMS_UML" src="https://github.com/user-attachments/assets/c976efe8-445d-4c61-9574-7ea3b11f4ba8" />
