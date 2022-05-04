---
id: octoprint-plugin-setup-manual-link
title: Link OctoPrint with a 6-digit code
---

Follow this guide in one of these 2 rare cases:

* You are trying to re-link OctoPrint. There are only [a few reasons](/docs/user-guides/relink-octoprint/) why you need to re-link OctoPrint.
* Your OctoPrint can't be identified at the last step in [The Spaghetti Detective Setup Guide](/docs/user-guides/octoprint-plugin-setup/). You don't need a 6-digit code if your OctoPrint can be identified and linked automatically.

:::caution
If you are setting up The Spaghetti Detective for the first time, you should follow [The Spaghetti Detective Setup Guide](/docs/user-guides/octoprint-plugin-setup) first. **Please DO NOT PROCEED** if you haven't done so.
:::



import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

## Step 1: Launch the Setup Wizard in the plugin

:::note

Most of the time the Setup Wizard will automatically launch when you open OctoPrint. Skip this step if it's the case.

:::

1. Open OctoPrint page in a browser.
1. Open OctoPrint settings page by clicking the wrench icon (**🔧**).
1. Scroll down to the bottom of the list on the left-hand side.
1. Click "**Access Anywhere - The Spaghetti Detective**".
1. Click "**Troubleshooting**".
1. Scroll down to the bottom, and click "**Re-run Wizard**".

![Install the Plugin](/img/user-guides/setupguide/tsd-plugin-rerun-wizard.gif)

## Step 2: Follow the Setup Wizard

:::note

Follow instructions in the "**📱  Mobile App**" tab if you are using The Spaghetti Detective mobile app, or the "**🌐  Web App**" tab if you are using the web app.

:::

<Tabs
  defaultValue="mobile"
  values={[
    {label: '📱  Mobile App', value: 'mobile'},
    {label: '🌐  Web App', value: 'web'},
  ]}>
  <TabItem value="mobile">

1. Click the "**Setup Plugin**" button.
1. On the next page, click on “**Continue with Mobile App**".
1. Since you have already downloaded the mobile app and signed up for an account, just click “**Continue**” here.
  :::caution
  If you haven't signed up for an The Spaghetti Detective account, stop here and follow [The Spaghetti Detective Setup Guide](/docs/user-guides/octoprint-plugin-setup) first.
  :::
1. Now you should see a page that asks you for a 6-digit verification code. Keep this browser tab open while you obtain the 6-digit code in The Spaghetti Detective app.

![TSD Wizard Page](/img/user-guides/setupguide/tsd-plugin-wizard-mobile.gif)

  </TabItem>
  <TabItem value="web">

1. Click the "**Setup Plugin**" button.
1. On the next page, click on “**Continue with Web Site**".
1. Since you have already signed up for an account, just click “**Continue**” here.
  :::caution
  If you haven't signed up for an The Spaghetti Detective account, stop here and follow [The Spaghetti Detective Setup Guide](/docs/user-guides/octoprint-plugin-setup) first.
  :::
1. Now you should see a page that asks you for a 6-digit verification code.

![TSD Wizard Page](/img/user-guides/setupguide/tsd-plugin-wizard-web.gif)

  </TabItem>
</Tabs>

## Step 3: Launch the "Link OctoPrint" wizard in The Spaghetti Detective app

