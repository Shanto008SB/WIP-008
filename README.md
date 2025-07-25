# WIP-008
-------------
Domain Reconnaissance Tool 🕵️‍♂️A powerful, user-friendly GUI tool built with Python for performing reconnaissance on a target domain. It automates the discovery of subdomains, checks their live status, detects Web Application Firewalls (WAFs), and finds historical IP information, saving all findingsLive Status: Shows which subdomains are active and which are not.Detects Firewalls (WAF): Tries to identify common web application firewalls.Finds Historical IPs: Looks up past IP addresses associated with the domain.Saves Results: Automatically saves a full report to a .txt file.Easy to Use: A clean and simple graphical interface.🚀 How to Use1. SetupFirst, clone the project and install the necessary packages.

# Clone the project from GitHub

```bash
git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
```

2.  **Navigate to the project directory:**
    ```bash
    cd WIP-008
    ```

3.  **Install the required packages using the `requirements.txt` file:**
    *(First, ensure you have a `requirements.txt` file in your project directory with the content below).*
    ```bash
    pip install -r requirements.txt
    ```

    **`requirements.txt`:**
    ```text
    customtkinter
    requests
    dnspython
    beautifulsoup4
    ```

---

## Usage

1.  Run the application from your terminal:
    ```bash
    python recon_kal.py
    ```

2.  A splash screen will appear for 3 seconds, followed by the main application window.

3.  Enter the target domain (e.g., `example.com`) in the input field.

4.  Click the **"Start Scan"** button or press the `Enter` key to begin.

5.  The tool will start the reconnaissance process. Output will be printed in the textbox in real-time.

6.  To stop the scan before it completes, click the **"Stop Scan"** button.

7.  Once the scan is finished (or stopped), a status message will confirm the completion, and the full results will be available in the corresponding log file (e.g., `example.com_recon_output.txt`).

---

## External Dependencies

This tool relies on the following third-party services. Its functionality is dependent on their availability and their current APIs.

-   **crt.sh**: For subdomain discovery.
-   **ViewDNS.info**: For historical IP lookups.
-   **ip-api.com**: For IP address whois/ownership information.

---

## Disclaimer

This tool is intended for educational and ethical purposes only. The user is responsible for their actions and must have explicit permission to scan any target domain. The author is not responsible for any misuse or damage caused by this program.
