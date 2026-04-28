# EDK2 UML Documentation using PlantUML

## Overview

This repository contains **UML-based documentation for EDK2 (EFI Development Kit II)** created using **PlantUML**.

The project provides:
- Source definitions of UML diagrams (in `.txt` format using PlantUML syntax)
- Generated UML diagrams for visualization
- A BSD-2-Clause licensed structure for reuse and distribution

The goal is to improve understanding of EDK2 architecture through **clear, structured, and reproducible UML diagrams**.

---

## Repository Structure

```
EDK2_UML/
│── code/ or src/        # PlantUML source files (.txt)
│── diagrams/            # Generated UML diagrams (images)
│── LICENSE              # BSD-2-Clause License
│── README.md            # Documentation
```

---

## UML Source Files

The source files are written in **PlantUML syntax** and stored as `.txt` files.

### Why `.txt`?

- Keeps files simple and portable  
- Easily editable without requiring special tooling  
- Fully compatible with PlantUML rendering tools  

### Diagram Types Implemented

This repository includes multiple UML diagram types:

- **Use Case Diagram** – EDK II
- **Class Diagram** – Protocols and Services  
- **Sequence Diagram** – Boot Flow  
- **State Diagram** – Boot Phases  
- **Activity Diagram** – DXE Dispathcer Algorithm  
- **Component Diagrams** – Package and ARM Firmware Architecture

---

## Generating Diagrams

Diagrams were created using the **PlantUML online editor**:

https://www.plantuml.com/plantuml/uml/SyfFKj2rKt3CoKnELR1Io4ZDoSa700003

### Steps to Generate

1. Open the PlantUML website  
2. Copy the contents of a `.txt` file  
3. Paste into the editor  
4. Render the diagram  
5. Export as PNG or SVG  

---

## Example (PlantUML Source)

```
@startuml
actor User
User --> (Login)
@enduml
```

---

## Diagrams

The `diagrams/` directory contains the **rendered UML outputs**.

These diagrams help:
- Visualize EDK2 architecture  
- Understand module relationships  
- Support learning and documentation  

---

## License

This project is licensed under the **BSD 2-Clause License**.

### Key Permissions:
- Redistribution and use in source and binary forms are permitted  
- Modification is allowed  

### Conditions:
- Must retain copyright notice  
- Must include license text in redistributions  

Refer to the `LICENSE` file for full details.

---

## Use Cases

This repository can be used for:

- Understanding EDK2 system design  
- Academic or research documentation  
- Firmware architecture visualization  
- Learning UML through real-world examples  

---

## Limitations

- Diagrams are manually generated via PlantUML web interface  
- No automated build or generation pipeline included  
- Coverage of EDK2 modules may not be exhaustive  

---

## Future Improvements

- Automate diagram generation using scripts  
- Convert `.txt` files to `.puml` format (optional standardization)  
- Expand diagram coverage across more EDK2 modules  
- Integrate with documentation frameworks  

---

## Authors

**Devin Haggitt**  
https://github.com/dhaggitt


**Neelesh Reddybattula**  
https://github.com/neeleshsai23  

---

## Acknowledgments

- PlantUML for diagram generation  
- TianoCore EDK2 for architectural reference  
