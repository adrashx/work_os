WORK_OS // HYPERVISOR

A high-fidelity, cyberpunk financial operating system for personal wealth tracking.

// SYSTEM_OVERVIEW

WorkOS is a local-first, single-file web application designed to track net worth, cash flow, and asset allocation with a terminal-inspired aesthetic. It features real-time market data synchronization via Finnhub.

[ CORE MODULES ]

COMMAND (Dashboard): Real-time HUD showing Net Worth, Liquidity, and Asset Allocation.

LEDGER: Transaction tracking (Income/Expense) with category support.

PORTFOLIO: * Market: Live stock/crypto tracking.

Commodities: Gold/Silver tracking.

Real Estate: Property tracking with auto-appreciation logic.

Business: Private equity valuation.

BALANCE: Balance sheet visualization and solvency analysis.

TOOLS: Integrated Notepad and Currency Converter.

// DEPLOYMENT

To use this as a cloud-synced app (via GitHub Pages) or install it on your device:

Repo Setup:

Upload WorkOS_HighFidelity.html (Rename it to index.html).

Upload manifest.json and service-worker.js.

(Optional) Add a black square image named icon-512.png for the app icon.

GitHub Pages:

Go to Repository Settings > Pages.

Set Branch to main / root.

Save.

Installation (PWA):

Visit your GitHub Pages URL on Mobile (Safari/Chrome).

Tap "Share" > "Add to Home Screen".

Result: The app launches fullscreen without browser UI.

// CONTROLS

KEY

ACTION

1-4

Navigate Sectors

SPACE

Open Command Line

N

Open Notepad

C

Open Converter

ARROWS

Slide Navigation

// CLI_COMMANDS

SYNC - Refresh market prices.

BUY [TIK] [QTY] [PRICE] - Add stock position.

IN [AMT] [DESC] - Log income.

OUT [AMT] [DESC] - Log expense.

PROP [NAME] [VAL] [RATE] [YR] - Add property.

SYSTEM_ROOT_ACCESS_GRANTED
