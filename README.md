# LinkedIn-automation
Creating an automated system that monitors competitors' LinkedIn activity, specifically targeting decision-makers' new connections. Based on the 'About Us' section, job description, or recent posts of these new connections, the automation would generate a hyper-personalized connection request to be sent from your LinkedIn account. 
# Install
python -m pip install naas_drivers
# Steps
1. Get Competitors' company followers:
   - Import libraries
   - Setup Variables
   - Setup Naas scheduler
   - Create Model
   - Update followers
   - Save dataframe in CSV
   - Add dependency to production
2. Send connection requests with personalized message to company followers:
   - Import libraries
   - Setup variables
   - Setup Naas
   - Get followers from company
   - Get LinkedIn invitations sent
   - Get profile checked and already in your network
   - Get invitations sent (CSV)
   - Get new invitation
   - Send invitation
   - Save company followers in CSV
   - Display invitations sent

Build a function to track new connections of competitor's decision makers. This involves understanding LinkedIn's API. Upon identifying a new connection, the script
would analyze their profile data, specifically the 'About Us' section, job description, or recent posts. Based on the analysis, the script would generate a
hyper-personalized connection request. The script would then send the connection request from your LinkedIn account with the generated personalized message.


