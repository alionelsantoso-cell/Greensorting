# ♻️ GreenSorting

### AI-Powered Smart Recycling & Online Recycling Exchange

**GreenSorting** is an innovative recycling exchange platform designed around the core idea of **“Reusing and Reducing Waste.”** The project combines an online recycling marketplace with an AI-powered smart sorting system to encourage people to recycle, reuse valuable materials, and reduce unnecessary waste.

Instead of allowing recyclable materials such as plastic bottles, cans, glass bottles, furniture, and other reusable items to end up in landfills, GreenSorting provides a way for users to sort, exchange, and make use of these materials.

What makes GreenSorting unique is its **rewarding system**. Users can earn points by actively sorting and recycling materials. These points can eventually be converted into money, providing a practical incentive for people to participate in sustainable recycling practices.

> **GreenSorting — Turning waste into value. ♻️**

---

# 🏆 Codeavour 6.0

GreenSorting was created as our project for **Codeavour 6.0**, an international coding and AI competition.

We took GreenSorting through every stage of the competition, progressing from the:

**🌐 Online Phase → 🗺️ Regional Phase → 🇮🇩 National Phase → 🌍 Global Phase**

Our team successfully advanced through the **online, regional, and national phases (where we got 2nd place)**, ultimately reaching the **global phase of Codeavour 6.0** with GreenSorting.

This journey gave us the opportunity to develop our idea further, improve our prototype, and present our approach to using AI and technology to address real-world environmental challenges.

> **From an idea to a prototype, and from the online phase all the way to the global phase — GreenSorting represents our journey in Codeavour 6.0.**

---

## 🌱 The Idea Behind GreenSorting

Many items that are thrown away still have value. GreenSorting aims to change the way people think about waste by encouraging them to:

* ♻️ Reuse materials instead of throwing them away
* 🌍 Reduce unnecessary waste
* 🔄 Exchange recyclable and reusable items
* 🤖 Use technology to make recycling easier
* ⭐ Earn rewards for participating in recycling activities
* 👨‍👩‍👧‍👦 Encourage sustainable habits within communities

Through GreenSorting, recycling becomes more than an environmental responsibility. It becomes an activity that can provide meaningful benefits to individuals and communities.

---

# 🤖 AI Smart Sorting System

GreenSorting also includes a physical **smart recycling bin prototype** powered by **PictoBlox, Arduino, and servo motors**.

The system uses a laptop camera and PictoBlox to identify recyclable materials. After the material is detected, Arduino controls the appropriate servo motor to open the corresponding disposal hole.

### Supported Materials

| Material          | Disposal Hole |
| ----------------- | ------------- |
| 🧴 Plastic Bottle | Plastic       |
| 🥫 Can            | Can           |
| 🍾 Glass Bottle   | Glass         |

---

## ⚙️ How It Works

The GreenSorting smart recycling system follows these steps:

```text
User Selects Material
        ↓
Places Material in Scanning Area
        ↓
Laptop Camera Captures the Object
        ↓
PictoBlox Detects the Material
        ↓
Material Type is Identified
        ↓
Arduino Receives the Result
        ↓
Servo Motor Opens the Correct Hole
        ↓
User Deposits the Material
        ↓
Material is Stored in the Box
        ↓
User Receives Recycling Points
        ↓
Points Can Be Converted Into Money
```

---

# 🧠 PictoBlox & Computer Vision

The project uses **PictoBlox** as the main software for the AI-based object detection system.

A laptop is positioned in front of the recycling box with its camera facing the scanning area. When an item is placed in front of the camera, PictoBlox analyzes the image and determines which category the item belongs to.

To improve detection reliability, the prototype includes a **white background section** behind the scanning area. This provides a more consistent background for the camera and helps the system distinguish the recyclable item.

### Detection Process

1. The user places a recyclable item in the scanning area.
2. The laptop camera captures the item.
3. PictoBlox analyzes the camera image.
4. The system identifies the material category.
5. The corresponding disposal hole is selected.
6. Arduino activates the appropriate servo motor.
7. The lid opens so the user can deposit the item.

---

# 🔧 Hardware Prototype

The physical prototype is built using an **acrylic box** with three separate disposal holes.

