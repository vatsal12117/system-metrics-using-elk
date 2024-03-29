# system-metrics-using-elk

Collect System Metrics

Collect and transfer system metrics ( CPU usage, Memory usage and Disk usage ) in real-time.
For the purpose, we are planning to use Topbeat.

Topbeat is a lightweight shipper that you can install on your servers to periodically read system-wide and per-process CPU and memory statistics and then index the statistics in Elasticsearch.

Topbeat helps you monitor your servers by collecting metrics like:

System-wide statistics
• System load: in the last minute, in the last 5 minutes, and in the last 15 minutes
• System wide CPU usage: user (and percentage), system, idle, IOWait, and so on at both per CPU and overall level
• System wide memory usage: total, used (and percentage), free, and so on
• System wide swap usage: total, used (and percentage), free, and so on

Per-process statistics
• Process name
• Process parent pid
• Process state
• Process pid
• Process CPU usage: user (and percentage), system, total, and start time
• Process Memory usage: virtual memory, resident memory (and percentage), and shared memory

File system statistics
• List of available disks
• For each disk, the name, type, and where it is mounted
• For each disk, the total, used (and percentage), free, and available space
