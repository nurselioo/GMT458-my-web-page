# 🌍 GMT 458 - Web GIS Assignment 1: Personal Web Page ✨

## 📖 Project Overview 🚀

This personal web portfolio is designed like an interactive autobiography with a cozy, warm "toasty pink" aesthetic 🌸. It showcases:
- 🙋‍♀️ **About Me:** An introduction to my academic journey and passion for Remote Sensing & Geomatics Engineering.
- 📚 **Favourite Books:** A structured data table featuring book covers, authors, read dates, and neat CSS hover effects.
- 🎨 **Art Things:** A responsive showcase gallery of my hand-drawn artwork and spatial sketches.
- 🗺️ **Places I Want to See:** Interactive Web GIS maps highlighting 5 dream travel destinations across the globe (Alaska ❄️, Indonesia 🌴, United Kingdom 🏰, Peru ⛰️, and South Africa 🌊).

## 🛠️ Key Technical Features & Solved Issues 💡

- **Multi-Library Web Mapping:** Implemented both **Leaflet** and **OpenLayers (OL)** maps side by side to visualize spatial points.
- **Issue 1 (Zoom Threshold):** Solved marker clutter by dynamically handling layers based on zoom levels.
- **Issue 2 (World Replication):** Prevented the infinite horizontal repetition of the globe on zoom out using bounds constraints and `wrapX: false` / `noWrap: true`.
- **CSS Animations & Layouts:** Smooth fade-in entrance animations, modern CSS grid/flexbox layouts, custom pin badges (📍), and custom typography.

## 🤖 AI Usage & Reflection Report ⏱️

In line with the assignment guidelines, here is the transparent breakdown of AI assistance:

- **Estimated Total AI Usage:** Approximately **45 – 50 minutes** ⏳
- **Key Areas of Assistance & Consultation:**
  - 🎨 **UI / Color Styling:** Fine-tuning the soft pink color palette, cohesive button states, and badge borders.
  - 🗺️ **Web GIS Map Integration:** Resolving map tile provider issues (overcoming 403 access restrictions with reliable basemaps) and configuring custom emoji pin markers (`L.divIcon`).
  - 🛠️ **Troubleshooting Layouts:** Image containment fixes in the Art Things gallery so sketches appear completely without awkward cropping.
