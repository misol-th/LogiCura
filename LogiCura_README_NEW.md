# LogiCura

LogiCura is a browser-based demo prototype for tracking medical supplies, identifying possible stock shortages, and planning deliveries.

## How to open the website

1. Download the `index.html` file from the LogiCura files.
2. Open the file in Chrome, Edge, or another modern web browser.
3. The demo will start automatically. No installation is required.

## How to publish the website on GitHub Pages

1. Open your GitHub repository.
2. Upload the file named `index.html` to the main (root) folder of the repository.
3. Check that the file is named exactly `index.html`.
   - Do not leave it as `index (1).html`.
   - Do not put it inside another folder.
4. Open the repository's **Settings**.
5. Select **Pages** in the left menu.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select the `main` branch and the `/ (root)` folder.
8. Click **Save**.
9. Wait for GitHub Pages to finish publishing, then click **Visit site**.

## Website features

- Dashboard with clickable inventory statistics.
- Add, edit, delete, and search inventory items.
- Stock status and estimated days of stock remaining.
- Delivery calendar with scheduled shipments.
- LogiCura demo assistant that answers selected inventory and delivery questions.
- Emergency event log where events can be entered manually.
- Editable account display name and workspace name.
- Export workspace data as a JSON file.

## Important limitations

This is an early demonstration prototype. The assistant uses simple built-in rules; it is not connected to a real AI model. The website does not receive live emergency or public-health alerts and is not connected to real hospital systems.

Use sample information only. Do not enter patient names, medical records, or other confidential information. Do not use this prototype to make clinical decisions. Always verify emergencies and supply information with authorized professionals and official services.

## Data storage

The demo saves information in the browser on the device being used. Data may not automatically appear on another device or browser. Use the **Export workspace data** option to save a copy of the current demo data.
