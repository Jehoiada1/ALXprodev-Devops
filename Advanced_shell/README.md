# Advanced Shell Scripting: Pokémon API Automation

This project demonstrates advanced shell scripting techniques for automating data extraction, transformation, and reporting using the Pokémon API.

## Structure
- `apiAutomation-0x00`: Fetches Pikachu data and logs errors.
- `data_extraction_automation-0x01`: Parses Pikachu data for name, type, height, and weight.
- `batchProcessing-0x02`: Batch fetches data for multiple Pokémon with error handling and rate limiting.
- `summaryData-0x03`: Summarizes Pokémon data into a CSV and calculates averages.
- `batchProcessing-0x04`: Fetches Pokémon data in parallel.
- `pokemon_data/`: Stores individual Pokémon JSON files.

## Usage
Make scripts executable:
```bash
chmod +x apiAutomation-0x00 data_extraction_automation-0x01 batchProcessing-0x02 summaryData-0x03 batchProcessing-0x04
```
Run each script as needed:
```bash
./apiAutomation-0x00
./data_extraction_automation-0x01
./batchProcessing-0x02
./summaryData-0x03
./batchProcessing-0x04
```

## Requirements
- bash
- curl
- jq
- awk
- sed

## Author
ALXprodev
