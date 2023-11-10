## NetHunter Installation for Termux

To install NetHunter on Termux, follow these steps:

1. Update package information:
    ```bash
    apt update -y
    ```

2. Set up storage:
    ```bash
    termux-setup-storage
    ```

3. Install wget:
    ```bash
    pkg install wget -y
    ```

4. Download NetHunter installation script:
    ```bash
    wget -O install-nethunter-termux https://offs.ec/2MceZWr
    ```

5. Make the script executable:
    ```bash
    chmod +x install-nethunter-termux
    ```

6. Run the installation script:
    ```bash
    ./install-nethunter-termux
    ```

7. Initialize NetHunter:
    ```bash
    nh -r
    ```

8. Edit resolv.conf using nano:
    ```bash
    nano /etc/resolv.conf
    ```

9. Update package information again:
    ```bash
    apt update
    ```

10. Install dbus-x11:
    ```bash
    apt install dbus-x11 -y
    ```

11. Open system settings:
    ```bash
    settings
    ```

12. Start NetHunter Kex:
    ```bash
    nh kex
    ```

Follow these steps to successfully install and configure NetHunter on your Termux environment.