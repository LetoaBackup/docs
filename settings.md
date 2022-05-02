## Verification Role

The verification role is a role provided to users when they successfully verify within your server. To setup this role, head to `Letoa Dashboard > Your Server > Verification > Main Verification Settings > Verification Role`. Once you click on the select menu, all the roles will be shown within your server.

### Verification Role Errors

If you try saving your settings and it results in an error, it could be one of many reasons. Firstly check that the `MaRy` role is above the role you are trying to provide to verified users, and try again. If it still does not work, please contact [support](https://discord.letoa.me).

!> Make sure the role doesn't have any privileged permissions as it could result in your users misusing them.

## Logging Channel

A logging channel is where all logs of the bot will be sent. Logs include:

-   Verified user successfully
-   Failed to verify a user
-   Proxy / VPN detected

When selecting your logging channel, make sure the bot has permissions to view the channel. If not, it will result in an error.

## In App Customization

We allow Gold Plan and above users to customize their in-app embed.

## Custom Domain

!> You must have the **Platinum Plan** to be able to configure this setting.

?> We are using Cloudflare for the guide, it is easy and simple to use.

### Step 1 - Configuring Custom Domain

Head over to the Letoa Dashboard. And go to your designated server where you want to configure your Custom Domain.

![](https://cdn.upload.systems/uploads/8lOM6rKK.png) ![](https://cdn.upload.systems/uploads/HYbM7ESv.png)

Input your custom domain without the **http** or **https** as shown below.

![](https://cdn.upload.systems/uploads/kqTdLWuK.png)

### Step 2 - Selecting Domain

Now head over to Cloudflare and select your domain you want to use. Head over to the "DNS" tab on the navigation panel on the left.

![](https://cdn.upload.systems/uploads/FpfNiSB3.png)

### Step 3 - Configuring DNS

Now, create a new record. Make sure the type is **CNAME**. And for the **Name**, make it **"@"**. For the "Target", configure it to "**custom.letoa.me**"

![](https://cdn.discordapp.com/attachments/882062292810883073/970623761923575860/unknown.png?size=4096)

### Step 4 - Previewing your website

Now head to your domain. It may take a while to update but it shouldn't take too long. Enjoy using **Custom Domains** through **Letoa**!
