# Trenton MOVES— 2023 Transportation Systems Summer Research Intern

<img width="400" alt="Screenshot 2024-08-12 at 12 08 13 PM" src="https://github.com/user-attachments/assets/551e9c62-1766-476f-9dc5-0e40638a5242">

[Trenton MOVES](https://www.cartsmobility.com/trenton-moves)

## Node Network and Minimum Spanning Tree

<img width="261" alt="Screenshot 2024-08-10 at 8 51 04 PM" src="https://github.com/user-attachments/assets/01346618-f8d5-4500-9884-85cb3dbc187a">
<img width="307" alt="Screenshot 2024-08-10 at 8 51 17 PM" src="https://github.com/user-attachments/assets/e8214ae0-e0e2-4d0d-a118-0eb47e407b78">

I worked on a project involving node networks using the NetworkX library in Python. We hoped to obtain a minimum spanning tree (MST) for a random sample of 50 nodes representing kiosks. This MST would serve as a foundation for autonomous vehicle paths. 

I utilized the Djikstra Library to apply the shortest path algorithm to the 50 randomly selected nodes within the original bounding box, ensuring connectivity between nodes. The yellow paths visualize the connections between nodes and remain consistent with what we expect: many paths travel through freeways and highways to arrive at the destination node. 

[Node Network & MST Code](https://colab.research.google.com/drive/12TKCj8wS4mzPQGAeRkee_pHYRs8_TBBk?usp=sharing)

## Fleet Simulator

The final and most rewarding project involved understanding and improving the fleet simulator. A previous intern had coded it years prior, but the simulator was not commented well, making it extremely difficult to parse through. After troubleshooting and reaching out to those above me, I learned, over two weeks, that every time an ODD is selected, the simulation runs an animation.json file that has pre-computed the data. However, none of the parameters such as # of kiosks, # of vehicles, # of personTrips, etc could be changed because the function that created the animation.json file seemed inaccessible. 

<img width="625" alt="Screenshot 2024-08-10 at 9 07 46 PM" src="https://github.com/user-attachments/assets/f2f63a81-c41e-40f6-8b8c-c9b74e96541e">

Nevertheless, one of my biggest breakthroughs happened when I managed to leverage Jupyter Notebook to reverse engineer the arguments of the animation.json file, allowing me to edit these parameters. Using this information, I could better understand how the simulation reacted to increases or decreases in the number of personTrips or autonomous taxis. 

[Fleet Simulator](https://github.com/albertshi31/TrentonMOVES/blob/main/Simulation.ipynb)

<img width="416" alt="Screenshot 2024-08-10 at 9 07 06 PM" src="https://github.com/user-attachments/assets/f7e3563e-d278-4f6b-bbba-88162a076e0f">

Further, I updated vehicle pop-up boxes to show the kiosk origin, number of completed personTrips, passenger wait times, and walking distances, enhancing the assessment of the autonomous vehicle system’s convenience and viability.

## ORF467 

<img width="450" alt="Screenshot 2024-08-11 at 12 18 12 PM" src="https://github.com/user-attachments/assets/4f06965e-4397-4018-bdef-e87a1dc3b04f">
<img width="450" alt="Screenshot 2024-08-11 at 12 18 22 PM" src="https://github.com/user-attachments/assets/73669399-95e8-4106-ac1b-c5af0ca36dbc">

Using my knowledge of Seaborns, Numpy, and Pandas, I curated and analyzed Python files featuring comprehensive data and statistical visualizations that portrayed the Total Addressable Market in Trenton and user-determined Operational Design Domains. 13 students used these files in ORF467: Transportation Systems Research, Fall 2023

[ORF467_trenton](https://colab.research.google.com/drive/1ar7Wg3MvqLys85rj4cQKJs6MnulEs3H?usp=sharing)

[ORF467_animation](https://colab.research.google.com/drive/1XHDIEOPUnxyAP_18iCm7fsswaaMODdLX?authuser=1)

## Mapbox ODD Maker

<img width="628" alt="Screenshot 2024-08-10 at 8 41 07 PM" src="https://github.com/user-attachments/assets/cefb4a83-760f-42da-a1ce-4d06fc9c3ab5">

I enhanced the Operational Design Domain (ODD) Maker Interface, a website allowing users to select and define an ODD. By integrating Mapbox GL JS documentation in Python and JavaScript into the existing framework, I improved the pixel visualization of user-selected domains, enhancing accuracy in forecasting demand and optimizing geospatial mappings. Our team used the Mapbox API to obtain GEOJson data for locations such as Trenton, New Jersey, and Little Rock, Arkansas. My contributions included implementing the draw_polygon tool to enclose specific areas and adding visible markers to represent airports

## UI Improvements

<img width="341" alt="Screenshot 2024-08-10 at 7 52 12 PM" src="https://github.com/user-attachments/assets/ce77e81a-9038-4d8d-af96-c5b1980a7e77">
<img width="363" alt="Screenshot 2024-08-10 at 7 52 49 PM" src="https://github.com/user-attachments/assets/e948efef-ef31-48c1-8cf9-707bba1f50e7">

I improved the design of the Basic Economic Analysis of MOVES-Style Mobility Systems website by standardizing spacing, emphasizing headings and titles, and adding boxes around cost calculations. Additionally, I adjusted colors for better readability and modified the margins to enhance alignment. Unfortunately, my design was never implemented, and I worked on a different project. 

[Basic Economic Analysis of MOVES-Style Mobility Systems](https://www.cartsmobility.com/blog/basic-economic-analysis-of-moves-style-mobility-systems)
