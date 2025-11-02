## AD_14_Fragments_App

### 📱 Short Description

Application demonstrating the use of **Fragments** to create a **modular and reusable** user interface that can adapt to different screen sizes.

---

### 🧩 Concepts Covered

* **Fragments** (reusable portion of UI, hosted by an Activity)
* **Fragment Lifecycle** (e.g., `onAttach`, `onCreateView`, `onResume`)
* **Frame Layout** (used as a container to display a single fragment)
* **Fragment Manager** and **Fragment Transaction** (used to manipulate fragments)
* `onCreateView()` method (used to inflate the fragment's UI)

---

### 🎯 Learning / Discovery Points

* Creating a custom fragment class that **extends `Fragment`**.
* Understanding the necessity of using `onCreateView` to inflate the fragment's XML layout and return the root `View`.
* Using the `replace()` and `commit()` methods on a `FragmentTransaction` to dynamically swap fragments at runtime.
* Recognizing the role of the `FragmentManager` in tracking fragment states within an Activity.

---

### ⚙️ App Features / Usage

* Two buttons trigger the display of either "Fragment One" or "Fragment Two".
* The activity container dynamically replaces the content based on the button clicked.

---

### 📝 Note

Fragments are crucial for creating complex and responsive applications, especially when aiming for multi-pan layouts on tablets or large screens.

---
