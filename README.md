
# 🛗 Intelligent Elevator Simulation System in C++

Welcome to the **Intelligent Elevator Simulation System** — a thoughtfully designed, console-based elevator experience built with C++. This project blends object-oriented programming with real-time user interaction to simulate an access-controlled elevator in a multi-floor building.

Step into the future of building automation — one floor at a time.

---

## ✨ Highlights

- 🔐 **Secure Entry** – Only authorized users can access the elevator  
- 🏢 **Multi-Level Architecture** – Simulates a four-floor smart building  
- ⚙️ **State-Driven Logic** – Elevator moves intelligently based on direction and floor selections  
- ⏱️ **Real-Time Interaction** – Floor selections must be made within a dynamic 5-second window  
- 🎯 **Targeted Navigation** – Skips duplicate or current floors to optimize travel  

---

## 🧠 System Architecture

### 🧩 Core Classes
- `Building`: Represents the building and its identity.
- `Person`: Handles user interaction and authorization validation.
- `Elevator`: Inherits both `Building` and `Person`, and manages the elevator state, direction, and floor logic.

### 🔄 Flow
1. User enters building and authenticates.
2. Elevator direction and current floor are selected.
3. Floor requests are made under a 5-second time constraint.
4. Elevator evaluates direction and stops logically based on input.
5. Users may continue or exit after each stop.

---

## 🌱 Future Enhancements

- 🖥️ GUI Integration with floor buttons and elevator panel  
- 🏙️ Expand support for high-rise buildings  
- 🚪 Multiple elevators with scheduling and queuing logic  
- 🛡️ Enhanced error handling and edge case validation  

---

## 📝 License

This project is licensed under the **MIT License** — open for exploration, extension, and enhancement. Contributions are welcome!

---

## 💬 Final Thoughts

This project is a blend of **object-oriented elegance** and **functional realism**, crafted for learning and expansion. Whether you're exploring class inheritance or building real-time simulations, this system lays the perfect foundation.

Happy coding — and don’t forget to press the right button before the doors close! 🚪🕒
