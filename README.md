# Buddy for Excel downloads

Windows private beta builds of Buddy for Excel are distributed here. This repository contains public download documentation only; application source and development files are not included.

The SEC beta includes a local HTTPS add-in and its own authenticated SEC service. Install it, start Buddy for Excel Private Beta from the Start menu, enter an application name and real contact email, review the local certificate and Excel registration permission, then choose Start / update service and Open beta in Excel.

In Excel enable + > Plugins > SEC Model Kit. In Settings > Plugins set the server URL to https://localhost:8767/mcp and paste the service key using Copy service key in the launcher. Choose Save and connect. Keep the service running while using Excel. Configure your AI provider separately to chat with the agent.

This is a Windows development sideload for Microsoft Excel desktop, not a Marketplace installation. Organization policy may block development add-ins. The installer is unsigned. Stop service ends the local server; Remove setup or uninstall removes only this beta's certificate trust and matching Excel registration. Configuration and workbooks are kept.

Only finished installers are release assets. GitHub's automatic Source code ZIP/tar links contain only this downloads documentation, not application source.