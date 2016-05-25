---
        public const string DeviceConnectionString = "<replace>";
-   Replace the above placeholder with device connection string you obtained in [Step 1](#Step-1:-Prerequisites) and save the changes.
-   Choose the right architecture (ARM) and set the debugging method to "Remote Machine":
-   To deploy the binaries on your device, right-click on the UWPSample project in the **Solution Explorer**, select **Properties** and navigate to the **Debug** tab:
    Type in the IP Address of your device. Make sure the "Use authentication" box is unchecked.
-   Build the solution.


-   You should be able to see the events received in the DeviceExplorer's data tab.

-   On Windows, refer "Send cloud-to-device messages" in [DeviceExplorer Usage document][lnk-device-explorer] for instructions on sending messages to device.
-   If you are running other OS, please use the JavaScript tool [iot-hub explorer tool][lnk-iothub-explorer]