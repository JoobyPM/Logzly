# **Logzly: Streamlined Log Analysis CLI**
> Effortlessly transform nginx logs into actionable insights with automated parsing, filtering, and analysis.


Logzly is a powerful and light Node.js-based command-line tool that simplifies access log analysis. It automates the process of scanning, parsing, and summarizing `nginx` log files, offering insightful metrics with minimal effort. Whether you're an admin seeking to analyze API usage, a QA engineer aiming to craft realistic load tests, or a support engineer needing detailed transaction contexts, Logzly has you covered.

Key Features:
- **Automated Parsing**: Scans and parses *.log* files in any specified directory, intelligently crafting regex from nginx log formats.
- **Insightful Summaries**: Provides a comprehensive recap of log stats, including request counts by status code, navigation agents, and API routes.
- **Advanced Filtering**: Excludes static files, non-RESTful requests, and specific status codes for focused analysis.
- **Intelligent Transformations**: Enhances log data by mapping URLs to API routes, decoding `JWTs` to user subjects, and classifying user agents by device type.
- **Flexible Output**: Saves analysis results to new log files or directly to `InfluxDB 2.0`, based on user-configured preferences.

Designed for developers by developers, `Logzly` is your go-to tool for navigating the complexities of log data, transforming raw logs into actionable insights with ease. Dive into Logzly today and unlock the full potential of your access logs!
