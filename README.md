# Snowflake Summit 2026 - Smart Calendar

Interactive calendar for Snowflake Summit 2026 with smart conflict detection and schedule building.

🌐 **Public Site** - Share with anyone!

## Features

- 📅 **Full Scroll Calendar View** - All 4 days visible at once with scrolling
- ⭐ **My Schedule View** - See your selected sessions organized by day with times
- 🔍 **Search & Filter** - Find sessions by keyword, track, or selection status
- ⚠️ **Smart Conflict Detection** - Conflicting time slots are automatically grayed out
- 📤 **Export/Import** - Save and share your schedule as CSV

## Usage

🌐 **Visit the live site:** https://vand-ch.github.io/snowflake-summit-2026/

**View Van's Schedule:** https://vand-ch.github.io/snowflake-summit-2026/?load=my_summit_schedule.csv

Or download `index.html` and open it locally in your browser - it's 100% self-contained!

## How to Use

1. **Browse all sessions** - Calendar View shows all 4 days in one scrollable page
2. **Star sessions** - Click ⭐ on sessions to add them to your schedule
3. **View your schedule** - Switch to "My Schedule" tab to see selections by day with times
4. **Export** - Download your schedule as CSV
5. **Import** - Load someone else's CSV schedule

## Sharing Your Schedule

### Option 1: Share a Direct Link
Your CSV is in the repo, so share this URL:
```
https://vand-ch.github.io/snowflake-summit-2026/?load=my_summit_schedule.csv
```

Anyone can view it - no login required!

### Option 2: Share the CSV File
Export your schedule and send the CSV file. Recipients can import it.

### Option 3: Share the HTML File
Send `index.html` - completely self-contained, works offline!

## Updating Your Schedule

After exporting from the calendar:

```bash
# Use the quick update script:
~/update_summit_schedule.sh

# Or manually:
cp ~/Downloads/my_summit_schedule.csv ~/Documents/GitHub/snowflake-summit-2026/
cd ~/Documents/GitHub/snowflake-summit-2026
git add my_summit_schedule.csv
git commit -m "Update schedule"
git push
```

Your link updates in ~2 minutes!

## Hosting

Static HTML hosted on GitHub Pages. Free, fast, and publicly accessible.
