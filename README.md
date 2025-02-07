# Team Sheets Portal

A simple website that allows teams to access their respective Google Sheets through password protection.

## Setup Instructions

1. **Google Sheets Setup**
   - Create 10 different Google Sheets for each team
   - For each sheet:
     1. Click the "Share" button in the top right
     2. Click "Change to anyone with the link"
     3. Set the permission to "Viewer"
     4. Copy the sharing URL

2. **Website Configuration**
   - Open `index.html`
   - In the `teams` object, replace `YOUR_SHEET_URL_X` with the actual Google Sheet URLs
   - Customize the passwords for each team in the `teams` object
   - The default team IDs are 'team1' through 'team10'

3. **Deployment**
   - Upload the files to your web hosting service
   - Share the website URL with your teams
   - Provide each team with their respective team ID and password

## Usage

1. Teams visit the website
2. Enter their team ID (e.g., 'team1') and password
3. Upon successful login, they will see their assigned Google Sheet
4. The sheet will update in real-time as the owner makes changes

## Security Notes

- Consider changing the default passwords in the code
- The current implementation uses client-side authentication for simplicity
- For higher security, consider implementing server-side authentication

## Team Credentials

Default credentials (customize these):
- Team 1: team1 / pass1
- Team 2: team2 / pass2
- Team 3: team3 / pass3
- etc. 