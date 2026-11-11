# myAIS × iPhone Duo: Change Main Package

Interactive prototype of the myAIS "Change Main Package" screen for the iPhone Duo foldable, built from the Figma file "myAIS x iPhone Duo". The app is `index.html` plus the images in `assets/`, so there is no build step.

The prototype opens on the myAIS Home screen. Tap แพ็กเกจ (Package) in the bottom bar to open the Package page, then tap Main Package to open Change Main Package. View details on a recommended main package also opens Change Main Package with that package selected. Back returns one step: Change → Package → Home.

Change Main Package opens in details mode. Tapping a package card shows its Package Details: beside the list in Unfolded Landscape, below a sideways-scrolling row of cards in Unfolded Portrait, and on its own screen when folded. Select this package opens the review step. The compare (scale) icon in the side rail or top bar switches to compare mode, with tick boxes, the compare table and View Comparison. Back leaves compare mode and returns to details.

The switcher in the toolbar opens five views. A Single/Split toggle appears while Unfolded Portrait is selected.

- Folded Portrait: the "Closed" frame, with the punch-hole camera top-right. View Comparison opens the compare table.
- Folded Landscape: the same screen turned sideways, with the camera top-left and the side rail on the right.
- Unfolded Portrait, Single: the "Open - Portrait" frame, with the list and compare table on one scrolling page.
- Unfolded Portrait, Split: the top half stays fixed and the compare table scrolls in the bottom half, divided at the hinge.
- Unfolded Landscape: the "Open - Landscape" frame, with the list and compare table side by side.

The phone frame uses the Figma "Bezel" mockup component. The two color dots in the toolbar switch it between Night Sky and Star White.

Change package opens a review step, then a confirmation screen. The Light/Dark switch and the device color are remembered between visits.

To run it locally, use `npm run dev` and open `http://localhost:8000`.

To deploy, enable GitHub Pages for the `main` branch, root folder.

All prices and package details are illustrative prototype data.
