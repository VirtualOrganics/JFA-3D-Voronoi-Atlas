# Demo Screenshots Instructions

To add screenshots to your repository:

1. **Take Screenshots**
   - Open `index.html` in your browser
   - Try different settings:
     - Glass transparency mode with low opacity
     - Multiple colored cells
     - Animation in action
     - Different slice views

2. **Create Screenshots Folder**
   ```bash
   mkdir screenshots
   ```

3. **Add Images**
   - Save screenshots as:
     - `screenshots/main-view.png` - Default view
     - `screenshots/glass-mode.png` - Glass transparency
     - `screenshots/animation.gif` - Animated points (optional)
     - `screenshots/sliced-view.png` - Volume slicing

4. **Update README**
   Add after the badges section:
   ```markdown
   ## 📸 Screenshots

   ![Main View](screenshots/main-view.png)
   *3D Voronoi cells with edge detection*

   ![Glass Mode](screenshots/glass-mode.png)
   *True transparency mode showing internal structure*
   ```

5. **Commit and Push**
   ```bash
   git add screenshots/
   git commit -m "Add demo screenshots"
   git push
   ``` 