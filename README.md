# 🌐 NGROK TCP Connection for Free RDP Access

## 🚀 Steps to Set Up

1. **🔑 Add a Secret Variable:**
   - Go to your repository's settings on GitHub.
   - Add a new secret variable named **`NGROK_AUTH_TOKEN`**.
   - [Get your Auth Token from NGROK.com](https://ngrok.com) and add it as the value for `NGROK_AUTH_TOKEN`.
   - <!-- HTML for copy action if hosted on web -->
     ```markdown
     NGROK_AUTH_TOKEN: `your-ngrok-auth-token` <!-- Replace `your-ngrok-auth-token` with your actual token -->
     ```
     > 📝 **Tip:** Copy your NGROK token by clicking on it above.

2. **📄 Copy the [rdp.txt](./rdp.txt) File:**
   - Copy the contents of the `rdp.txt` file, which contains the necessary setup code.

3. **⚙️ Create a Workflow:**
   - In your repository, create a new workflow file under `.github/workflows`.
   - Paste the code from the `rdp.txt` file into the workflow.

4. **▶️ Run the Workflow:**
   - Start the workflow to initialize the connection.

5. **📡 Check NGROK Settings:**
   - Open your NGROK dashboard and wait until you see the TCP connection under the "Endpoints" section.

6. **💻 Connect via RDP:**
   - Open Remote Desktop on Windows.
   - Enter the NGROK URL provided in the endpoint (e.g., `2.tcp.ngrok.io:*****`).

7. **🔐 Login Credentials:**
   - **Username:** `runneradmin`
   - **Password:** `P@ssw0rd!`
   - <!-- HTML for copy action if hosted on web -->
     ```markdown
     Username: `runneradmin`
     Password: `P@ssw0rd!`
     ```
     > 📝 **Tip:** Click the username or password above to easily copy it!

8. **🎉 Success!**
   - You should now have RDP access. Enjoy!

## 📌 Notes
- Ensure the `NGROK_AUTH_TOKEN` variable is correctly added in the settings, as it’s crucial for establishing the connection.
- Check NGROK periodically to ensure the connection remains active.
