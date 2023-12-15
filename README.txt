Vehicle Speed Detection 

1. This is a python script to detect speed of multiple vehicles on multi-lane highways.
2. It uses Haar Cascade Classifier to detect vehicles in the every nth frame.
3. It removes unnecessary portion from the image to speed up processing.
4. Two reference lines have been set, one for vehicle entry and one for exit.
5. When any vehicle in any lane crosses the entry point, the time is recorded, and the vehicle is tracked.
6. Tracking is done using centroid tracking Techniques.
7. Time is recorded when the vehicles crosses the exit line.
8. Based on the time difference, the vehicles speed is estimated.
