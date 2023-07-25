# ApiMinerSolarEdge

Document for `SolarEdge` inverter `API Miner`.

When an `Arkreen` user want to add their `SolarEdge` inverters to `Arkreen Network` as `API Miner`, they need provide 2 key information:
* `Site ID`, which be used to specific the power plant that `Arkreen Network` can access, can be found in [SolarEdge Monitoring Service](https://monitoring.solaredge.com/),
* `API Key`, which be used to authorize `Arkreen Network` to access your site data;


There are 3 options can be used to get the `Site ID` and `API Key`:
* **Option 1**: Get them yourself by logging in [SolarEdge Monitoring Service](https://monitoring.solaredge.com/)
* **Option 2**: Ask your installer through email
* **Option 3**: Get them from [SolarEdge Chat Support](https://www.solaredge.com/us/support)

# **Option 1**: Get them yourself

## Step 1

Log in to your [SolarEdge Monitoring Account](https://monitoring.solaredge.com/).

## Step 2

If your account permissions are set to `“Admin”` the menu on the top will include an `Admin` link. Click to go to the `Admin` area.

## Step 3

Once you’re in the `Admin` area, click `Site Access`, scroll down to the `API Access` area, then click `New key` button and copy the generated `API Key` and `Site ID` and click `Save` button to save them.




# **Option 2**: Ask your installer through email

If you don’t have the `Admin` menu link, you can request `API Key` and `Site ID` from your installer via email, here’s a sample email:

```
Hello My Installer,

I am tracking the energy output of my panels with a online system, can you please reply with my API key and Site ID?

Thanks!

You!
```


# **Option 3**: SolarEdge Chat Support

## Step 1

Click the link to go to [SolarEdge Chat Support](https://www.solaredge.com/us/support).

## Step 2

Click `Chat with an Agent`, Before you get connected with a representative, you must answer a series of questions.

## Step 3

Enter your email address linked to your `SolarEdge` account.

## Step 4

Enter the `serial number` for your inverter. the `serial number` can be found in `SolarEdge` inverter `nameplate`, named `SN` usually, for example:

![SolarEdge inverter nameplate](./inverter.png)

## Step 5

Once connected with a live chat representative. Copy and paste the following message into the chat: 

```
Hi, I need to get my API keys so that I can track the energy output of my panels. The site ID for my inverter is: (paste in your serial number)
```