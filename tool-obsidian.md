## Installing Obsidian on Raspberry Pi using Flatpak

To install Obsidian on your Raspberry Pi using Flatpak, follow these steps:

1. **Install Flatpak:**

    ```bash
    sudo apt install flatpak
    ```

2. **Add the Flathub repository:**

    ```bash
    sudo flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
    ```

3. **Reboot your Raspberry Pi:**

    ```bash
    sudo reboot
    ```

4. **Install Obsidian:**

    ```bash
    flatpak install flathub md.obsidian.Obsidian
    ```

5. **Run Obsidian:**

    ```bash
    flatpak run md.obsidian.Obsidian
    ```

---

These commands are based on the guide provided by [Pi My Life Up](https://pimylifeup.com/raspberry-pi-obsidian/).

Let me know if you need further assistance!
