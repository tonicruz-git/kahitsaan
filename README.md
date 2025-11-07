# Kahit Saan / Anywhere / Cualquier Lugar
**Because "anywhere" isn't a plan.**

A multilingual restaurant and café discovery app that helps you make actual decisions when you're hungry.

## 🎯 The Problem

We've all been there:
- "Where should we eat?" 
- "I don't know, anywhere is fine."
- *30 minutes later, still haven't decided*

When people say "anywhere," they usually end up nowhere. **Anywhere** solves this by giving you real options instead of indecision.

## ✨ Features

### 🌍 Global Search
- Find restaurants, cafes, and bars anywhere in the world
- Search by city or use your current location
- Powered by OpenStreetMap data

### 🍽️ Cuisine Filtering
- Choose from 19 international cuisine types
- **Smart ordering** - Local cuisines appear first based on your location
- Filter by Italian, Japanese, Filipino, Spanish, Chinese, Thai, Mexican, Indian, and more
- Optional filtering - search all cuisines or get specific

### 🌐 Multilingual Support
Three languages, three personalities:
- **English:** "Anywhere" - Because "anywhere" isn't a plan.
- **Spanish:** "Cualquier Lugar" - Porque "cualquier lugar" no es un plan.
- **Filipino:** "Kahit Saan" - Dahil ang hirap ng kahit saan.

### 🔍 Smart Features
- Filter by type: Restaurants, Cafes, or Bars
- Filter by cuisine with location-aware ordering
- Get 3 random suggestions to make the choice easier
- Direct links to Google Maps for viewing and directions
- See cuisine types, addresses, and phone numbers (if available)
- Dark mode for comfortable browsing

## 🚀 How It Works

1. **Choose your language** - EN, ES, or FIL
2. **Set your location** - Search any city or use your current location
3. **Pick your vibe** - What are you in the mood for? (Restaurants, Cafes, or Bars)
4. **Select cuisine** (Optional) - Choose from local and international cuisines
5. **Get suggestions** - Receive 3 curated options nearby
6. **Explore** - View on map or get directions instantly

## 🛠️ Technologies Used

- **React 18** - UI framework
- **OpenStreetMap Overpass API** - Restaurant data
- **Nominatim API** - Location search and geocoding
- **Google Maps** - Map integration for viewing and directions
- **Inter Font** - Modern typography
- Pure CSS - No framework needed, custom styling

## 📱 Usage

Simply open `index.html` in any modern web browser. No build process or installation required!

### Running Locally

```bash
# Clone the repository
git clone https://github.com/tonicruz-git/kahitsaan.git

# Navigate to the directory
cd kahitsaan

# Open in your browser
open index.html

# or serve with Python
python -m http.server 8000
# Then visit http://localhost:8000
```

## 🎨 Design Philosophy

**Warm & Inviting**
- Red and orange gradients stimulate appetite
- Clean, uncluttered interface reduces decision fatigue
- Friendly, conversational copy

**Mobile-First**
- Responsive design works on all screen sizes
- Touch-friendly buttons and inputs
- Optimized for on-the-go decisions
- Horizontal scrolling for cuisine selection

**Accessible**
- High contrast ratios in both light and dark modes
- Clear, readable typography
- Semantic HTML structure
- Text truncation for long cuisine names

## 🌟 Features In Detail

### Location Search
- Real-time search suggestions as you type
- Reverse geocoding for "Use My Location"
- Displays current location clearly
- Supports cities worldwide

### Cuisine Filtering
- **19 cuisine options** including Italian, Japanese, Filipino, Spanish, Chinese, Thai, Mexican, Indian, French, American, Korean, Vietnamese, Greek, Mediterranean, Asian, Seafood, Burger, and Pizza
- **Location-aware ordering** - When you're in Spain, Spanish and Mediterranean cuisines appear first. In the Philippines, Filipino and Asian cuisines are prioritized
- **Horizontal scrolling selector** with smooth touch experience
- **Visual feedback** for selected cuisine
- **Text overflow handling** - Long cuisine names are truncated with ellipsis
- Optional filtering - choose "All" to see everything

### Smart Randomization
- Shows 3 random places each search
- Prevents decision paralysis
- Fresh results every time you search
- Filtered by both venue type and cuisine

### Dark Mode
- Automatic theme switching
- Optimized colors for both modes
- Persistent icon toggle
- Easy on the eyes for evening browsing

### Multilingual
- Seamless language switching
- Culturally appropriate translations
- Hybrid approach for Filipino (English UI with local flavor)

## 🗺️ Live Demo

Visit the live app: [https://tonicruz-git.github.io/kahitsaan/](https://tonicruz-git.github.io/kahitsaan/)

## 📄 License

MIT License - feel free to use this project however you'd like!

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve translations
- Add more cuisine types

## 🛣️ Roadmap

Potential future features:
- [ ] Price range filtering
- [ ] Save favorite places
- [ ] Share results with friends
- [ ] Opening hours display
- [ ] Dietary restrictions filtering (vegetarian, vegan, gluten-free)
- [ ] Ratings integration

## 👨‍💻 Author

Created with ❤️ to solve the eternal question: "Where should we eat?"

**GitHub:** [@tonicruz-git](https://github.com/tonicruz-git)

---

**Note:** This app uses free, public APIs (OpenStreetMap). No API keys required!
