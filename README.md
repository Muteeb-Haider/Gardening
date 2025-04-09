# Gardening Project 🌱

This Java project simulates a simple gardening system with parcels of land that can be planted with vegetables or flowers. Each plant type has a ripening time, and only vegetables can be harvested when ripe.

## 📋 Description

- **Garden**: Contains a list of parcels, each of which can hold one plant.
- **Parcel**: Holds a plant type and the planting time (month).
- **PlantType (abstract)**: Base class for all plants. Has a ripening time and a method to check if it's a vegetable.
- **Vegetable / Flower**: Inherits from PlantType. Vegetables can be harvested; flowers cannot.
- **Specific Plants**: Includes singleton classes for Potato, Pea, Onion, Tulip, Carnation, and Rose.
- **Gardener**: Takes care of the garden (future functionality can be added).
- **Main**: Demonstrates planting and checking which parcels are harvestable in a future month.

## 🧪 Features

- Supports planting, harvesting, and checking for ripe vegetables.
- Demonstrates object-oriented programming concepts: inheritance, encapsulation, and polymorphism.
- Uses Singleton pattern for plant types.

## 🚀 How to Run

1. Import the project into NetBeans or any Java IDE.
2. Compile and run `Main.java`.
3. Observe the output showing which parcels are harvestable in a future month.

## 📂 Folder Structure

```
GardeningProject/
├── Garden.java
├── Gardener.java
├── Parcel.java
├── PlantType.java
├── Vegetable.java
├── Flower.java
├── Main.java
├── README.md
└── types/
    ├── Potato.java
    ├── Pea.java
    ├── Onion.java
    ├── Tulip.java
    ├── Carnation.java
    └── Rose.java
```

## 🧠 Summary for GitHub

This project is a simple Java simulation of a garden with parcels that can be planted with vegetables or flowers. It demonstrates object-oriented design, use of abstract classes and singletons, and supports checking which parcels can be harvested in a given month.

---

Made with 💚 for learning and fun!
