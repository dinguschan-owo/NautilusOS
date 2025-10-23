# nautilusos

a fully functional web-based operating system that runs entirely in your browser. no installation required, no backend needed - just pure html, css, and javascript creating a complete desktop environment with file management, applications, and customization options.

## overview

nautilusos is a comprehensive web-based os that provides a complete desktop computing experience. it features a bootloader, login system, draggable windows, a virtual file system, and over a dozen built-in applications. everything is stored locally using browser storage, making it perfect for use as a distraction-free environment, a learning tool, or just for fun.

the os includes both graphical and command-line interfaces, customizable themes, profile management, and even tab cloaking for privacy. all your data persists between sessions, and you can export/import your entire profile to backup or share your setup.

built entirely from scratch with no frameworks or dependencies (except font awesome for icons), nautilusos demonstrates what's possible with modern web technologies.

## screenshots

coming soon!

## features

### 🚀 boot system
- **dual boot modes** - choose between graphical desktop or command-line interface on startup
- **animated boot sequence** - realistic startup with loading bar and system messages
- **boot preference memory** - remembers your choice and boots directly next time
- **reset option** - easily return to boot menu through settings

### 🔐 authentication & setup
- **first-time setup wizard** - guided account creation with username and password
- **beautiful login screen** - live clock, system information, and greeting messages
- **password visibility toggle** - show/hide password with eye icon
- **forgot password recovery** - reset your account while preserving all data
- **auto-fill username** - remembers your username for faster login

### 🖥️ desktop environment
- **modern interface** - glassmorphism design with blur effects and smooth animations
- **draggable icons** - click and drag desktop icons to rearrange them
- **grid snapping** - icons automatically align to an invisible grid
- **collision detection** - prevents icons from overlapping
- **animated wallpaper** - subtle floating elements in background
- **context menus** - right-click anywhere for quick actions
- **taskbar** - centered dock-style taskbar with app indicators
- **start menu** - comprehensive app launcher with user info and sign out
- **system tray** - clock, notifications, and quick actions
- **desktop icon visibility toggle** - show/hide all icons from settings

### 🪟 window management
- **multiple windows** - open and manage multiple applications simultaneously
- **drag to move** - click and drag title bar to reposition windows
- **resize from any edge** - drag from top, bottom, left, right, or corner
- **minimize** - hide windows to taskbar, restore with click
- **maximize** - full-screen windows with one click, restore to previous size
- **close** - smooth fade-out animation when closing
- **focus management** - click any window to bring it to front
- **taskbar indicators** - active window highlighted, minimized shown with dot
- **dynamic taskbar icons** - opened apps automatically appear in taskbar
- **window animations** - smooth scale and fade effects
- **z-index stacking** - proper window layering

### 📁 file system
- **virtual file system** - complete hierarchical file structure
- **tree navigation** - collapsible folder tree in sidebar
- **breadcrumb navigation** - click any path segment to jump there
- **file operations** - create folders, save files, delete items
- **drag and drop** - drag files into folders to move them
- **file selection** - click to select, shows action buttons
- **multiple file types** - folders and text files supported
- **persistent storage** - all files saved between sessions
- **visual feedback** - hover effects and drag-over highlighting

### 💻 applications

#### files
- visual file explorer with dual-pane interface
- create unlimited nested folders
- drag and drop file organization
- quick action buttons (open, delete)
- search and navigation tools

#### terminal
- command-line interface with unix-like commands
- commands: help, ls, apps, themes, clear, date, whoami, echo, reset-boot, gui
- command history
- colored output for better readability
- auto-scrolling terminal output
- switch between gui and cli modes

#### nautilus browser
- fully functional web browser within the os
- multiple tab support with tab management
- forward/back navigation with history
- refresh and url bar
- loading indicators
- new tab page with search
- handles iframes for most websites
- error handling for blocked content

#### text editor
- create and edit text files
- save to virtual file system
- save as new file
- download to real device
- syntax-free plain text editing
- file name editing in toolbar

#### settings
- clock format toggle (12/24 hour)
- show/hide seconds option
- desktop icon visibility control
- theme management (install/uninstall)
- boot preference reset
- account information display
- profile export/import
- reset all data option
- what's new startup toggle

#### music player
- load audio files from device
- play/pause controls
- skip forward/backward 10 seconds
- restart track
- loop toggle
- volume slider with percentage
- progress bar with seeking
- time display (current/total)
- track information display

#### photos
- screenshot storage and viewing
- grid layout thumbnail view
- click to view full screen
- delete photos
- automatic screenshot naming with timestamp
- photo count display

#### calculator
- basic operations (+, -, ×, ÷)
- decimal support
- percentage calculations
- backspace to correct mistakes
- clear button
- visual calculation history
- equals for final result
- keyboard-friendly design

#### app store
- browse and install themes
- browse and install apps
- sections for themes and apps
- visual app cards with descriptions
- install/uninstall with one click
- shows installation status
- auto-updates settings and desktop

#### help
- comprehensive documentation
- searchable help topics
- command reference
- keyboard shortcuts
- tips and tricks
- feature explanations
- troubleshooting guide

