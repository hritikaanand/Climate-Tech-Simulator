# Climate Tech Simulator
A simple and student-friendly **Java project** that models a city’s energy and transport emissions — showing how climate policies and technology choices impact sustainability.

## Project Overview
This Java-based simulator calculates and compares emissions from:
- Different **energy sources** (Solar, Coal, etc.)
- Various **vehicles** (Cars, Buses)
- **Policies** that reduce emissions (like renewable incentives)

It also shows results using **ASCII charts** for easy visualization.

## 🏗️ Code Structure
| Class | Description |
|--------|--------------|
| `EnergySource` | Represents energy types and emissions |
| `Vehicle` | Models transportation emissions |
| `Policy` | Applies emission reduction |
| `Optimizer` | Finds the best low-emission energy mix |
| `ClimateTechInnovator` | Main program connecting everything |

## 🧠 Reflection
> Building this project helped me explore how coding can solve real sustainability problems.  
> It strengthened my problem-solving and system design skills while deepening my curiosity about computational sustainability — a field Cornell strongly promotes.

## 📊 System Diagram
       ┌────────────────────────────┐
       │   ClimateTechInnovator     │
       │  (Main Controller)         │
       └─────────────┬──────────────┘
                     │
  ┌──────────────────┼──────────────────┐
  │                  │                  │
  ▼                  ▼                  ▼
+---------------+     +-------------+     +-------------+
| EnergySource  |     | Vehicle     |     | Policy      |
|---------------|     |-------------|     |-------------|
| cost/unit     |     | emission/km |     | reduction%  |
| emissions     |     | count       |     +-------------+
| units         |     | avgDistance |      
+---------------+     +-------------+      
     |                    |                  |
     v                    v                  v
 getTotalCost()     getTotalEmissions()   applyReduction()
     |                    |
     +--------------------------------------+
                             |
                             v
                     +----------------+
                     |   Optimizer    |
                     |----------------|
                     | Sorts sources  |
                     | Applies budget |
                     | Minimizes CO₂  |


## 🪪 License
This project is licensed under the **MIT License** — feel free to use and modify it for educational purposes.


