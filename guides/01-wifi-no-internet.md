# Windows Wi-Fi has no internet

**Reported symptom:** “My laptop is connected to Wi-Fi, but websites don't load.”  
**Applies to:** Windows 11 laptop on a Wi-Fi network.  
**Goal:** Identify whether the problem is the laptop, Wi-Fi link, DNS, or a wider outage.

## Ask first

- When did it last work? Did you move locations or change networks?
- Do other devices on the same Wi-Fi work?
- Is every website affected, or only one site or work app? Is a VPN involved?
- What exact message appears in the browser or Windows network settings?

## Checks, in order

1. **Check scope.** If several devices on the same network fail, record that and contact the network team or internet provider through the approved channel. If only one laptop fails, continue.
2. **Check the connection.** Select the network icon in the taskbar. Confirm Airplane mode is off and Wi-Fi is on. Confirm the laptop is connected to the expected network. Reconnect if appropriate. A connection to Wi-Fi alone does not prove internet access.
3. **Check another website and, if available, another device.** If one website fails but others work, capture the URL and error. If work apps alone fail, check the required VPN or organization service status.
4. **Run Windows diagnostics.** Open **Get Help** and run the **Network and Internet troubleshooter**. Record what it reports before applying any suggested change.
5. **Separate connectivity from name resolution.** In a terminal, run `ipconfig` and record whether the Wi-Fi adapter has an address and a default gateway (redact these in public notes). Try `ping 1.1.1.1` and `nslookup example.com`. If the IP test works but the name lookup fails, investigate DNS. A failed ping by itself is not proof of an outage; some networks block ICMP.
6. **Retry after an approved simple fix.** If the connection is stale, disconnect and reconnect or restart the laptop with the user's agreement. Do not reset network settings or change DNS on a managed computer without approval.

## Verify and document

Have the user open the original website or work app. Note the network, scope, error message, checks performed, and the successful or failed retest. Do not publish actual local IPs, device names, or VPN details.

## Escalate when

- Multiple users or devices are affected.
- The adapter is missing, the network repeatedly disconnects, or a VPN/work-only service fails.
- DNS or gateway results point to organization infrastructure, or an approved change did not help.

## Reference

- [Microsoft: Fix Wi-Fi connection issues in Windows](https://support.microsoft.com/en-us/windows/experience/connectivity-networking/fix-wi-fi-connection-issues-in-windows)
