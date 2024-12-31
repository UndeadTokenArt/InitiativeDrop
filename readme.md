# Drag and Drop with Initiative Tracker

This project combines a drag-and-drop file preview functionality with an initiative tracker system. The drag-and-drop feature allows users to upload and preview image and video files. The initiative tracker is designed to track player initiatives, which is particularly useful for role-playing games.

## Features

### Drag and Drop File Preview
- Users can drag and drop image or video files onto the drop zone.
- The uploaded files are previewed within the drop zone.
- Only image and video files are supported.

### Initiative Tracker
- Users can input player names and their initiative scores.
- The tracker displays a list of players and their initiatives.
- The list is automatically sorted by initiative scores in descending order.
- Users can highlight player rows to indicate different statuses (highlighted, critical, dead).
- A reset button to clear the initiative list.

## Usage

1. Open the `display.html` file in a web browser.
2. To upload a file, drag and drop an image or video file onto the drop zone. The file will be previewed within the drop zone.
3. To add a player to the initiative tracker:
   - Enter the player's name in the "Name" field.
   - Enter the player's initiative score in the "Initiative" field.
   - Click the "Add" button to add the player to the list.
4. To highlight a player row, click on the row. Clicking multiple times will cycle through the statuses (highlighted, critical, dead).
5. To reset the initiative tracker, click the "Reset" button.

## File Structure

- `display.html`: The main HTML file containing the structure of the web page and the embedded CSS and JavaScript.
- Inline CSS: Styles for the web page elements.
- Inline JavaScript: Logic for the drag-and-drop functionality and the initiative tracker.

## Customization

### CSS
The styles for the web page are defined within the `<style>` tag in the `display.html` file. You can customize the appearance by modifying the CSS rules.

### JavaScript
The logic for the drag-and-drop functionality and the initiative tracker is implemented within the `<script>` tag in the `display.html` file. You can enhance or modify the functionality by editing the JavaScript code.

## License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).
