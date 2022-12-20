# Nvidia Stock Alerter
Alerts you when a specific Nvidia product has stock available.

## Downloads
See the [Releases](https://github.com/BootBlock/nvidia-stock-alerter/releases) section for available downloads; only Windows is supported.
[.NET 7](https://dotnet.microsoft.com/en-us/download/dotnet/7.0) is required (download the Desktop Runtime x64 version).

## Which Regions are Supported?
* UK

## Which Products are Supported?
* GeForce RTX 4090
* GeForce RTX 4080

* GeForce RTX 3090, 3090 Ti
* GeForce RTX 3080, 3080 Ti
* GeForce RTX 3070, 3070 Ti
* GeForce RTX 3060, 3060 Ti

## What Does it Look Like?

Below is the default UI state before any checking has been performed.

![nsa_mainwindow1](https://user-images.githubusercontent.com/18527642/208289030-8c548184-c297-4e94-b279-7ebe7c1c260e.png)

This particular screenshot shows the UI state after stock has been detected. Clicking on the *Visit Product URL* link directly opens the purchase page for the product, if available.

![nsa_mainwindow2](https://user-images.githubusercontent.com/18527642/208289024-795e3fff-ad33-4361-8518-01bdcf8ea651.png)

## How Do I Install Nvidia Stock Alerter?
Download the latest version (see **Downloads** section, above) and extract the `.zip` archive to a location of your choice. Ideally, don't extract it to `Program Files` as Windows will not allow it to write to its own directory which is required as NSA stores its settings right along with the executable. Extract with paths as the archive doesn't include the root level `NividaStockAlerter` directory.

## How Do I Update?
You can use the built-in update checker to check for updates. Please note that currently you'll need to select *Download to File...* from within the update checker interface as it does not yet support updating via a `.zip` archive.

Once downloaded, either via the update checker or manually downloaded from this site, delete the existing `Nvidia Stock Alerter` directory and extract the new archive to a location of your choice. You can extract the archive over the existing installation if you wish to keep your existing settings.

## Where Are the Settings Saved?
Within the NvidiaStockAlerter directory, there is a directory called `ApplicationData` that contains all settings. NSA is an entirely portable application.
