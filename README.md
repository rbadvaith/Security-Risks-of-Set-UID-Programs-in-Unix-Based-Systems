This project explores the security implications of Set-UID programs in Unix-based operating systems. Through hands-on experiments, it examines why critical commands like passwd require root privileges and demonstrates how improper Set-UID configurations can lead to privilege escalation vulnerabilities. The study analyzes security flaws in older shells like zsh, investigates why bash behaves differently under Set-UID, and demonstrates the risks of using the system() function within Set-UID programs. Finally, it discusses mitigation strategies, including secure programming practices and environmental variable restrictions, to prevent unauthorized privilege escalation.
