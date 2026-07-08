# 🎲 RNGdle Unlimited

An infinite version of RNGdle - Roll random numbers, collect badges, and compete with friends!

## What is RNGdle Unlimited?

RNGdle Unlimited is a web-based random number game where players:
- **Roll** random numbers from 0 to 1,000,000
- **Discover** what badges their numbers earn based on mathematical properties
- **Collect** unique badges over time
- **Earn** Entropy Points (EP) based on badge rarity

Unlike the original RNGdle (limited to 1 roll per day), this unlimited version lets you play as much as you want!

## Features

✨ **20+ Unique Badges**
- Prime numbers, palindromes, perfect squares, fibonacci numbers, and more
- Each badge has a rarity tier (Common → Mythic)
- Unlocking badges based on mathematical properties

📊 **Statistics Tracking**
- Total rolls counter
- Cumulative Entropy Points
- Badge collection progress
- Roll history (last 50 rolls)

🏆 **Badge System**
- 6 rarity tiers: Common, Uncommon, Rare, Epic, Anomaly, Mythic
- Badge collection with visual progress
- EP rewards based on rarity

💾 **Persistent Storage**
- All game data saved locally using browser localStorage
- Your progress is automatically saved

📱 **Responsive Design**
- Works on desktop, tablet, and mobile
- Dark theme optimized for gaming

## Getting Started

### Online (No Installation)
Simply open `rngdle-unlimited.html` in any modern web browser!

### Development Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/rngdle-unlimited.git
   cd rngdle-unlimited
   ```

2. **Open the game**
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Or using Node.js (if you have http-server installed)
   npx http-server
   ```

3. Visit `http://localhost:8000` in your browser

## Available Badges

| Badge | Emoji | Rarity | Description |
|-------|-------|--------|-------------|
| Prime Time | 🔢 | Uncommon | A prime number |
| Palindrome | 🔄 | Uncommon | Reads same forwards and backwards |
| Perfect Square | 📦 | Rare | A perfect square number |
| Perfect Cube | 🎲 | Rare | A perfect cube number |
| Fibonacci | 🌀 | Epic | Part of Fibonacci sequence |
| Power of Two | ⚡ | Rare | A power of 2 |
| Repeating | 🔁 | Uncommon | Has repeating digits |
| All Same | 🌟 | Epic | All digits are identical |
| Meme Number | 😂 | Rare | Famous meme numbers (69, 420, 666, etc) |
| Lucky 7 | 🍀 | Uncommon | Divisible by 7 or contains 7 |
| Lucky 8 | ∞ | Uncommon | Divisible by 8 or contains 8 |
| Ascending | 📈 | Epic | Digits in ascending order |
| Descending | 📉 | Epic | Digits in descending order |
| Zero Hero | 0️⃣ | Uncommon | Contains the digit 0 |
| Odd Squad | 🤪 | Rare | All digits are odd |
| Even Steven | 🎯 | Rare | All digits are even |
| Triangular | △ | Epic | A triangular number |
| Perfect | ✨ | Mythic | A perfect number (EXTREMELY rare) |
| Round Number | ⭕ | Common | Ends in zeros |
| Million Dollar | 💰 | Mythic | Rolled exactly 1,000,000 |

## How Entropy Points Work

Each badge earned contributes EP based on its rarity:
- Common: 10 EP
- Uncommon: 25 EP
- Rare: 50 EP
- Epic: 100 EP
- Anomaly: 250 EP
- Mythic: 500 EP

Your roll's rarity is determined by total EP:
- **Trash**: 0-9 EP (Bottom 1%)
- **Common**: 10-24 EP (Bottom 50%)
- **Uncommon**: 25-49 EP (Top 50-25%)
- **Rare**: 50-99 EP (Top 25-10%)
- **Epic**: 100-249 EP (Top 10-5%)
- **Anomaly**: 250-499 EP (Top 5-1%)
- **Mythic**: 500+ EP (Top 1%)

## Technical Details

- **Framework**: Vanilla HTML/CSS/JavaScript (no dependencies)
- **Storage**: Browser localStorage
- **Compatibility**: Works in all modern browsers (Chrome, Firefox, Safari, Edge)
- **File Size**: Single HTML file (~25 KB)

## Data Privacy

All game data is stored locally in your browser. No data is sent to any server. Your rolls, badges, and statistics are yours alone.

## Contributing

Found a bug? Want to add more badges? Contributions are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-badge`)
3. Commit your changes (`git commit -m 'Add amazing badge'`)
4. Push to the branch (`git push origin feature/amazing-badge`)
5. Open a Pull Request

## Ideas for Contributions

- More badge types (Armstrong numbers, Kaprekar numbers, etc.)
- Leaderboard system (with optional cloud sync)
- Achievement milestones
- Different number range modes
- Badge sharing feature
- Dark/Light theme toggle
- Sound effects and animations
- Mobile app version

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Inspired By

- [RNGdle](https://www.rngdle.com/) - The original daily RNG game

## Support

- Found an issue? Open a GitHub Issue
- Have a suggestion? Start a Discussion
- Want to chat? Join our Discord (coming soon!)

---

**Made with 💜 for random number enthusiasts**
