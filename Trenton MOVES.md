## Trenton MOVES

Transportation Systems Summer Research Intern

# UI Improvements

<img width="341" alt="Screenshot 2024-08-10 at 7 52 12 PM" src="https://github.com/user-attachments/assets/ce77e81a-9038-4d8d-af96-c5b1980a7e77">
<img width="363" alt="Screenshot 2024-08-10 at 7 52 49 PM" src="https://github.com/user-attachments/assets/e948efef-ef31-48c1-8cf9-707bba1f50e7">

I improved the design of the Basic Economic Analysis of MOVES-Style Mobility Systems website by standardizing spacing, emphasizing headings and titles, and adding boxes around cost calculations. Additionally, I adjusted colors for better readability and modified the margins to enhance alignment. Unfortunately, my design was never implemented, and I worked on a different project. 

[Basic Economic Analysis of MOVES-Style Mobility Systems](https://www.cartsmobility.com/blog/basic-economic-analysis-of-moves-style-mobility-systems)

# Mapbox ODD Maker

<img width="628" alt="Screenshot 2024-08-10 at 8 41 07 PM" src="https://github.com/user-attachments/assets/cefb4a83-760f-42da-a1ce-4d06fc9c3ab5">

I enhanced the Operational Design Domain (ODD) Maker Interface, a website allowing users to select and define an ODD. By integrating Mapbox GL JS documentation in Python and JavaScript into the existing framework, I improved the pixel visualization of user-selected domains, enhancing accuracy in forecasting demand and optimizing geospatial mappings. Our team used the Mapbox API to obtain GEOJson data for locations such as Trenton, New Jersey, and Little Rock, Arkansas. My contributions included implementing the draw_polygon tool to enclose specific areas and adding visible markers to represent airports

# Node Network and Minimum Spanning Tree

<img width="261" alt="Screenshot 2024-08-10 at 8 51 04 PM" src="https://github.com/user-attachments/assets/01346618-f8d5-4500-9884-85cb3dbc187a">
<img width="307" alt="Screenshot 2024-08-10 at 8 51 17 PM" src="https://github.com/user-attachments/assets/e8214ae0-e0e2-4d0d-a118-0eb47e407b78">

I worked on a project involving node networks using the NetworkX library in Python. We hoped to obtain a minimum spanning tree (MST) for a random sample of 50 nodes representing kiosks. This MST would serve as a foundation for autonomous vehicle paths. 

I utilized the Djikstra Library to apply the shortest path algorithm to the 50 randomly selected nodes within the original bounding box, ensuring connectivity between nodes. The yellow paths visualize the connections between nodes and remain consistent with what we expect: many paths travel through freeways and highways to arrive at the destination node. 

# Fleet Simulator

The final and most rewarding project involved understanding and improving the fleet simulator. A previous intern had coded it years prior, but the simulator was not commented well, making it extremely difficult to parse through. After troubleshooting and reaching out to those above me, I learned, over two weeks, that every time an ODD is selected, the simulation runs an animation.json file that has pre-computed the data. However, none of the parameters such as # of kiosks, # of vehicles, # of personTrips, etc could be changed because the function that created the animation.json file seemed inaccessible. 

<img width="629" alt="Screenshot 2024-08-10 at 8 58 58 PM" src="https://github.com/user-attachments/assets/a78a07d3-04cc-4790-a5f5-dd3d479e4605">

Nevertheless, one of my biggest breakthroughs happened when I managed to leverage Jupyter Notebook to reverse engineer the arguments of the animation.json file, allowing me to edit these parameters. Using this information, I could better understand how the simulation reacted to increases or decreases in the number of personTrips or autonomous taxis. 

<img width="420" alt="Screenshot 2024-08-10 at 8 59 14 PM" src="https://github.com/user-attachments/assets/e150a15a-4912-4a81-bba5-f96824135480">

Further, I updated vehicle pop-up boxes to show the kiosk origin, number of completed personTrips, passenger wait times, and walking distances, enhancing the assessment of the autonomous vehicle system’s convenience and viability.
