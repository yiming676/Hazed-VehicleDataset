#Hazed-Vehicle-Datasets

In this project, I have uploaded a foggy vehicle dataset. The original dataset is a niche collection from India, known as VehicleDatasets(If you are interested in obtaining this dataset, you can find it in my other projects). I have applied an exponential hazification model to this original dataset to introduce fog effects. Additionally, the package includes YOLO format annotations corresponding to each image, encompassing a total of 21 vehicle categories.

List of all categories is provided.

names:
  0: human hauler
  1: bicycle
  2: bus
  3: suv
  4: policecar
  5: ambulance
  6: truck
  7: auto rickshaw
  8: three wheelers (CNG)
  9: van
  10: scooter
  11: minibus
  12: army vehicle
  13: taxi
  14: rickshaw
  15: garbagevan
  16: car
  17: pickup
  18: motorbike
  19: wheelbarrow
  20: minivan

The dataset has several advantages:
1. It features a wide variety of vehicles with diverse shapes and forms, which can enhance the robustness of the model when trained.
2. It includes images with both dense and sparse vehicle populations, which can be particularly helpful for specific experimental purposes.

However, there are also some drawbacks:
The original dataset was captured under poor environmental conditions and features older models of vehicles, which may not be effectively detected by the current state-of-the-art vehicle detection systems.

Please use this dataset with discretion.
