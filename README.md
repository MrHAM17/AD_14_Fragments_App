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

### Screenshots
<table style="width:100%;"> 
  <tr> 
    <td align="center" style="width:50%;"> 
      <strong>Main Screen
        <br>
      </strong>
      <br> 
      <img src="https://github.com/MrHAM17/AD_14_Fragments_App/blob/main/Result%20Pics/01%20Main%20Screen.jpg" height="510" width="240"> 
  </td> 
    <td align="center" style="width:50%;"> 
      <strong>First Fragment
        <br>
      </strong>
      <br> 
      <img src="https://github.com/MrHAM17/AD_14_Fragments_App/blob/main/Result%20Pics/02%20First%20Fragment.jpg" height="510" width="240"> 
  </td> 
    <td align="center" style="width:50%;"> 
      <strong>First Fragment
        <br>
      </strong>
      <br> 
      <img src="https://github.com/MrHAM17/AD_14_Fragments_App/blob/main/Result%20Pics/03%20First%20Fragment.jpg" height="510" width="240"> 
  </td> 
    <td align="center" style="width:50%;"> 
      <strong>First Fragment
        <br>
      </strong>
      <br> 
      <img src="https://github.com/MrHAM17/AD_14_Fragments_App/blob/main/Result%20Pics/04%20First%20Fragment.jpg" height="510" width="240"> </td> </tr> </table>

<table style="width:100%;"> 
  <tr> 
    <td align="center" style="width:50%;"> 
      <strong>First Fragment
        <br>
      </strong>
      <br> 
      <img src="https://github.com/MrHAM17/AD_14_Fragments_App/blob/main/Result%20Pics/05%20First%20Fragment.jpg" height="510" width="240"> 
  </td> 
    <td align="center" style="width:50%;"> 
      <strong>Second Fragment
        <br>
      </strong>
      <br> 
      <img src="https://github.com/MrHAM17/AD_14_Fragments_App/blob/main/Result%20Pics/06%20Second%20Fragment.jpg" height="510" width="240"> 
  </td> 
    <td align="center" style="width:50%;"> 
      <strong>Second Fragment
        <br>
      </strong>
      <br> 
      <img src="https://github.com/MrHAM17/AD_14_Fragments_App/blob/main/Result%20Pics/07%20Second%20Fragment.jpg" height="510" width="240"> </td> </tr> </table>

---