### Main Components

| Component          | Purpose                                |
| ------------------ | -------------------------------------- |
| 💻 Laptop          | Runs PictoBlox and provides the camera |
| 📷 Camera          | Scans recyclable materials             |
| 🤖 PictoBlox       | AI / Computer Vision detection         |
| 🔌 Arduino         | Controls the hardware mechanism        |
| ⚙️ Servo Motors    | Open and close disposal lids           |
| 📦 Acrylic Box     | Holds the sorted recyclable materials  |
| ⬜ White Background | Improves object detection consistency  |

---

# ⚙️ Arduino & Servo Mechanism

After PictoBlox identifies the material, the system determines which disposal hole should be opened.

Arduino controls the servo motors responsible for the lids.

For example:

```text
Plastic Detected
      ↓
Arduino
      ↓
Plastic Servo Activated
      ↓
Plastic Lid Opens
```

The same process is used for cans and glass bottles.

After the item has been deposited, the servo can return the lid to its original closed position.

---

# ⭐ Reward System

GreenSorting introduces a reward system to encourage active participation in recycling.

Users receive **points** when they successfully sort and deposit recyclable materials.

These points can accumulate over time and can eventually be converted into money.

```text
♻️ Recycle
     ↓
⭐ Earn Points
     ↓
📈 Accumulate Points
     ↓
💰 Convert Points into Money
```

The reward system provides a practical incentive for users to participate in sustainable waste management.

For example, students could use their recycling earnings to help cover school-related expenses.

---

# 🌍 Environmental Impact

GreenSorting is designed to contribute to a more sustainable community by helping reduce the amount of recyclable material that is unnecessarily discarded.

The project promotes:

* Reduced landfill waste
* Increased recycling participation
* Reuse of valuable materials
* Better waste sorting habits
* Community participation
* Sustainable living
* Technology-assisted recycling

The goal is to make recycling **simple, accessible, and rewarding**.

---

# 💡 What Makes GreenSorting Different?

GreenSorting combines several ideas into one system:

### ♻️ Recycling

Users can sort and deposit recyclable materials instead of throwing them away.

### 🤖 Artificial Intelligence

PictoBlox helps identify recyclable materials using computer vision.

### ⚙️ Automation

Arduino and servo motors automatically control the appropriate disposal hole.

### ⭐ Rewards

Users receive points for participating in recycling activities.

### 🔄 Recycling Exchange

The online platform provides a way for users to exchange recyclable and reusable materials with others.

Together, these features create a system that connects **technology, sustainability, and community participation**.

---

# 🛠️ Technologies Used

* **PictoBlox**
* **AI / Computer Vision**
* **Arduino**
* **Servo Motors**
* **Laptop Camera**
* **Acrylic Prototype**
* **Online Marketplace Concept**

---

# 🎥 Project Demonstration

Watch the GreenSorting prototype demonstration:

**▶️ YouTube Demo**

https://youtu.be/KF8tm80juVs

---

# 📊 Project Presentation

View the GreenSorting presentation slides:

**📑 Presentation**

https://drive.google.com/open?id=1XwL2Xh-2zVr2unTOiuviiwSjQ-zbW9NI

---

# 🎯 Our Vision

We envision a world where recycling is not simply a responsibility, but a **rewarding and meaningful experience**.

GreenSorting aims to empower individuals and communities to make better use of recyclable materials while reducing environmental harm.

By combining AI, hardware automation, recycling, and a reward system, GreenSorting demonstrates how technology can help create more sustainable communities.

> **Detect → Sort → Reuse → Reward**

### 🌱 Together, we can build a greener and more sustainable future.

---

## 👥 Project

**Project Name:** GreenSorting
**Competition:** Codeavour 6.0
**Category:** AI, Recycling & Sustainability
**AI Platform:** PictoBlox
**Hardware:** Arduino + Servo Motors
**Prototype:** Acrylic Smart Recycling Box

**Competition Journey:**
🌐 Online → 🗺️ Regional → 🇮🇩 National → 🌍 Global

**#GreenSorting #Codeavour6 #Recycling #Sustainability #AI #PictoBlox #Arduino #ComputerVision #SmartRecycling**
