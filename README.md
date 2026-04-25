# Real-Time Network Reachability Monitor
# RT-NRM Will Soon Be Released!
# Created By     : x_4rch4n63l_x
# Created On     : 01/20/2026 - 04:10 AM
#
# Script Name    :
#   Real-Time Network Reachability Monitor (RT-NRM)
#
# Script Purpose :
#   Persistent, real-time monitoring of IPv4 and IPv6 host reachability using
#   multiple network-layer and application-layer probing techniques.
#
# Description    :
#   This script provides a terminal-based, continuously updating network
#   reachability monitor for IP networks specified in CIDR notation. All usable
#   hosts within the target network are repeatedly scanned, and host states
#   (ON/OFF) are dynamically updated as network conditions change.
#
#   Unlike traditional one-shot ping sweep tools, this utility is designed for
#   long-running observation and situational awareness. It supports both
#   privileged and non-privileged probing methods, allowing it to function in
#   restricted user environments as well as elevated (admin/root) contexts.
#
#   The user interface is powered by the Rich library, providing a responsive,
#   auto-scaling, live-updating dashboard that adapts to terminal size and refreshes
#   in near real time. Scanning is performed concurrently using a configurable
#   thread pool to maintain performance on medium-to-large networks.
