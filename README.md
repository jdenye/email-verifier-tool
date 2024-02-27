# Email Verifier Tool in GoLang

## Overview
This project is a simple yet effective Email Verifier Tool developed in GoLang. It aims to validate email addresses by performing various checks on the domain, MX records, SPF records, and optionally DMARC records. The tool provides users with increased confidence in the validity of email addresses they input.

## How It Works
1. **User Input**: Users are prompted to enter an email address for verification.
2. **Domain Name Check**: The program extracts the domain name from the provided email address using basic GoLang packages like `bufio` and `strings`.
3. **MX Records Check**: Utilizing the `net` package, the tool performs DNS lookups to verify the presence of valid Mail Exchange (MX) records for the domain.
4. **SPF Records Check**: Through DNS queries, the program ensures the existence of a legitimate Sender Policy Framework (SPF) record associated with the domain.
5. **Optional DMARC Check**: Users have the option to include a check for Domain-based Message Authentication, Reporting & Conformance (DMARC) records for additional email authentication and reporting mechanisms.

## Getting Started
To run this tool locally, follow these steps:
1. Clone this repository to your local machine.
2. Ensure you have GoLang installed.
3. Navigate to the project directory in your terminal.
4. Run `go run main.go` to start the program.
5. Follow the on-screen instructions to verify email addresses.

## Technologies Used
- GoLang
- Basic GoLang packages: `bufio`, `os`, `net`, etc.

## Contribution
If you'd like to contribute to this project, feel free to submit a pull request or open an issue.

## Contact
For any questions or feedback regarding this project, you can reach me at github.com/jdenye.

Let's connect and innovate together! 🚀 #GoLang #EmailVerification #GitHubProject