#### what's new
- interactive carousel showcasing features
- 13 slides covering all major features
- visual illustrations for each feature
- navigation dots and arrow buttons
- links to help and github
- can be disabled in settings

#### cloaking
- disguise browser tab title
- custom favicon from any website url
- auto-rotate through multiple sites
- configurable rotation speed (1-300 seconds)
- manage rotation list (add/remove sites)
- enable/disable auto-rotate toggle
- uses google and duckduckgo favicon services
- perfect for privacy and distraction-free browsing

#### startup apps
- control which apps launch on login
- toggle individual apps on/off
- visual list with app icons
- shows enabled/disabled status
- integrates with what's new setting
- instant apply (no restart needed)

#### task manager
- view all running applications
- see open window count
- close individual apps
- close all apps at once
- refresh all apps
- system status display
- quick action buttons
- auto-refreshes when windows open/close

### 🎨 customization

#### themes
- dark theme (default) - sleek teal and dark blue
- light theme (installable) - bright and clean
- theme installation from app store
- theme persistence between sessions
- future theme support planned

#### profiles
- **export profile** - download complete backup as .nautilusprofile file
- **import profile** - restore from backup file
- **includes everything** - username, password, settings, files, apps, themes
- **cross-device sync** - transfer setup to another browser/device
- **backup safety** - protect against data loss
- **share setups** - give your config to friends

### 🔔 notifications & quick actions
- **notification center** - view all system messages in one place
- **notification history** - keeps last 50 notifications with timestamps
- **toast notifications** - temporary pop-ups for important events
- **clear all** - dismiss all notifications at once
- **time ago display** - shows when each notification occurred
- **quick actions panel** - bolt icon in taskbar
- **screenshot capture** - capture your desktop with one click
- **close all windows** - quickly close everything
- **sign out** - return to login screen
- **shut down** - return to home page

### ⌨️ keyboard & interaction
- **enter to login** - press enter on password field
- **boot menu navigation** - arrow keys to select, enter to boot
- **terminal input** - full command line with enter to execute
- **calculator keyboard** - number keys work in calculator
- **text editing** - standard keyboard shortcuts in editor
- **window dragging** - smooth mouse-based dragging
- **click to focus** - standard window focusing behavior

### 💾 data persistence
- **local storage** - all data saved to browser
- **survives refresh** - everything persists on page reload
- **settings memory** - all preferences saved automatically
- **file system storage** - virtual files stored locally
- **theme preferences** - installed themes remembered
- **app installations** - installed apps persist
- **startup app config** - startup preferences saved
- **cloaking settings** - tab disguise config saved
- **window positions** - windows open where you left them (upcoming)

### 🎯 context menus
- **desktop context menu** - right-click desktop for actions
  - refresh desktop
  - new text file
  - new folder
  - help
- **icon context menu** - right-click icons
  - open application
  - properties (shows app info)
- **window context menu** - right-click windows
  - minimize
  - maximize/restore
  - close
  - help
- **smart positioning** - menus adjust to stay on screen

### 📊 properties system
- **app properties** - right-click any desktop icon, select properties
- **detailed information** - app name, icon, status, type, location
- **installation status** - shows if preinstalled or from app store
- **visual badges** - color-coded badges for easy identification
- **hover positioning** - appears near cursor
- **screen boundary aware** - automatically adjusts position
- **click outside to close** - intuitive dismissal

### 🛠️ system tools
- **refresh desktop** - reopen all windows to reset state
- **refresh all apps** - close and reopen all applications
- **reset boot preference** - return to boot menu on reload
- **reset all data** - complete factory reset with confirmation
- **sign out to login** - return to login without losing session
- **shut down** - redirect to home page
- **browser detection** - shows your browser in login screen
- **uptime counter** - displays time since login
- **time/date widgets** - live updating clocks

### 🎭 special features
- **easter eggs** - special messages for certain usernames
- **developer credit** - attribution on boot screen and wallpaper
- **smooth animations** - polished transitions throughout
- **loading states** - visual feedback for all actions
- **error handling** - graceful failures with helpful messages
- **confirmation dialogs** - custom modals for important actions
- **input validation** - prevents invalid data entry
- **auto-focus** - inputs automatically focused when appropriate

### 🏗️ technical features
- **no dependencies** - pure vanilla javascript (except font awesome)
- **no frameworks** - no react, vue, angular, etc.
- **no build process** - runs directly in browser
- **no backend required** - completely client-side
- **responsive design** - adapts to window size
- **modern css** - flexbox, grid, custom properties
- **es6+ javascript** - async/await, promises, classes
- **local storage api** - for data persistence
- **blob urls** - for screenshot storage
- **mediadevices api** - for screenshot capture
- **file api** - for profile import/export
- **favicon manipulation** - dynamic tab icon changes
- **document title control** - dynamic tab title changes

### 📱 browser compatibility
- works in all modern browsers
- chrome/edge - full support
- firefox - full support
- safari - full support
- brave - full support
- opera - full support
- mobile browsers - limited (desktop experience optimized)

