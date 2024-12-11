# Creating a Terms of Service file for Volcano Music in Markdown format.
tos_content = """
# Terms of Service for Volcano Music

## 1. Introduction  
Welcome to **Volcano Music**! By using this bot, you agree to the following Terms of Service. If you do not agree, please do not use this bot.

## 2. Description of Service  
**Volcano Music** is a Discord bot that provides music playback and other related features. It is designed to enhance your Discord server experience by allowing users to listen to high-quality music.

## 3. User Responsibilities  
- Users must comply with Discord's [Terms of Service](https://discord.com/terms) and [Community Guidelines](https://discord.com/guidelines).  
- Users agree not to use the bot for any illegal, harmful, or malicious activities.  
- Users are responsible for ensuring their actions while using the bot comply with all applicable laws and server rules.

## 4. Data Collection  
- **Volcano Music** may collect user data, such as user IDs, server IDs, and usage logs, to ensure proper functionality.  
- We do not share or sell user data to third parties.  

## 5. Bot Availability  
- We strive to keep **Volcano Music** online, but we do not guarantee 24/7 availability.  
- Features may change, be added, or removed at any time without prior notice.

## 6. Limitation of Liability  
- **Volcano Music** is provided "as is" without any warranties.  
- We are not liable for any damages resulting from the use or inability to use this bot.

## 7. Termination of Service  
- We reserve the right to ban users or terminate the bot's services at any time without prior notice.  
- Misuse of the bot may result in termination or bans.

## 8. Contact Information  
For questions or concerns about these Terms of Service, please contact us via email at **volcano07@gmail.com**.
"""

# Writing the content to a Markdown file
file_path = "/mnt/data/Volcano_Music_Terms_of_Service.md"
with open(file_path, "w") as file:
    file.write(tos_content)

file_path
