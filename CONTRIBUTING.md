# Contributing to RNGdle Unlimited

Thank you for your interest in contributing! This document provides guidelines and instructions for contributing.

## How Can I Contribute?

### Reporting Bugs
1. Check if the bug has already been reported in [Issues](../../issues)
2. Provide a clear, descriptive title
3. Describe the exact steps to reproduce the bug
4. Include any error messages or screenshots
5. Mention your browser and OS

### Suggesting Enhancements

#### New Badge Ideas
New badges are welcome! When suggesting:
- Describe the mathematical property or pattern
- Suggest a name and emoji
- Estimate the rarity (common to mythic)
- Explain why it would be interesting

Example:
```
Armstrong Number Badge
Emoji: 💎
Rarity: Epic
Description: Numbers equal to the sum of their digits each raised to the power of the number of digits
Examples: 153 (1³+5³+3³), 370, 9474
```

#### Feature Requests
- Describe the use case
- Provide examples of how it would work
- Consider performance impact

### Code Contributions

1. **Fork the repository**
   ```bash
   git clone https://github.com/yourusername/rngdle-unlimited.git
   cd rngdle-unlimited
   ```

2. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make your changes**
   - Keep the single HTML file structure
   - Follow the existing code style
   - Add comments for complex logic
   - Test in multiple browsers

4. **Commit with clear messages**
   ```bash
   git commit -m "Add: descriptive message about your changes"
   ```

5. **Push and create a Pull Request**
   ```bash
   git push origin feature/your-feature-name
   ```

## Development Guidelines

### Code Style
- Use 4 spaces for indentation
- Use semicolons
- Use meaningful variable names
- Add comments for non-obvious code

### Adding New Badges

1. Create a check function:
   ```javascript
   function isMyBadge(n) {
       // Mathematical check
       return true/false;
   }
   ```

2. Add to BADGES object:
   ```javascript
   my_badge: {
       name: "Badge Name",
       emoji: "🎯",
       rarity: "rare", // common, uncommon, rare, epic, anomaly, mythic
       description: "What this badge represents",
       check: (n) => isMyBadge(n)
   }
   ```

3. Test edge cases (0, 1, large numbers)

### Performance Considerations
- Check functions should be fast (no infinite loops)
- Avoid heavy computations for every roll
- Test with larger number ranges if expanding

### Testing

Before submitting:
1. Test in Chrome, Firefox, Safari
2. Test on mobile/tablet
3. Verify badges unlock correctly
4. Check localStorage functionality
5. Test the clear history button
6. Verify calculation accuracy

## Pull Request Process

1. Update the README.md if needed
2. Update the badge table if adding badges
3. Provide a clear description of changes
4. Reference any related issues
5. Be open to feedback and review

## Questions?

- Open an Issue for discussion
- Be respectful and constructive

Thank you for contributing! 🎲
