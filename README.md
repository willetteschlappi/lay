# StreamBoltScanner

StreamBoltScanner is a high-throughput log processor that applies matching rules to live log streams with millisecond latency, ideal for alerting and security pipelines.

## Features
- Regex-based matching engine for plain text or JSON logs.
- In-memory streaming scanner with debounce control.
- Highlights rule hits in terminal and saves to disk.
- Reloadable rule sets on the fly.

## Usage
```bash
git clone https://github.com/your-org/StreamBoltScanner.git
cd StreamBoltScanner
python streambolt/scanner.py logs/live.log
