# Network Mask Calculator

An interactive, single-file HTML tool for visualizing IP addresses and CIDR notation in binary.

## Features

- **Binary visualization** — See each IP address and netmask broken down into 32 individual bits, grouped by octet
- **Interactive CIDR slider** — Drag a slider from /0 to /32 to dynamically adjust the network mask length
- **Color-coded bits** — Visual distinction between:<br/>
  🟢 Network address (green) — computed network identifier<br/>
  🟠 Host address (orange) — the variable portion for individual hosts<br/>
  🔵 Network bits (cyan) — the fixed portion of the address<br/>
  🟣 Host bits (purple) — host portion of the address<br/>

## Usage

Visit https://netmask.page in any web browser. It's that simple!

1. Enter an IPv4 address in the input field (e.g., `192.168.1.1`)
2. Drag the slider to set the CIDR mask length (0–32)
3. Observe how bits are partitioned between network and host portions

## Technical Details

- **Single HTML file** — All CSS and JavaScript are embedded inline
- **No dependencies** — Pure vanilla JS, no frameworks or libraries

## File Structure

```
index.html   # Single self-contained HTML file
```

## Source Code

[github.com/circuitrewind/netmask.page](https://github.com/circuitrewind/netmask.page/)

## License

Public Domain. See [LICENSE](./LICENSE) for details.
