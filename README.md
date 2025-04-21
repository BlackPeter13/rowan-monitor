# Rowan Energy RWN Token Monitor

A simple dashboard to monitor the total supply of Rowan Energy (RWN) tokens live.

**Features:**
- Live total supply checking every 15 seconds.
- Detection of suspicious minting activity.
- History log of all supply checks.
- Visual alerts if unusual supply increases are detected.

**Why?**
Rowan Energy operates its own blockchain but still allows minting via a smart contract function.  
This dashboard helps track the RWN token supply for transparency and community monitoring.

**Live Dashboard:**
> [Visit the Monitor Dashboard](https://blackpeter13.github.io/rowan-monitor/)

## Security Notes

Because the Rowan RPC node (`http://3.19.248.157:8504`) does not support HTTPS, browsers might block requests due to mixed content policies.  
You can either:
- Allow insecure content manually in your browser settings.
- Set up a proxy server to handle HTTPS requests securely.

---

## License

This project is open for public use. Feel free to copy, modify, and improve it.
