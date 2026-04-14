# 🔢 Character Counter

[](https://opensource.org/licenses/MIT)
[](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[](https://developer.mozilla.org/en-US/docs/Web/HTML)
[](https://developer.mozilla.org/en-US/docs/Web/CSS)

**Character Counter** is a high-utility, minimalist web tool designed for real-time text analysis. Built with vanilla JavaScript, it provides immediate feedback on input length, helping users adhere to character limits for social media, SEO metadata, or technical documentation with zero latency.

> ⚡ **Mission:** To provide a responsive and lightweight text-tracking solution by leveraging event-driven programming.

-----

## 🧠 Overview

The Character Counter is a fundamental demonstration of reactive UI design using native web technologies. It focuses on:

  * ⚡ **Performance:** Leveraging the `input` event for instantaneous updates.
  * 🧠 **Event Logic:** Efficiently capturing and processing user keystrokes.
  * 🎯 **Responsive Feedback:** Maintaining a clean, distraction-free interface across all device sizes.

-----

## 💡 The Problem & The Solution

**The Problem:** Many platforms (like X/Twitter or SMS) impose strict character limits. Manually checking the length of a draft or relying on slow, server-side counters leads to a disjointed writing experience and potential errors.

**The Solution:** This application provides a "live-sync" experience. By monitoring the text node directly in the browser, it calculates and renders the count the moment a character is typed or deleted, ensuring the user is always aware of their current status.

-----

## ✨ Features

  * **Live Counting:** Dynamic updates as you type, paste, or delete text.
  * **Instant Reset:** Automatically adjusts to zero when the input is cleared.
  * **Responsive Layout:** A fluid design that works perfectly on both mobile browsers and desktop monitors.
  * **Lightweight Footprint:** Optimized code that loads instantly and consumes minimal system resources.

-----

## ⚙️ How It Works: The Logic Flow

1.  **Selection:** JavaScript selects the `textarea` or `input` element and the `counter` display element.
2.  **Event Listening:** An `input` event listener is attached to the text field to detect any content change.
3.  **Calculation:** The script accesses the `.value.length` property of the input element.
4.  **DOM Rendering:** The current length is injected into the counter's `innerText`, updating the UI in real time.

-----

## 🛠 Tech Stack

| Category | Technology |
| :--- | :--- |
| **Structure** | HTML5 (Semantic Elements) |
| **Styling** | CSS3 (Flexbox for centering & Layout) |
| **Logic** | Vanilla JavaScript (ES6+ Event Listeners) |

-----

## 📊 Engineering Highlights

  * **Event Efficiency:** Used the `input` event instead of `keyup` to ensure the counter accurately tracks actions like right-click pasting or text dragging.
  * **Low Latency:** Optimized DOM manipulation to prevent UI stuttering during rapid typing.
  * **Zero Dependencies:** Achieved high performance without the overhead of heavy frameworks like React or Vue.

-----

## 🧪 Edge Case Handling

  * **Empty States:** Specifically handles empty strings to ensure the counter displays `0`.
  * **Whitespace Awareness:** Accurately counts spaces and newlines as characters, reflecting true string length.
  * **Rapid Input:** Handles high-speed typing and bulk pasting without lag.

-----

## ⚙️ Setup & Installation

This is a standalone frontend project. No installation or build steps are required:

1.  **Clone the Repo**

    ```bash
    git clone https://github.com/AsifpMulla123/character-counter.git
    cd character-counter
    ```

2.  **Launch**
    Open `index.html` in any modern web browser to start counting characters immediately.

-----

## 🔮 Future Roadmap

  - [ ] **Word Counter:** Add a secondary display to track total word count.
  - [ ] **Visual Limits:** Implement a progress bar that changes color as the user nears a defined limit.
  - [ ] **Text Analysis:** Include basic statistics like reading time or paragraph count.
  - [ ] **Persistence:** Save the current text to `localStorage` so it remains after a page refresh.

-----

## 🤝 Connect With Me

  * **LinkedIn:** [linkedin.com/in/asif-p-mulla](https://linkedin.com/in/asif-p-mulla)
  * **Email:** [asifmullaofficial@gmail.com](mailto:asifmullaofficial@gmail.com)

-----

**If you found this utility helpful, please give it a ⭐\!**
