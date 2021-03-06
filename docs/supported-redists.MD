# Supported Redistributables

Microsoft publishes a list of supported Visual C++ Redistributables here: [The latest supported Visual C++ downloads](https://support.microsoft.com/en-gb/help/2977003/the-latest-supported-visual-c-downloads). VcRedist includes manifests for the supported Redistributables and the full list of available Redistributbles.

By default Get-VcList will only export the list of supported Redistributables from the internal manifest. The supported list includes the following XML structure.

```xml
<?xml version="1.0" encoding="UTF-8"?>
<Redistributables>
    <Platform Architecture="x64" Release="2008" Install="/Q">
        <Redistributable>
            <Name>Visual C++ 2008 Service Pack 1 Redistributable Package MFC Security Update</Name>
            <ShortName>SP1MFC</ShortName>
            <URL>https://www.microsoft.com/en-us/download/details.aspx?id=26368</URL>
            <ProductCode>{5FCE6D76-F5DC-37AB-B2B8-22AB8CEDB1D4}</ProductCode>
            <Download>https://download.microsoft.com/download/5/D/8/5D8C65CB-C849-4025-8E95-C3966CAFD8AE/vcredist_x64.exe</Download>
        </Redistributable>
    </Platform>
    <Platform Architecture="x86" Release="2008" Install="/Q">
        <Redistributable>
            <Name>Visual C++ 2008 Service Pack 1 Redistributable Package MFC Security Update</Name>
            <ShortName>SP1MFC</ShortName>
            <URL>https://www.microsoft.com/en-us/download/details.aspx?id=26368</URL>
            <ProductCode>{9BE518E6-ECC6-35A9-88E4-87755C07200F}</ProductCode>
            <Download>https://download.microsoft.com/download/5/D/8/5D8C65CB-C849-4025-8E95-C3966CAFD8AE/vcredist_x86.exe</Download>
        </Redistributable>
    </Platform>
    <Platform Architecture="x64" Release="2010" Install="/passive /norestart">
        <Redistributable>
            <Name>Visual C++ 2010 Service Pack 1 Redistributable Package MFC Security Update</Name>
            <ShortName>SP1</ShortName>
            <URL>https://www.microsoft.com/en-us/download/details.aspx?id=26999</URL>
            <ProductCode>{1D8E6291-B0D5-35EC-8441-6616F567A0F7}</ProductCode>
            <Download>https://download.microsoft.com/download/1/6/5/165255E7-1014-4D0A-B094-B6A430A6BFFC/vcredist_x64.exe</Download>
        </Redistributable>
    </Platform>
    <Platform Architecture="x86" Release="2010" Install="/passive /norestart">
        <Redistributable>
            <Name>Visual C++ 2010 Service Pack 1 Redistributable Package MFC Security Update</Name>
            <ShortName>SP1</ShortName>
            <URL>https://www.microsoft.com/en-us/download/details.aspx?id=26999</URL>
            <ProductCode>{F0C3E5D1-1ADE-321E-8167-68EF0DE699A5}</ProductCode>
            <Download>https://download.microsoft.com/download/1/6/5/165255E7-1014-4D0A-B094-B6A430A6BFFC/vcredist_x86.exe</Download>
        </Redistributable>
    </Platform>
    <Platform Architecture="x64" Release="2012" Install="/install /passive /norestart">
        <Redistributable>
            <Name>Visual C++ Redistributable for Visual Studio 2012 Update 4</Name>
            <ShortName>Update4</ShortName>
            <URL>https://www.microsoft.com/en-us/download/details.aspx?id=30679</URL>
            <ProductCode>{ca67548a-5ebe-413a-b50c-4b9ceb6d66c6}</ProductCode>
            <Download>https://download.microsoft.com/download/1/6/B/16B06F60-3B20-4FF2-B699-5E9B7962F9AE/VSU_4/vcredist_x64.exe</Download>
        </Redistributable>
    </Platform>
    <Platform Architecture="x86" Release="2012" Install="/install /passive /norestart">
        <Redistributable>
            <Name>Visual C++ Redistributable for Visual Studio 2012 Update 4</Name>
            <ShortName>Update4</ShortName>
            <URL>https://www.microsoft.com/en-us/download/details.aspx?id=30679</URL>
            <ProductCode>{33d1fd90-4274-48a1-9bc1-97e33d9c2d6f}</ProductCode>
            <Download>https://download.microsoft.com/download/1/6/B/16B06F60-3B20-4FF2-B699-5E9B7962F9AE/VSU_4/vcredist_x86.exe</Download>
        </Redistributable>
    </Platform>
    <Platform Architecture="x64" Release="2013" Install="/install /passive /norestart">
        <Redistributable>
            <Name>Update for Visual C++ 2013 and Visual C++ Redistributable Package</Name>
            <ShortName>Update</ShortName>
            <URL>https://support.microsoft.com/en-us/help/3179560/update-for-visual-c-2013-and-visual-c-redistributable-package</URL>
            <ProductCode>{ef6b00ec-13e1-4c25-9064-b2f383cb8412}</ProductCode>
            <Download>https://download.microsoft.com/download/0/5/6/056dcda9-d667-4e27-8001-8a0c6971d6b1/vcredist_x64.exe</Download>
        </Redistributable>
    </Platform>
    <Platform Architecture="x86" Release="2013" Install="/install /passive /norestart">
        <Redistributable>
            <Name>Update for Visual C++ 2013 and Visual C++ Redistributable Package</Name>
            <ShortName>Update</ShortName>
            <URL>https://support.microsoft.com/en-us/help/3179560/update-for-visual-c-2013-and-visual-c-redistributable-package</URL>
            <ProductCode>{61087a79-ac85-455c-934d-1fa22cc64f36}</ProductCode>
            <Download>https://download.microsoft.com/download/0/5/6/056dcda9-d667-4e27-8001-8a0c6971d6b1/vcredist_x86.exe</Download>
        </Redistributable>
    </Platform>
    <Platform Architecture="x64" Release="2015" Install="/install /passive /norestart">
        <Redistributable>
            <Name>Visual C++ 2015 Redistributable Update 3</Name>
            <ShortName>Update3</ShortName>
            <URL>https://www.microsoft.com/en-us/download/details.aspx?id=53840</URL>
            <ProductCode>{d992c12e-cab2-426f-bde3-fb8c53950b0d}</ProductCode>
            <Download>https://download.microsoft.com/download/6/A/A/6AA4EDFF-645B-48C5-81CC-ED5963AEAD48/vc_redist.x64.exe</Download>
        </Redistributable>
    </Platform>
    <Platform Architecture="x86" Release="2015" Install="/install /passive /norestart">
        <Redistributable>
            <Name>Visual C++ 2015 Redistributable Update 3</Name>
            <ShortName>Update3</ShortName>
            <URL>https://www.microsoft.com/en-us/download/details.aspx?id=53840</URL>
            <ProductCode>{e2803110-78b3-4664-a479-3611a381656a}</ProductCode>
            <Download>https://download.microsoft.com/download/6/A/A/6AA4EDFF-645B-48C5-81CC-ED5963AEAD48/vc_redist.x86.exe</Download>
        </Redistributable>
    </Platform>
    <Platform Architecture="x64" Release="2017" Install="/install /passive /norestart">
        <Redistributable>
            <Name>Visual C++ Redistributable for Visual Studio 2017</Name>
            <ShortName>RTM</ShortName>
            <URL>https://www.visualstudio.com/downloads/</URL>
            <ProductCode>{e2ee15e2-a480-4bc5-bfb7-e9803d1d9823}</ProductCode>
            <Download>https://download.visualstudio.microsoft.com/download/pr/100349091/2cd2dba5748dc95950a5c42c2d2d78e4/VC_redist.x64.exe</Download>
        </Redistributable>
    </Platform>
    <Platform Architecture="x86" Release="2017" Install="/install /passive /norestart">
        <Redistributable>
            <Name>Visual C++ Redistributable for Visual Studio 2017</Name>
            <ShortName>RTM</ShortName>
            <URL>https://www.visualstudio.com/downloads/</URL>
            <ProductCode>{56e11d69-7cc9-40a5-a4f9-8f6190c4d84d}</ProductCode>
            <Download>https://download.visualstudio.microsoft.com/download/pr/100349138/88b50ce70017bf10f2d56d60fcba6ab1/VC_redist.x86.exe</Download>
        </Redistributable>
    </Platform>
</Redistributables>
```