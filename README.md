# ToggleWMRHeadset
<P>Description</P>
<UL>
<LI>Two PowerShell scripts to disable &amp; enable WMR VR headsets
</UL>
<P>Why would I want to use these scripts?</P>
<UL>
<LI>Are you tired of your WMR headset starting up when you don't want it to? If yes, you can control your WMR VR headset without the need to physically unplug your headset when you don't want to use it.
</UL>
Requirements:
<OL>
<LI>You need to allow "unrestricted" scripts: https://docs.vmware.com/en/vRealize-Automation/7.1/com.vmware.vra.iaas.hp.doc/GUID-9670AFC5-76B8-4321-822A-BCE05800DB5B.html
<LI>You need to lookup the device id of your headset and replace the value of "InstanceId" above which can be found via Device Manager
<OL>
<LI>Open Device Manager
<LI>Find "Mixed Reality Devices", then right-click on your headset and choose "Properties"
<LI>Select "Events" tab
<LI>The ID you want begins (and includes USB)
<LI>Copy/paste this ID replacing the single-quoted string in the Line #3 (you can't miss it!)
</OL>
<LI>Create shortcuts on your desktop to these scripts and make sure to run them via PowerShell
</OL>
