# InteractiveHelpSystem
An advanced, user-friendly help system for Discord bots that makes discovering commands effortless.



> 💡 **Built for the Zygnal Ecosystem — to download and use this extension, you must be part of the Zygnal Ecosystem.**  
> This extension (cog) is part of the **Zygnal Ecosystem** and is only available through its supported platforms.  
> You can use it with:  
> - The **[Discord Bot Framework](https://github.com/TheHolyOneZ/discord-bot-framework)** — ideal for developers who want full control and flexibility *(includes an integrated extension marketplace)*, or  
> - The **[ZygnalBot](https://zygnalbot.de)** — a prebuilt, plug-and-play Discord bot *(also includes an integrated extension marketplace)*.  
>
> Browse and install extensions at [zygnalbot.com/extension](https://zygnalbot.com/extension).  
> For help or community discussions, join us on Discord: [discord.gg/sgZnXca5ts](https://discord.gg/sgZnXca5ts)








# 📚 Interactive Help System

An advanced, user-friendly help system for Discord bots that makes discovering commands effortless.

**Created by TheHolyOneZ**

---

## 🚀 Quick Start Guide

### Opening the Help System

Simply type one of these commands in any channel:
```
!help
!commands
!cmds
!h
```

**What happens:**
1. Your command message is **instantly deleted** (keeps chat clean)
2. A tutorial screen appears explaining the system
3. Click the **"Continue"** button to start exploring
4. Browse categories, search commands, and navigate with buttons

### Quick Search

Want to find specific commands fast? Add a search term:
```
!help moderation
!help ban
!help music
!help fun
```

This skips the tutorial and shows search results immediately.

---

## ⏱️ Important: 10-Minute Auto-Close

**Every help panel automatically closes after 10 minutes.**

Don't worry though - you'll get a warning:
- At **8 minutes**: Warning message appears
- Says: "closing in 2 minutes!"
- Includes a link to jump back to your panel
- At **10 minutes**: Panel and warning both delete

**Tip:** If you need more time, just run `!help` again to open a fresh panel!

---

## 🌟 Features

### ✨ Interactive Tutorial
- Welcome screen that introduces the help system
- Explains navigation and features
- Shows auto-close time with Discord timestamp
- Continue button to start exploring

### 🧹 Auto-Cleanup
- Command messages are instantly deleted for clean chat
- Help windows automatically close after 10 minutes
- 2-minute warning before closure
- Background cleanup runs automatically
- No manual maintenance needed

### 🛡️ Smart Protection
- Maximum 5 help windows per user
- Rate limiting prevents spam
- Only the person who opened a help window can use its buttons
- Others attempting to interact get a friendly message

### 📄 Perfect Pagination
- Commands displayed 10 per page
- Categories shown 15 per page
- Search results displayed 10 per page
- Never exceeds Discord's limits
- Smooth navigation with arrow buttons

### 🔍 Powerful Search
- Search by command name
- Search by command alias
- Search by keyword in description
- Direct search: `!help <query>`
- Interactive search button with modal popup
- Results show command category

### 🎨 Beautiful Design
- Professional Discord embeds
- Color-coded sections
- Emoji navigation buttons
- Clear page indicators
- User-friendly interface

### 🧭 Easy Navigation
- **Home Button** - Return to category overview
- **Previous/Next Buttons** - Navigate pages
- **Dropdown Menu** - Jump directly to categories
- **Search Button** - Find specific commands
- **Close Button** - Exit anytime

### ⏰ 2-Minute Warning System
- After 8 minutes, you get a warning message
- Shows "@you this panel is closing in 2 minutes"
- Includes link to jump back to your help panel
- Warning message auto-deletes when panel closes
- Keeps you informed without being intrusive

---

## 🎮 Commands

### Main Command
```
!help
```
Opens the interactive help system with tutorial screen.

**Aliases:**
- `!commands`
- `!cmds`
- `!h`

### Quick Search
```
!help <search query>
```
Instantly search for commands matching your query.

**Examples:**
- `!help moderation` - Search for moderation commands
- `!help ban` - Search for commands with "ban"
- `!help fun` - Search for fun commands

---

## 📖 How to Use - Step by Step

### 🎬 First Time Using

**Step 1: Open Help**
```
Type: !help
```
- Your command disappears immediately
- Tutorial screen appears with welcome message

**Step 2: Read Tutorial**
- Learn about navigation buttons
- See what features are available
- Note the auto-close time

**Step 3: Click Continue**
- Click the green **"✨ Continue to Commands"** button
- Overview of all categories appears

**Step 4: Explore**
- Use dropdown to select a category
- Browse through commands with arrow buttons
- Click search to find specific commands
- Click home to return to overview

### 🗂️ Browsing by Category

**From Overview Screen:**
1. Look at the dropdown menu (📂 Select a category...)
2. Click it to see all available categories
3. Select the category you want to explore
4. Commands appear, 10 per page
5. Use **◀️ Previous** and **Next ▶️** buttons to navigate
6. Click **🏠 Home** to return to overview

**Example:**
```
You want to see moderation commands
↓
Click dropdown → Select "ModerationCommands"
↓
See all moderation commands with descriptions
↓
Click through pages to see more
```

### 🔍 Using Search

**Method 1: Direct Search (Fastest)**
```
Type: !help moderation
```
- Skips tutorial
- Shows results immediately
- Searches command names, aliases, and descriptions

**Method 2: Interactive Search**
1. Open help with `!help`
2. Click Continue (if on tutorial)
3. Click **🔍 Search** button
4. Popup appears asking for search term
5. Type your query (e.g., "ban")
6. Press Submit
7. Results appear with page navigation

**Search Tips:**
- Search by command name: `!help kick`
- Search by category: `!help music`
- Search by keyword: `!help delete`
- Search is case-insensitive

### 🧭 Navigation Guide

**Buttons You'll See:**

**Overview Mode:**
- **◀️** / **▶️** - Navigate overview pages (if you have many categories)
- **📂 Dropdown** - Jump directly to any category
- **🔍 Search** - Open search modal
- **❌ Close** - Exit help system

**Category View Mode:**
- **◀️ Previous** - Go to previous page of commands
- **🏠 Home** - Return to category overview
- **▶️ Next** - Go to next page of commands
- **🔍 Search** - Search for commands
- **❌ Close** - Exit help system

**Search Results Mode:**
- **◀️ Previous** - Previous page of results
- **🏠 Home** - Return to overview
- **▶️ Next** - Next page of results
- **🔍 New Search** - Search again
- **❌ Close** - Exit help system

### ❌ Closing Help

**Manual Close:**
- Click the **❌ Close** button anytime
- Help panel disappears immediately

**Auto-Close:**
- Panel auto-closes after 10 minutes
- Warning sent at 8 minutes
- Everything cleaned up automatically

---

## ⚙️ System Limits

### Per User
- **Maximum Windows:** 5 help windows at once
- **Window Lifetime:** 10 minutes auto-close
- **Command Deletion:** Instant

### Pagination
- **Commands per Page:** 10
- **Categories per Page:** 15
- **Search Results per Page:** 10

### Protection
- **User-Specific:** Only you can interact with your help window
- **Rate Limited:** Prevents spam and abuse
- **Auto-Cleanup:** Old windows removed automatically

---

## 🎯 Example Workflows

### Exploring by Category
1. Type `!help`
2. Click Continue
3. Use dropdown to select "Moderation"
4. Browse through moderation commands
5. Use arrows to see more commands
6. Click Home when done

### Quick Command Search
1. Type `!help ban`
2. See all commands related to "ban"
3. View command details and categories
4. Click Home or Close when done

### Interactive Search
1. Type `!help`
2. Click Continue
3. Click Search button
4. Enter "music" in the popup
5. Browse music-related commands
6. Try a new search or return home

---

## 💡 Pro Tips

1. **Quick Access** - Use `!help <word>` to search immediately
2. **Clean Chat** - Commands auto-delete, keep discussions clean
3. **Multiple Searches** - Open up to 5 help windows at once
4. **Warning Alert** - Get notified 2 minutes before auto-close
5. **Private Control** - Others can't interfere with your help window
6. **Jump Link** - Warning message has link to return to panel
7. **Modal Search** - Click Search button for advanced searching
8. **Page Numbers** - Footer shows current page and total pages

---

## 🔒 Security Features

### User Validation
Every button interaction checks if you're the window owner. Other users get a friendly error message if they try to interact with your help window.

### Rate Limiting
Maximum 5 help windows per user prevents spam. Older windows auto-close to make room for new ones.

### Auto-Cleanup
Background task removes expired windows every 30 seconds, ensuring no abandoned help windows stay forever.

---

## ⏰ Warning System

### 2-Minute Warning Before Auto-Close

When you open a help panel, it will automatically close after **10 minutes**. To give you a heads up, you'll receive a warning message **2 minutes before** it closes.

**Timeline:**
```
  Time        Event
  ────────────────────────────────────────────
  0:00  →  You open help panel with !help
            ↓
            Panel is active, you browse commands
            ↓
  8:00  →  ⏰ WARNING MESSAGE SENT
            "Hey @You, your help panel is closing in 2 minutes!"
            • Sent in the same channel
            • Mentions you so you get notified
            • Includes a jump link back to your panel
            • You have 2 minutes to finish browsing
            ↓
 10:00  →  🗑️ AUTO-CLOSE
            • Help panel deleted
            • Warning message deleted
            • Everything cleaned up automatically
```

**The Math:**
- Total lifetime: **600 seconds** = **10 minutes**
- Warning at: **480 seconds** = **8 minutes**
- Warning buffer: **120 seconds** = **2 minutes** (10min - 8min = 2min)

So you get a **2-minute warning** before the **10-minute auto-close**!

### What You See

At the 8-minute mark, a warning message appears:

```
┌────────────────────────────────────────────┐
│ ⏰ Help Panel Closing Soon                │
│                                            │
│ Hey @YourName, your help panel is closing │
│ in 2 minutes!                              │
│                                            │
│ 🔗 Jump to Panel                           │
│                                            │
│ This message will auto-delete when the     │
│ panel closes                               │
└────────────────────────────────────────────┘
```

**Key Features:**
- **@ Mention** - You get a Discord notification
- **Jump Link** - Click to instantly return to your panel
- **2-Minute Buffer** - Enough time to finish what you're doing
- **Auto-Delete** - Warning disappears with the panel
- **No Manual Cleanup** - Everything is automatic

### Why This System?

This gives you:
1. **Advance Notice** - Never surprised by auto-close
2. **Time to Save** - 2 minutes to finish browsing or note commands
3. **Easy Return** - Jump link if you're in another channel
4. **Clean Experience** - Both messages auto-delete together

---

## 🎨 Interface Elements

### Tutorial Screen
- Welcome message
- Feature overview
- Navigation guide
- Continue button
- Close button
- Made by TheHolyOneZ footer

### Overview Screen
- All command categories
- Command count per category
- Sample commands
- Category dropdown
- Search button
- Page navigation
- Close button

### Command View
- 10 commands per page
- Full command signature
- Command description
- Aliases if available
- Previous/Next navigation
- Home button
- Search button
- Close button

### Search Results
- Matching commands
- Category information
- Command descriptions
- Page navigation
- Home button
- New Search button
- Close button

---

## 📝 Notes

- Help windows auto-close after 10 minutes
- Warning message sent at 8 minutes (2 min before close)
- Maximum 5 windows per user at once
- Command messages deleted instantly
- Only you can use your help window buttons
- Search works across command names, aliases, and descriptions
- Warning message includes jump link to panel
- Warning auto-deletes with panel
- Zero manual cleanup required

---

## 🎓 Getting Help

If you encounter issues:
1. Check if you've reached the 5 window limit
2. Close old help windows using the ❌ button
3. Wait for windows to auto-close after 10 minutes
4. Try reloading the help cog if commands aren't showing

---

## ❓ Frequently Asked Questions

### "Why did my command message disappear?"
This is intentional! The bot deletes your `!help` command to keep the chat clean. Only the help panel remains.

### "I got a message saying 'Too Many Help Windows' - what does this mean?"
You can have maximum 5 help panels open at once. Close some old ones using the ❌ button, or wait for them to auto-close after 10 minutes.

### "Can other people use my help panel buttons?"
No! Only you can interact with your help panel. If someone else tries to click your buttons, they'll see "This help menu belongs to someone else!"

### "What happens after 10 minutes?"
The help panel automatically closes and deletes itself. You'll get a warning at the 8-minute mark giving you 2 minutes to finish up.

### "I was in another channel when the warning came - how do I get back?"
Click the "Jump to Panel" link in the warning message. It will take you directly back to your help panel.

### "Can I keep it open longer than 10 minutes?"
No, but you can simply run `!help` again to open a fresh panel!

### "Why doesn't the dropdown show all categories?"
If you have more than 25 categories, they're split across multiple overview pages. Use the ◀️ ▶️ buttons to navigate pages, and the dropdown will update to show the categories on your current page.

### "I clicked a button but nothing happened"
Make sure you're clicking buttons on YOUR help panel (one you opened). You can't interact with other people's help panels.

### "No commands are showing up"
Make sure your bot has cogs loaded. Check with your bot owner to verify extensions/cogs are loaded properly.

### "The search isn't finding my command"
Search looks in command names, aliases, and descriptions. Try different keywords. If a command isn't showing up, it might be marked as hidden by the bot owner.

### "Can I customize the colors or timing?"
Bot owners can customize colors, window limits, and timing in the `auto_help.py` file. Users cannot change these settings.

---

## 🔧 For Bot Owners

### Customizing Settings

All settings are in `AutoHelpCommand.py` in the `__init__` method:

**Timing:**
```python
self.max_windows_per_user = 5    # Max help windows per user
self.window_lifetime = 600       # Auto-close after 10 minutes (in seconds)
```

**Colors:**
```python
self.colors = {
    'primary': 0x5865F2,      # Main screens
    'success': 0x57F287,      # Success actions
    'danger': 0xED4245,       # Errors
    'warning': 0xFEE75C,      # Warnings
    'info': 0x00D9FF,         # Search results
    'tutorial': 0xFF6B9D,     # Tutorial screen
    'premium': 0x9B59B6       # Reserved for future use
}
```

**Warning Timing:**
The warning is sent at 480 seconds (8 minutes), which is 2 minutes before the 10-minute auto-close. To change this, edit the `send_warning` method:
```python
await asyncio.sleep(480)  # Change 480 to desired seconds
```

---

**Made By TheHolyOneZ**
*Interactive Help System - Making command discovery effortless*****
