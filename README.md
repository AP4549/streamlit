# Streamlit Authentication & Marks Dashboard

This is a Streamlit-based web application that allows users to sign up, log in, and input their subject marks to generate interactive reports using Plotly charts.

## Features
- **User Authentication**
  - Sign Up (stores user credentials in JSON)
  - Login with Email & Password
  - Session management with Streamlit session state
- **Marks Dashboard**
  - Enter marks for 7 subjects
  - Save marks to CSV
  - Generate interactive charts (Bar, Line, Pie) using Plotly
- **User Management**
  - Data is stored in a `credentials` folder
  - Email uniqueness check during sign-up
  - Secure password handling (plain-text for now, can be improved)
  - Logout functionality

## Installation
### Prerequisites
Ensure you have Python installed along with the following dependencies:

```bash
pip install streamlit pandas plotly
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/AP4549/streamlit.git
cd streamlit
```

2. Run the Streamlit app:
```bash
streamlit run app.py
```

3. Open the URL displayed in your terminal (usually `http://localhost:8501`).

## File Structure
```
project_root/
│── credentials/            # Stores user JSON and CSV data
│── app.py                 # Main Streamlit application
│── README.md              # Project documentation
```

## Future Enhancements
- **Secure Password Storage:** Hashing passwords with bcrypt
- **Database Integration:** Replace JSON storage with SQLite or PostgreSQL
- **Advanced Analytics:** Additional performance metrics & data insights
- **User Profile Management**

## License
This project is licensed under the MIT License.

## Contributing
Feel free to fork the repository, create a feature branch, and submit a pull request!

---
**Author:** AYUSH PANDITA  
**GitHub:** [AP4549](https://github.com/AP4549)

