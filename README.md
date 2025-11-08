# digitial_footprint_analyzer
A simple Python project to analyze the digital footprint of a domain in a clear and visual way.
Digital Footprint Analyzer

Ever wondered what kind of digital footprint a website leaves behind? This little Python tool gives you a quick and visual look at a domain’s public info. It’s simple, easy to use, and even has a dark mode for late-night investigations.

With this app, you can peek at things like:

The domain’s IP address

HTTP headers (like what server it’s running)

WHOIS info (registrar, creation and expiration dates, emails)

Meta tags from the site’s HTML

Basic technologies detected from headers and scripts

Features

Clean, simple Tkinter GUI

Analyze domains with one click

Clear results whenever you want

Toggle between light and dark modes

Works smoothly with Python 3.10+ on Windows

Installation

First, clone the repo:

git clone https://github.com/your-username/digital-footprint-analyzer.git
cd digital-footprint-analyzer


Then, install the necessary Python packages:

pip install requests beautifulsoup4 python-whois

How to Use

Open the script:

python footprint_analyzer.py

Type the domain you want to analyze into the text box.

Hit Analyze and watch the results fill the window.

Click Clear to start fresh anytime.

Switch to Dark Mode if your eyes need a break.

License

MIT License – feel free to use it, fork it, or improve it however you like.
