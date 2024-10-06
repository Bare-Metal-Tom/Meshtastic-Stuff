# Meshtastic-Stuff

Welcome to the Meshtastic-Stuff repository! Here you'll find useful scripts, tips, and resources related to Meshtastic, PowerShell, and LoRa mesh-networking.

---

## Tips for Successfully Running PowerShell Scripts

- **Run PowerShell as Administrator**: Ensure that you are running PowerShell with **Administrator privileges**. This is often required for scripts that need to make system-level changes or configurations.

- **Set Execution Policy**: If you've never run a PowerShell script on your Windows machine, you might need to set your **execution policy** first. By default, Windows restricts the execution of scripts for security purposes.

---

## How to Set Execution Policy

- To download and run a PowerShell `.ps1` file, you will need to run this command in an **Administrator PowerShell window**:
- Set-ExecutionPolicy Unrestricted

## However, use caution and understand the risks of having your execution policy set this way. Setting the execution policy to Unrestricted allows all scripts to run, including potentially harmful ones.

## Understand the Risks: Always be cautious when running scripts from unknown sources. Consider setting the execution policy back to a more restrictive setting after running your scripts.

---

## Alternative Execution Policy Setting
- **For a safer approach**: you can set the execution policy to RemoteSigned, which allows scripts you've written locally to run but requires that scripts downloaded from the internet be signed by a trusted publisher:
### Set-ExecutionPolicy RemoteSigned

---

## msh-py-cli-setup-export.ps1 Script
- This PowerShell script helps you automate the setup and export of configuration files for Meshtastic CLI.

## Important Disclaimer
-**Overwrite Warning**: After you generate your first config file, if you run the script again from the same directory, it will overwrite the config file with the latest exported data.

## Recommendation: Consider renaming your config files after exporting them to prevent unintentional overwrites.
- I will fix this flaw in a future version of the script

## Additional Notes:
-**Meshtastic Resources**: Learn more about Meshtastic
- All scripts provided here are meant to help you easily interact with Meshtastic devices and networks.
- Feel free to contribute or report any issues!

---

### Disclaimer: Use these scripts and tips at your own risk. Be sure to review and understand any script before running it on your system.

# License
- This project is released under The Unlicense, which means you are free to use, modify, and distribute the code without any restrictions.
