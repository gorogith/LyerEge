# LayerEdge

Automate your LayerEdge light node with this tool.


## Installation

1. Clone the repository:

```bash
git clone https://github.com/gorogith/LyerEge.git
```

2. Navigate to the project directory:

```bash
cd LayerEdge-BOT
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Edit configuration:
   - Edit `data.txt` file in the root directory
   - Add your wallet addresses one per line


## Usage

1. Start the bot:

```bash
python main.py
```

## Features Explained

### Auto Ping

- Automatically pings the LayerEdge network every configured interval
- Keeps your light node active and earning points
- Configurable ping interval (default: 30 seconds)
- Automatic retry mechanism with configurable attempts

### Points Claiming

- Automatically attempts to claim daily points
- Tracks claim status and results
- Shows error messages if claim fails
- Retry mechanism for failed claims

### Dashboard Interface

- Clean and intuitive terminal interface
- Real-time status updates
- Color-coded status indicators
- Pagination for managing multiple wallets
- Error display and tracking

