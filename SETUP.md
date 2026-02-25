# 🚀 Quick Setup Guide

## No Installation Required!

Just open the HTML file in any modern browser:

### Option 1: Direct Open (Easiest)
```
1. Download index.html from https://github.com/theTotesmagoats/tactical-radar-sweep-improved/raw/main/index.html
2. Double-click to open in Chrome, Firefox, Safari, or Edge
3. Click anywhere on the page to enable audio
4. Start exploring!
```

### Option 2: Local Web Server (Recommended for best experience)
```bash
# Using Python (pre-installed on most systems)
python -m http.server 8000

# Using Node.js (if you have it installed)  
npx serve

# Then open: http://localhost:8000
```

## 🎮 First Time Experience

1. **Watch the radar** - Green blips are friendly, red are hostile
2. **Click to add contacts** - Add more targets by clicking on the radar
3. **Select a contact** - Click on any blip to highlight it with yellow ring
4. **Adjust filters** - Use sliders to filter by range and depth
5. **Try keyboard shortcuts**:
   - `SPACE` for quick sonar ping
   - `S` to save current scenario
   - `L` to load a saved scenario

## 📊 What You'll See

### Real-time Radar Display
- 360° sweep rotating every ~5.3 seconds
- contacts only appear when swept over
- Green = Friendly, Red = Hostile
- Ghost blips show delayed echoes (when enabled)

### Advanced Controls
- **Range Filter**: Show only contacts within specific distances
- **Depth Filter**: Filter by underwater depth
- **Ghost Echoes**: Visualize contacts between sweeps
- **Contact Selection**: Click to highlight and see detailed telemetry

## 🛠️ Troubleshooting

### No Audio?
- Click anywhere on the page first (browser requirement)
- Check your speaker volume
- Some browsers block auto-play audio

### Radar Not Updating?
- Make sure you're using a modern browser (Chrome 90+, Firefox 88+, Safari 14+)
- Open developer console (F12) to check for errors

### Filters Not Working?
- Try adjusting sliders slowly - the system updates in real-time
- Check that min/max values are logical (min < max)

## 📚 Next Steps

1. Read `README.md` for complete feature documentation
2. Review `COMPARISON.md` to see what improved over original
3. Experiment with different filter settings and scenarios
4. Use keyboard shortcuts for faster operation

## 💡 Pro Tips

- **Training Scenario**: Save a challenging setup, then load it to practice
- **Tactical Filtering**: Show only high-value targets in specific ranges/depths
- **Quick Ping**: Press SPACEBAR instead of clicking the sonar button
- **Track Movement**: Watch ghost blips to see contact paths between sweeps

---

**Enjoy your enhanced tactical radar system!** 🛰️