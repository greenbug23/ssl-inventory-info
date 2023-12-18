# ssl-inventory-info
Audt ssl certs on hosts to find specific certificates
## Centralized SSL Certificate Record and Management

This repository houses scripts and tools to centrally track and manage SSL certificates across various systems and appliances, regardless of their differing operating systems and certificate storage locations.

**Problem:**

- Decentralized SSL certificate storage across systems leads to difficulty in tracking expiration dates, issuers, and locations.
- Manual efforts to monitor each system are time-consuming and error-prone.

**Solution:**

- Scripts automatically discover and record information about *.crt files on each system.
- Captured data includes:
    - Certificate Expiration Date
    - Certificate Authority (CA)
    - Certificate Store Directory Path

**Benefits:**

- **Proactive management:** Identify expiring certificates before outages occur.
- **Centralized view:** Gain a comprehensive overview of all system certificates.
- **Improved efficiency:** Automate manual tasks and reduce the risk of human error.

**Usage:**

1. **Deploy the scripts:**
    - Copy the scripts to a central location accessible by all systems.
    - Configure each script with any necessary system-specific information.
2. **Run the scripts:**
    - Execute the scripts manually or schedule them to run periodically (e.g., daily).
3. **Analyze the results:**
    - The scripts will output log files containing detailed information about discovered certificates.
    - Use this data to plan renewal/migration activities before certificates expire.

**Additional Features:**

- **Email notifications:** Send alerts for upcoming certificate expirations.
- **Certificate validation:** Verify certificate validity and chain of trust.
- **Integration with management platforms:** Export data to ticketing systems or monitoring tools.

**This initial implementation provides a solid foundation for centralized SSL certificate management. Feel free to extend and customize the scripts to meet your specific needs.**

**Disclaimer:** This script is provided for informational purposes only and should be customized to fit your specific environment. The author is not responsible for any consequences of using this script.

**Feel free to contribute to this project and improve the functionality!**


