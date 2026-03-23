# SAP GUI Launcher

A Fiori app that launches SAP GUI transactions directly from the Fiori Launchpad on Windows. Pick a transaction, click it, and SAP GUI opens with the right connection and T-code.

## How it works

The app reads your SAP GUI favorites via the `ZFAVORITES_SRV` OData service and displays them as tiles. Clicking a tile generates a `.sap` shortcut file that opens SAP GUI for Windows with the correct system, client, and transaction code.

## Requirements

- SAP GUI for Windows installed on the client machine
- SAP Fiori Launchpad (on-premise or BTP)
- Backend OData service `ZFAVORITES_SRV` deployed and activated

## Setup

1. Deploy the UI5 app to your SAP system or Fiori Launchpad.
2. Activate the `ZFAVORITES_SRV` OData service in `/IWFND/MAINT_SERVICE`.
3. Add the app to a Fiori catalog and assign to users.

## License

See repository for license details.

## Contact

jonathanbragg@mindsetconsulting.com

Built by [Mindset Consulting](https://mindsetconsulting.com).
