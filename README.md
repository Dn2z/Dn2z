# Hey, It's MK

I'm learning **malware analysis** and **digital forensics (DFIR)**. I build small defensive security tools in Python to understand how analysts actually work.

Everything I build is for defensive research and is tested on harmless samples.

## Projects

| Project | What it does |
| --- | --- |
| [malware-hash-checker](https://github.com/Dn2z/malware-hash-checker) | Hashes files and checks them against a local database and VirusTotal |
| [pe-file-analyzer](https://github.com/Dn2z/pe-file-analyzer) | Static analysis of Windows executables: sections, entropy, imports, suspicious APIs |
| [ioc-extractor](https://github.com/Dn2z/ioc-extractor) | Pulls IPs, domains, URLs, registry keys and more out of files, including UTF-16 strings |
| [yara-scanner](https://github.com/Dn2z/yara-scanner) | Scans files with YARA rules and reports matches with string offsets |

Together they follow the same triage flow analysts use on a suspicious file: **hash it, inspect its structure, extract indicators, then match it against detection rules.**

## Toolbox

Python · YARA · pefile · Git & GitHub

## Currently learning

Malware analysis · Digital forensics & incident response · Writing detection rules · Reverse engineering

Ideas and feedback are welcome. Feel free to open an issue on any repo.
