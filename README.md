# Reconify
Automate your recon game.

🛠️ reconify – Automated Nmap Recon Tool
Created by Haddo Grepps. For the pentesters, the homelabbers, the rebels building their own systems.

⚡ What is this?
reconify is a no-nonsense CLI tool to automate your recon game using nmap. Whether you're testing your own setup or mapping out a client environment, this script handles the repetitive stuff so you can focus on the fun part—finding stuff that shouldn't be exposed.

🎯 Features
Host discovery (ping sweep)

Full TCP port scan (-p-, T4 timing)

Service version + OS fingerprinting

Vulnerability scan using NSE

HTTP/HTTPS enumeration if detected

Clean Markdown report generator

Timestamped output folders

🧑‍💻 Usage

Run the command below. No need to use an elevated account.

> ./reconify -t <target>
