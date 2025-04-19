# SwiftVote

SwiftVote is a secure, efficient digital voting system built in Python that provides a seamless voting experience while maintaining the integrity and confidentiality of the electoral process.

## Features

- **Secure Authentication**: Multi-layered security with facial recognition and password verification
- **User-Friendly Interface**: Simple and intuitive voting process accessible to all users
- **Real-Time Results**: Instant counting and visualization of voting outcomes
- **Admin Dashboard**: Comprehensive management tools for election officials
- **Data Encryption**: End-to-end encryption to protect voter information
- **Audit Trail**: Complete logging of all system activities for transparency

## System Requirements

- Python 3.8+
- OpenCV for facial recognition
- SQLite for database management
- Additional dependencies listed in `requirements.txt`

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/NANDAGOPALNG/SwiftVote.git
   cd SwiftVote
   ```

2. Create and activate a virtual environment (recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Set up the database:
   ```
   python setup_db.py
   ```

## Usage

### For Voters

1. Launch the voter application:
   ```
   python voter_app.py
   ```

2. Complete facial recognition and password verification
3. Cast your vote securely
4. Receive confirmation of your vote submission

### For Administrators

1. Launch the admin dashboard:
   ```
   python admin_app.py
   ```

2. Log in with admin credentials
3. Access tools for:
   - Managing voter registrations
   - Setting up elections
   - Monitoring voting progress
   - Analyzing results
   - Generating reports

## Project Structure

```
SwiftVote/
├── admin_app.py         # Admin dashboard application
├── database/            # Database scripts and files
├── encryption/          # Security and encryption modules
├── face_recognition/    # Facial recognition implementation
├── static/              # Static assets (CSS, images)
├── templates/           # HTML templates
├── tests/               # Test suite
├── utils/               # Utility functions
├── voter_app.py         # Voter-facing application
├── requirements.txt     # Project dependencies
└── setup_db.py          # Database setup script
```

## Security Measures

SwiftVote implements several security measures:
- Biometric verification
- Two-factor authentication
- End-to-end encryption
- Session management
- Prevention of double voting
- Audit trails
- Regular security updates

## Contributing

We welcome contributions to SwiftVote! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Nandagopal NG - [GitHub Profile](https://github.com/NANDAGOPALNG)

Project Link: [https://github.com/NANDAGOPALNG/SwiftVote](https://github.com/NANDAGOPALNG/SwiftVote)
