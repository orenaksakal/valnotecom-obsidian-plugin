# Valnote Calculator for Obsidian

A natural language calculator plugin for Obsidian that supports:



https://github.com/user-attachments/assets/647025fe-8226-4511-ba72-4d780da94787

- ✨ Basic and advanced math
- 💱 Currency conversions (100+ currencies)
- 📏 Unit conversions (length, weight, volume, etc.)
- 📅 Date calculations
- ⏰ Time and timezone support
- 📊 Variables and aggregations

## Usage

Create a code block with the `valnote` or `calc` language:

````markdown
```valnote
# Valnote Calculator
# Type anywhere to calculate!

# Basic Math
2 + 2
10 * 5 + 3
(100 - 20) / 4
2^8

# Variables
price = 29.99
quantity = 3
total = price * quantity

# Percentages
50% of 200
15% off $100
20% on 80
25 as a % of 100

# Unit Conversions
5 ft in cm
10 km to miles
100 MB in GB
90 deg in rad
72 fahrenheit in celsius

# Currency
$100 to EUR
500 JPY to USD
10k CAD to GBP

# Time & Dates
today
now in Tokyo
time in London
today + 2 weeks
3 days ago

# Math Functions
sqrt 144
sin 90 deg
log 1000
abs -42
round 3.7

# Aggregations
Rent = $1200
Utilities = $150
Internet = $60
sum
average

# Number Formatting
1.5M
10k
$1,000,000

# Comments (like this!)
42 // the answer

```
````

Results appear inline next to each calculation!

## Installation

### From Obsidian Community Plugins

1. Open Settings → Community Plugins
2. Search for "Valnote Calculator"
3. Click Install, then Enable

### Manual Installation

1. Download `main.js`, `manifest.json`, and `styles.css` from the latest release
2. Create folder: `<vault>/.obsidian/plugins/valnote-calculator/`
3. Copy the downloaded files into this folder
4. Reload Obsidian and enable the plugin

## Building from Source

```bash
# From the monorepo root
pnpm install
pnpm --filter @valnote/obsidian-plugin build
```

## Features

### Math Operations
```
2 + 2
10 * 5 + 3
(100 - 20) / 4
2^8
sqrt 144
```

### Variables
```
price = 29.99
quantity = 3
total = price * quantity
```

### Percentages
```
50% of 200
15% off $100
25 as a % of 100
```

### Unit Conversions
```
5 ft in cm
10 km to miles
100 MB in GB
72 fahrenheit in celsius
```

### Currency
```
$100 to EUR
500 JPY to USD
10k CAD to GBP
```

### Dates & Time
```
today
today + 2 weeks
3 days ago
time in Tokyo
```

### Aggregations
```
Rent = $1200
Utilities = $150
Internet = $60
sum
average
```

## License

MIT
