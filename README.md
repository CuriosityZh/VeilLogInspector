# VeilLogInspector

VeilLogInspector is a lightweight real-time log inspector that tags log entries based on rule definitions for easier filtering, alerting, and downstream processing.

## Features
- Works with plain text and JSON logs.
- Applies custom tags using regex or keyword rules.
- Supports rule reloading without restart.
- Can be piped into log aggregators.

## Usage
```bash
git clone https://github.com/your-org/VeilLogInspector.git
cd VeilLogInspector
python src/stream_watcher.py logs/app.log rules.yaml
