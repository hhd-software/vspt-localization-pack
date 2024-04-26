# Localization Pack for Virtual Serial Port Tools

This repository hosts a community-based development page of free localization pack for [Virtual Serial Port Tools](//www.hhdsoftware.com/virtual-serial-port-tools) product from HHD Software Ltd.

Please browse our [Wiki](https://github.com/hhd-software/vspt-localization-pack/wiki) for detailed instructions on using this repository and localization utility.

## Localization Utility System Requirements

* Operating system: Windows 7 or later (both 32 and 64 bit supported).
* .NET 4.8 Framework

## Finished Language Packs

Complete language packs are available directly in Virtual Serial Port Tools. Go to the **Tools » Settings » Languages** tab to see the list of published language packs and to download them.

Currently, the following language packs are complete for latest version of Virtual Serial Port Tools:


## Manually Building Language Packs

You can manually build non-complete language pack and use it in Virtual Serial Port Tools. Follow this procedure:

1. Install Git client.
2. Execute a Clone command for the following repository:

   ```
   git clone https://github.com/hhd-software/vspt-localization-pack.git
   ```

3. Switch to your language's branch.
4. Run the supplied `langtool.exe` utility (located at the root of the repository) and open the `rsp.xml` project file.
5. Execute the **File » Compile…** command and select the language you want to compile.
6. Make sure you have Virtual Serial Port Tools installed. Compile the Language Pack.
7. Run Virtual Serial Port Tools and select the language pack in corresponding box on the toolbar.

## Acknowledgements