:::note
If you wan to re-link OctoPrint to an existing printer, you should do [step 3a](#step-3a-launch-the-re-link-octoprint-wizard-in-the-spaghetti-detective-app) instead.
:::

<Tabs
  defaultValue="mobile"
  values={[
    {label: '📱  Mobile App', value: 'mobile'},
    {label: '🌐  Web App', value: 'web'},
  ]}>
  <TabItem value="mobile">

1. Open The Spaghetti Detective mobile app. You should see a screen with a big "**Link OctoPrint**" button. If you don't see that screen, tap the menu icon (☰) on the top-left corner, and select "Link New Printer".

<div style={{display: "flex", justifyContent: "center"}}><img src="/img/user-guides/setupguide/launch-manual-link-mobile.jpg" /></div>

  </TabItem>
  <TabItem value="web">

1. Open [The Spaghetti Detective web app](https://app.thespaghettidetective.com/) in another browser tab. You should see a screen with a big "**Link OctoPrint**" button. If you don't see that screen, click "Link OctoPrint Printer" button.

<div style={{display: "flex", justifyContent: "center"}}><img src="/img/user-guides/setupguide/launch-manual-link-web.jpg" /></div>

  </TabItem>
</Tabs>

## Step 3a: Launch the "Re-Link OctoPrint" wizard in The Spaghetti Detective app

:::note
If you want to link OctoPrint to a new printer, you should do [step 3](#step-3-launch-the-link-octoprint-wizard-in-the-spaghetti-detective-app) instead.
:::

1. From the printer screen, click the kebab menu (⋮) on the top right of the screen.
2. Click "**Configure 🔧**".
3. Scroll down to the bottom and click "**Re-link OctoPrint**".

<div style={{display: "flex", justifyContent: "center"}}><img src="/img/user-guides/setupguide/launch-relink-wizard.gif" /></div>


## Step 4: Obtain the 6-digit code in The Spaghetti Detective app

<Tabs
  defaultValue="mobile"
  values={[
    {label: '📱  Mobile App', value: 'mobile'},
    {label: '🌐  Web App', value: 'web'},
  ]}>
  <TabItem value="mobile">

1. Assuming you have followed [this Setup Guide](/docs/user-guides/octoprint-plugin-setup) and installed the plugin, you can simply click the "**Yes, plugin is installed**" button.
1. On the next screen, if it is stuck in "Scanning..." for more than 1 minutes, tap the "**Manual Setup**" link.
1. Tap "**I'm ready now**" on the next screen.
1. Now you will see a screen with a 6-digit verification code. This is the code you will use the manually link OctoPrint. You can long-press the number to copy it to the clipboard.

<div style={{display: "flex", justifyContent: "center"}}><img src="/img/user-guides/setupguide/manual-link-mobile.gif" /></div>

  </TabItem>
  <TabItem value="web">

1. Assuming you have followed [this Setup Guide](/docs/user-guides/octoprint-plugin-setup) and installed the plugin, you can simply click the "**Next>**" button.
1. On the next screen, if it is stuck in "Scanning..." for more than 1 minutes, tap the "**Manual Setup**" link.
1. Tap "**Next >**" on the next screen.
1. Now you will see a screen with a 6-digit verification code. This is the code you will use the manually link OctoPrint. You can press Ctrl-C (Windows) or Cmd-C (Mac) to copy the 6 digit code to the clipboard.

<div style={{display: "flex", justifyContent: "center"}}><img src="/img/user-guides/setupguide/manual-link-web.gif" /></div>

  </TabItem>
</Tabs>

## Step 5: Enter the 6-digit code in the plugin Setup Wizard

1. Go back to the browser tab in which your OctoPrint is open.
1. Enter the 6-digit code you obtained in [the previous step](#step-3-link-octoprint-to-your-the-spaghetti-detective-account). You can press Ctrl-V (Windows) or Cmd-V (Mac) to paste the code if you have previously copied them in the clipboard.
1. Restart OctoPrint. This is necessary only if you are re-linking OctoPrint.

<div style={{display: "flex", justifyContent: "center"}}><img src="/img/user-guides/setupguide/tsd-plugin-code-success.gif" /></div>
<br />

**Hooray! You are done! You can close the Setup Wizard window now.**

## Step 6 (optional): Give your printer a shinny name!

Optionally, you can now give your printer a name. If you skip this step, your printer will have the default name "*My Awesome Cloud Printer*".

<Tabs
  defaultValue="mobile"
  values={[
    {label: '📱  Mobile App', value: 'mobile'},
    {label: '🌐  Web App', value: 'web'},
  ]}>
  <TabItem value="mobile">

<div style={{display: "flex", justifyContent: "center"}}><img src="/img/user-guides/setupguide/link-success-mobile.gif" /></div>

  </TabItem>
  <TabItem value="web">

<div style={{display: "flex", justifyContent: "center"}}><img src="/img/user-guides/setupguide/link-success-web.gif" /></div>

  </TabItem>
</Tabs>

<b />

