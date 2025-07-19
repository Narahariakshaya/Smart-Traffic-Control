# Smart-Traffic-Control
🚦 Smart Traffic Signals Using AI (Canny-CNN System)
In busy cities, traffic jams are a daily headache—causing long waits, wasting fuel, and polluting the air. One major reason? Old-fashioned traffic lights that run on fixed timers, not actual traffic conditions.

Your project solves this with AI-powered smart traffic signals. Instead of using manual observation or expensive sensors, your system watches live traffic video and automatically adjusts signal timings depending on how many vehicles are on the road.

🔍 How it works:

📷 A traffic camera captures the road.

✂️ Canny Edge Detection enhances vehicle shapes in the image.

🧠 A Convolutional Neural Network (CNN) processes the images to detect and count vehicles.

⏱ Based on the vehicle count, the green light duration changes dynamically, helping clear busy lanes faster.

🎯 Key Benefits:

Cuts down waiting time by up to 30%.

Reduces fuel consumption and emissions.

Doesn’t need human monitoring or expensive equipment.

Works in real-time and can be expanded across many junctions.

🔧 Tech Stack:

Python, OpenCV, TensorFlow/Keras

Real-time video feed

Optional: Raspberry Pi for local deployment

🚀 Future Ideas:

Add IoT sensors or weather-awareness

Prioritize ambulances or buses

Show real-time signal info via a mobile app
