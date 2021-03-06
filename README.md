# Bluetooth Low Energy sample

Shows how to use the Windows Bluetooth LE APIs to act either as a BLE client or server. 

> **Note:** This sample is part of a large collection of UWP feature samples. 
> You can download this sample as a standalone ZIP file
> [from docs.microsoft.com](https://docs.microsoft.com/samples/microsoft/windows-universal-samples/bluetoothle/),
> or you can download the entire collection as a single
> [ZIP file](https://github.com/Microsoft/Windows-universal-samples/archive/master.zip), but be 
> sure to unzip everything to access shared dependencies. For more info on working with the ZIP file, 
> the samples collection, and GitHub, see [Get the UWP samples from GitHub](https://aka.ms/ovu2uq). 
> For more samples, see the [Samples portal](https://aka.ms/winsamples) on the Windows Dev Center. 

## Client

Shows how to act as a client to communicate with a Bluetooth Low Energy (LE) device
using the Bluetooth GATT protocol. Acts as a GATT client to access nearby GATT servers like
heart rate sensors or temperature sensors.

Specifically, this sample shows how to:

- Enumerate nearby Bluetooth LE devices
- Query for supported services
- Query for supported characteristics
- Read and write data
- Subscribe to indicate and notify events

## More Details
Search for "BT_Code" to find the portions of the sample that are particularly
relevant to Bluetooth.
Note in particular the "bluetooth" capability declaration in the manifest.

**Note** The Windows universal samples require Visual Studio to build and Windows 10 to execute.

To obtain information about Windows 10 development, go to the [Windows Dev Center](http://go.microsoft.com/fwlink/?LinkID=532421)

To obtain information about Microsoft Visual Studio and the tools for developing Windows apps, go to [Visual Studio](http://go.microsoft.com/fwlink/?LinkID=532422)

## Related topics

### Conceptual

* Documentation
  * [Bluetooth GATT Client](https://msdn.microsoft.com/windows/uwp/devices-sensors/gatt-client)
  * [Bluetooth GATT Server](https://msdn.microsoft.com/windows/uwp/devices-sensors/gatt-server)
  * [Bluetooth LE Advertisements](https://docs.microsoft.com/windows/uwp/devices-sensors/ble-beacon)
* [Windows Bluetooth Core Team Blog](https://blogs.msdn.microsoft.com/btblog/)
* Videos from Build 2017
  * [Introduction to the Bluetooth LE Explorer app](https://channel9.msdn.com/Events/Build/2017/P4177)
    * [Source code](https://github.com/Microsoft/BluetoothLEExplorer)
    * [Install it from the Microsoft Store](https://www.microsoft.com/store/apps/9n0ztkf1qd98)
  * [Unpaired Bluetooth LE Device Connectivity](https://channel9.msdn.com/Events/Build/2017/P4178)
  * [Bluetooth GATT Server](https://channel9.msdn.com/Events/Build/2017/P4179)

## System requirements

**Client:** Windows 10 Anniversary Edition

**Server:** Windows Server 2016 Technical Preview

**Phone:** Windows 10 Anniversary Edition

## Build the sample

1. If you download the samples ZIP, be sure to unzip the entire archive, not just the folder with the sample you want to build. 
2. Start Microsoft Visual Studio and select **File** \> **Open** \> **Project/Solution**.
3. Starting in the folder where you unzipped the samples, go to the Samples subfolder, then the subfolder for this specific sample, then the subfolder for your preferred language (C++, C#, or JavaScript). Double-click the Visual Studio Solution (.sln) file.
4. Press Ctrl+Shift+B, or select **Build** \> **Build Solution**.

## Run the sample

The next steps depend on whether you just want to deploy the sample or you want to both deploy and run it.

### Deploying the sample

- Select Build > Deploy Solution. 

### Deploying and running the sample

- To debug the sample and then run it, press F5 or select Debug >  Start Debugging. To run the sample without debugging, press Ctrl+F5 or selectDebug > Start Without Debugging. 
