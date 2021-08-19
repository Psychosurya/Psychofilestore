from pyrogram import Client

api_id = 7437682
api_hash = "0123456789abcdef0123456789abcdef"

with Client("my_account", api_id, api_hash) as app:
    app.send_message("me", "Greetings from **Pyrogram**!")