### 🎓 educational value
- learn about operating systems
- understand file system concepts
- practice command-line interfaces
- explore window management
- study web development techniques
- see complex ui patterns in action
- review vanilla javascript architecture

### 🔒 privacy & security
- **no data collection** - everything stays local
- **no analytics** - no tracking of any kind
- **no cookies** - uses only local storage
- **no external requests** - except favicon fetching for cloaking
- **open source** - audit the code yourself
- **local only** - never leaves your browser
- **tab cloaking** - hide what you're doing

### 🚧 limitations & known issues
- screenshots use blob urls (don't transfer between devices)
- browser storage limits (~5-10mb depending on browser)
- some websites block iframe embedding in browser app
- mobile experience not optimized (desktop-focused)
- no multi-user support
- no file upload to virtual file system (yet)
- no copy/paste between apps (yet)

## installation

1. download or clone this repository
2. open `index.html` in any modern web browser
3. that's it! no build step, no server, no npm install
```bash
# clone the repo
git clone https://github.com/yourusername/nautilusos.git

# open in browser
cd nautilusos
open index.html  # or just double-click the file
```

## usage

### first time setup
1. choose boot mode (graphical or command-line)
2. create your username (minimum 3 characters)
3. create your password (minimum 6 characters)
4. optionally install extra apps and themes
5. click finish to complete setup

### daily use
1. the boot menu appears (or auto-boots if preference saved)
2. enter your password to login
3. explore the desktop, open apps, manage files
4. sign out or shut down when finished

### exporting your profile
1. open settings app
2. scroll to profile management section
3. click "export profile"
4. save the .nautilusprofile file somewhere safe

### importing a profile
1. from the setup screen, click "import profile"
2. select your .nautilusprofile file
3. confirm the import
4. you'll be redirected to login with imported credentials

## technical details

### file structure
```
nautilusos/
├── index.html          # entire os in one file
└── README.md           # this file
```

### architecture
- single-page application
- event-driven architecture
- object-based window management
- virtual file system in memory
- local storage for persistence
- no external dependencies (except font awesome cdn)

### storage keys
all data stored in `localStorage` with `nautilusOS_` prefix:
- `nautilusOS_username` - user's username
- `nautilusOS_password` - user's password (stored in plain text locally)
- `nautilusOS_setupComplete` - whether first-time setup is done
- `nautilusOS_settings` - json object of all settings
- `nautilusOS_installedThemes` - array of installed theme names
- `nautilusOS_installedApps` - array of installed app names
- `nautilusOS_startupApps` - array of apps that launch on login
- `nautilusOS_showWhatsNew` - whether to show what's new on login
- `nautilusOS_bootChoice` - saved boot mode preference
- `nautilusOS_bootTime` - timestamp of when os was first loaded
- `nautilusOS_cloaking` - json object of cloaking configuration

### customization

you can easily customize nautilusos by editing the css variables:
```css
:root {
    --accent: #7dd3c0;          /* primary accent color */
    --accent-hover: #6bc4b0;    /* hover state */
    --bg-primary: #0a0e1a;      /* main background */
    --bg-secondary: #151923;    /* secondary background */
    --text-primary: #e8eaed;    /* main text */
    --text-secondary: #9aa0a6;  /* secondary text */
    --border: #7dd3c0;          /* border color */
}
```

## contributing

contributions are welcome! this is a learning project and there's always room for improvement.

ideas for contributions:
- add more applications
- create new themes
- improve mobile responsiveness
- add file upload capability
- implement copy/paste between apps
- add more terminal commands
- improve accessibility
- optimize performance
- fix bugs

## roadmap

potential future features:
- [ ] file upload from device to virtual fs
- [ ] copy/paste between applications
- [ ] more terminal commands (cd, mkdir, rm, cat, etc)
- [ ] text editor syntax highlighting
- [ ] music playlist support
- [ ] photo editing tools
- [ ] more themes (dark blue, purple, etc)
- [ ] widget system for desktop
- [ ] system sounds
- [ ] window snapping (drag to edge)
- [ ] multiple desktops/workspaces
- [ ] search functionality
- [ ] keyboard shortcuts reference
- [ ] performance monitoring
- [ ] browser extensions support
- [ ] mobile-optimized version

## credits

- **created by** dinguschan
- **icons** font awesome (cdnjs)
- **inspiration** operating systems everywhere

## license

this project is open source and available for anyone to use, modify, and learn from. please keep the attribution to dinguschan in the code.

## support

if you encounter any issues or have questions:
- open an issue on github
- check the help app within nautilusos
- review the code (it's all in one file!)

## fun facts

- entire os is ~4800 lines of code in a single html file
- no build process or compilation needed
- works completely offline after initial load
- uses only ~2-3mb of browser storage
- boot sequence is just for show (loads instantly)
- wallpaper gradients are procedurally generated
- all animations are css-based for performance
- context menus use absolutely positioned divs
- windows use the z-index system for stacking

---

**built with ❤️ by dinguschan**
