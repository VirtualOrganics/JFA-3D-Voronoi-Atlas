# Adding Your Screenshots

To add your screenshots (JFA1.png, JFA2.png, JFA3.png):

1. **Copy the images to the screenshots folder**:
   ```bash
   cp /path/to/JFA1.png screenshots/
   cp /path/to/JFA2.png screenshots/
   cp /path/to/JFA3.png screenshots/
   ```

2. **Add and commit the screenshots**:
   ```bash
   git add screenshots/
   git commit -m "Add demo screenshots"
   git push
   ```

3. **The images will appear in your README automatically!**

The README is already configured to display:
- JFA1.png - Main view of 3D Voronoi cells
- JFA2.png - Glass transparency mode
- JFA3.png - Single color mode

Once you push the images, they'll show up on your GitHub repository page and GitHub Pages site. 