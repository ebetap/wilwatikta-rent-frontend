### Wilwa-Tikta Rent Frontend

**Wilwa-Tikta Rent Frontend** is the user interface for the Wilwa-Tikta Rent online rental application.

### Key Features
- **Homepage:** Displays available rental items.
- **Search & Filter:** Find items by category and criteria.
- **Item Details:** View details and make reservations.
- **Order Management:** Manage user orders.
- **User Profile:** Manage profile and account settings.
- **Review System:** Write and read item reviews.
- **API Integration:** Connects to the backend for data and actions.

### Requirements
- Node.js
- NPM

### Installation & Running
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ebetap/wilwatikta-rent-frontend.git
   cd wilwa-tikta-frontend
   ```
2. **Install Dependencies:**
   ```bash
   npm install
   ```
3. **Configuration:** Create a `.env` file with:
   ```bash
   REACT_APP_API_BASE_URL=https://api.wilwatikta.com/api/v1
   ```
4. **Run the Application:**
   ```bash
   npm start
   ```
   The app will run on `http://localhost:3000`.

5. **Build for Production:**
   ```bash
   npm run build
   ```

### Project Structure
- `src/`
  - `components/`: UI components
  - `pages/`: Application pages
  - `styles/`: CSS/SCSS files
  - `utils/`: Utility functions and API helpers
  - `App.js`: Entry point
- `public/`
  - `index.html`: HTML template
  - `favicon.ico`: App icon

### Contribution
Contributions are welcome. Please create a pull request or open an issue.

### License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

### Contact
For questions or assistance, contact us at [artechspirit@gmail.com](mailto:artechspirit@gmail.com).
