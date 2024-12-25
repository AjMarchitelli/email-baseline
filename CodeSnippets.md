# Proper superscript tag
```
    <span style="font-size:10px; vertical-align:7px;font-weight: normal;line-height: 0;">&reg;</span>
```
-OR-

```
    <sup style="line-height: 0px;font-size: 60%;vertical-align: 6px;">&reg;</sup>
```
Add this to css as well 👇🏽

```
    sup{
        line-height: 0px !important;
    }
```

# Start of bulleted List 
```
<table cellspacing="0" cellpadding="0" border="0" width="100%">
    <tr>
        <td valign="top" style="font-size:16px;line-height:22px;padding-right: 3px;">
        •
        </td>
        <td style="font-size:16px;line-height:22px;">
        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries.
        </td>
    </tr>
</table>
```



# Button w/o image template
```
    <tr>
        <td style="padding-top: 6px;padding-bottom: 24px;">
            <table role="presentation" cellpadding="0" cellspacing="0" border="0" bgcolor="#236e6e" align="center">
                <tbody>
                    <tr>
                        <td align="center" style="font-size:18px;line-height:24px;color: #ffffff;font-family:Arial, sans-serif;padding-top:20px;padding-bottom:20px;padding-left:40px;padding-right:40px;">
                            <a href="https://www.google.com" target="_blank" style="text-decoration: none;color: #ffffff;"><strong>LEARN MORE</strong></a>
                        </td>
                    </tr>
                </tbody>
            </table>
        </td>
    </tr>
```
## Button w/o image and rounded corners
```
    <tr>
        <td align="center" bgcolor="#243746" style="padding: 20px;">
            <table role="presentation" width="100%" border="0" cellspacing="0" cellpadding="0">
                <tr>
                    <td align="center">
                    <div>
                        <!--[if mso]>
                        <v:roundrect xmlns_v="urn:schemas-microsoft-com:vml" xmlns_w="urn:schemas-microsoft-com:office:word" href="http://google.com" style="height:34px;v-text-anchor:middle;width:205px;" arcsize="19px" strokecolor="#ee2a7a" fillcolor="#ee2a7a">
                            <w:anchorlock/>
                            <center style="color:#ffffff;font-family:Arial,Helvetica,sans-serif;font-size:13px;font-weight:700;">IM A BUTTON</center>
                        </v:roundrect>
                        <![endif]-->
                        <a href="http://google.com" target="_blank" style="background-color:#ee2a7a;border:1px solid #ee2a7a;border-radius:19px;color:#ffffff;display:inline-block;font-family: Arial, Helvetica, sans-serif;font-size:13px;font-weight: 700;line-height:32px;text-align:center;text-decoration:none;width:205px;-webkit-text-size-adjust:none;mso-hide:all;">IM A BUTTON</a>
                    </div>
                    </td>
                </tr>
            </table>
        </td>
    </tr>
```
# Button w/ image template 
```
    <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="100%">
    <tr>
        <td align="center" style="padding: 20px 0 30px;">
            <div>
                <!--[if mso]>
                <v:roundrect xmlns:v="urn:schemas-microsoft-com:vml" 
                    xmlns:w="urn:schemas-microsoft-com:office:word" 
                    href="{URL}" 
                    style="height:51px;v-text-anchor:middle;width:237px;" arcsize="0%" stroke="f" fillcolor="#0077A8;">
                    <w:anchorlock/>
                    <center>
                <![endif]-->
                <a href="{URL}" target="_blank" style="display:inline-block;font-size:14px;text-align:center;text-decoration:none;height:51px;width:237px;-webkit-text-size-adjust:none;">
                    <table role="presentation" cellspacing="0" border="0" cellpadding="0" style="padding:0px;margin:auto;background-color: #0077A8;width: 100%;height: 100%;">
                        <tr>
                            <td height="51" style="height:51px;padding-right:10px;mso-padding-top-alt: 0px;" align="center">
                                <table role="presentation"  cellspacing="0" border="0" cellpadding="0">
                                    <tr>
                                        <!-- Some words -->
                                        <td align="right" width="210" style="width:210px;box-sizing: border-box;line-height: 16px;mso-line-height-rule:exactly;mso-padding-bottom-alt: 10px;">
                                            <span style="font-size:14px;-webkit-font-smoothing: antialiased;-moz-osx-font-smoothing: grayscale;font-family: 'Arial', sans-serif;color:white;font-weight: 700;">
                                                SOME WORDS
                                            </span>
                                        </td>
                                        <!-- Some space -->
                                        <td width="8" style="width:8px;">
                                            &nbsp;
                                        </td>
                                        <!-- An image -->
                                        <td align="left" style="box-sizing: border-box;line-height: 16px;mso-line-height-rule:exactly;width: 24px;" width="24">
                                            <img width="6" height="11" src="anImage.png" alt="Imagery">
                                        </td>
                                    </tr>
                                </table>
                            </td>
                        </tr>
                    </table>
                </a>
                <!--[if mso]>
                    </center>
                </v:roundrect>
                <![endif]-->
            </div>
        </td>
    </tr>
    </table>
```
- What is this? ^
    - Makes a button that is 237 x 51 with text and image thats about 8px away
    - Things such as button sizing, font sizing, and spacing are project specific. Good reference point 


# A Navbar example
```
    <tr>
        <td class="nav-pad" height="40" style="background-color: #F1F7FA;height: 40px;font-family: 'Arial', sans-serif;font-size: 12px;line-height: 14px;font-weight: 700;color:#0077A8;mso-line-height-rule: exactly;">
            <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="100%">
                <tr>
                    <!-- <th valign="top" width="166"> -->
                    <th valign="top" width="31%">
                        <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="100%">
                            <tr>
                                <td valign="top" style="text-align: left;">
                                    <a style="text-decoration: none; font-family: Arial, sans-serif; font-size: 12px; line-height: 14px; text-align: center;color:#0077A8; cursor:pointer;mso-line-height-rule: exactly;" target="_blank" href="#">one</a>
                                </td>
                            </tr>
                        </table>
                    </th>
                    <th valign="top" width="18%">
                        <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="100%">
                            <tr>
                                <td valign="top" style="text-align: left;">
                                    <p style="margin: 0;">&nbsp;</p>
                                </td>
                            </tr>
                        </table>
                    </th>
                    <th valign="top" width="26%">
                        <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="100%">
                            <tr>
                                <td valign="top" style="text-align: center;">
                                    <a style="text-decoration: none; font-family: Arial, sans-serif; font-size: 12px; line-height: 14px; text-align: center;color:#0077A8; cursor:pointer;mso-line-height-rule: exactly;" target="_blank" href="#">two</a>
                                </td>
                            </tr>
                        </table>
                    </th>
                    <th valign="top" width="18%">
                        <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="100%">
                            <tr>
                                <td valign="top" style="text-align: right;">
                                    <p style="margin: 0;">&nbsp;</p>
                                </td>
                            </tr>
                        </table>
                    </th>
                    <th valign="top" width="36">
                        <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="100%">
                            <tr>
                                <td valign="top" style="text-align: right;" class="mobile-align-r">
                                    <a style="text-decoration: none; font-family: Arial, sans-serif; font-size: 12px; line-height: 14px; text-align: center;color:#0077A8; cursor:pointer;mso-line-height-rule: exactly;" target="_blank" href="#">three</a>
                                </td>
                            </tr>
                        </table>
                    </th>
                </tr>
            </table>
        </td>
    </tr>

```


# A Footer example
```
    <!-- Email Footer : BEGIN -->
    <table align="center" role="presentation" class="email-container" cellspacing="0" cellpadding="0" border="0" width="600" style="margin: 0 auto;">
        <!-- 4 Even Columns - Left align & stack on mobile: BEGIN -->
        <!-- Remove any classes t -->
        <tr>
            <td width="100%" style="width:100%;font-family:'Arial', sans-serif; font-size: 14px; line-height: 18px; text-align: center;background-color: #00263F;">
                <table role="presentation" cellpadding="0" cellspacing="0" border="0" width="100%" style="margin:0 auto;width: 100%;">
                    <tr width="100%">
                        <th valign="top" width="88" class="stack-column-center">
                            <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="100%">
                                <tr>
                                    <td class="center-on-narrow" style="padding: 0 32px 0 0;text-align: left;color: white;">
                                        <a style="text-decoration: none; font-family: Arial, sans-serif; font-size: 14px; line-height: 18px; color: white; cursor:pointer;font-weight: 700;" target="_blank" href="https://www.google.com">Unsubscribe</a>
                                    </td>
                                </tr>
                            </table>
                        </th>
                        <th valign="top" width="96"  class="stack-column-center">
                            <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="100%">
                                <tr>
                                    <td class="center-on-narrow" style="padding: 0 32px 0 0;text-align: left;color: white;">
                                        <a style="text-decoration: none; font-family: Arial, sans-serif; font-size: 14px; line-height: 18px; color: white; cursor:pointer;font-weight: 700;" target="_blank" href="https://www.google.com">Privacy&nbsp;Policy</a>
                                    </td>
                                </tr>
                            </table>
                        </th>
                        <th valign="top" width="122" class="stack-column-center">
                            <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="100%">
                                <tr>
                                    <td class="center-on-narrow" style="padding: 0 33px 0 0;text-align: left;color: white;">
                                        <a style="text-decoration: none; font-family: Arial, sans-serif; font-size: 14px; line-height: 18px; color: white; cursor:pointer;font-weight: 700;" target="_blank" href="https://www.google.com">Terms&nbsp;&amp;&nbsp;Conditions</a>
                                    </td>
                                </tr>
                            </table>
                        </th>
                        <th valign="top" width="82" class="stack-column-center">
                            <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="100%">
                                <tr>
                                    <td class="center-on-narrow" style="padding: 0 0 0 0;text-align: left;color: white;">
                                        <a style="text-decoration: none; font-family: Arial, sans-serif; font-size: 14px; line-height: 18px; color: white; cursor:pointer;font-weight: 700;" target="_blank" href="#">View&nbsp;in&nbsp;Browser</a>
                                    </td>
                                </tr>
                            </table>
                        </th>
                    </tr>
                <!-- 4 Even Columns : END -->  
                </table>
                <table role="presentation" cellpadding="0" cellspacing="0" border="0" width="100%" style="margin:0 auto;width: 100%;">
                    <tr>
                        <td align="left" style="color:white;padding-top:20px;font-family: 'Arial', sans-serif;font-size: 14px;text-decoration: none;">
                            ©2021 Biogen. All rights reserved. 01/21&nbsp;ADU&#8209;US&#8209;0112
                        </td>
                    </tr>
                    <tr>
                        <td align="left" style="color:white;font-family: 'Arial', sans-serif;font-size: 14px;text-decoration: none;">
                            225 Binney Street, Cambridge, MA 02142  |  1&#8209;800&#8209;456&#8209;2255
                        </td>
                    </tr>
                    <tr>
                        <td align="left" style="color:white;padding: 20px 0;font-family: 'Arial', sans-serif;font-size: 14px;">
                            All trademarks are the property of their respective owners.
                        </td>
                    </tr>
                    <tr>
                        <td align="left" class="mobile-pad-0" style="color:white;font-family: 'Arial', sans-serif;font-size: 14px;padding-right: 70px;">
                            This email is intended for residents of the United States, Puerto Rico, and US territories. This is a notification-only mailbox that cannot accept incoming email.
                        </td>
                    </tr>
                </table>
            </td>
        </tr>
    </table>
    <!-- Email Footer : END -->
```

# Desktop/Mobile swapping techniques 
```
    <!--Bare minimum css for swapping  -->

    //desktop styles
        .mobileOnly{
            display: none !important;
        }
        .mobileOnly-cell{
            display: none !important;
        }
        .desktopOnly{
            display: block !important;
        }
        .desktopOnly-cell{
            display: table-cell !important;
        }

    //mobile styles
    @media screen and (max-width: 600px) {
        .mobileOnly{
            display: block !important;
        }
        .mobileOnly-cell{
            display: table-cell !important;
        }

        .desktopOnly{
            display: none !important;
        }
        .desktopOnly-cell{
            display: none !important;
        }
    }

    // some css from cereberus thats included in baseline/starter
    /* What it does: Prevents Gmail from displaying a download button on large, non-linked images. */
    .a6S {
        display: none !important;
        opacity: 0.01 !important;
    }
    /* If the above doesn't work, add a .g-img class to any image in question. */
    img.g-img + div {
        display: none !important;
    }


    <!-- Swap an image -->
    <tr>
        <td>
            <img src="https://sf-asset-manager.s3.amazonaws.com/96751/168/7647.jpg" width="311" height="" alt="" border="0" style="width: 100%; max-width: 311px; height: auto; background: #fff; font-family: sans-serif; font-size: 15px; line-height: 15px; color: #555555; margin: auto; display: block;" class="g-img desktopOnly">
            <!--[if !mso]><\!-->
            <img class="mobileOnly g-img" src="https://sf-asset-manager.s3.amazonaws.com/96751/168/7648.jpg" width="260" style="width: 100%; max-width: 260px; height: auto; background: #fff; font-family: sans-serif; font-size: 15px; line-height: 15px; color: #555555; margin: auto; display: block;" alt=""/>
            <!-- <![endif]-->
        </td>
    </tr>



    <!-- Swap entire table cells -->
    <tr>
        <td class="desktopOnly-cell">
            <!-- Content/Nested Table -->
        </td>
    </tr>
    <!--[if !mso]><\!-->
    <tr>
        <td class="mobileOnly-cell">
            <!-- Content/Nested Table -->
        </td>
    </tr>
    <!-- <![endif]-->
```


# Those thin divider lines that arent full width
```
<tr>
    <td align="center" style="background-color: #fff;padding-top:40px;">
        <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="178" style="margin: auto;">
            <tr>
                <td style="font-size:0;line-height:0;width: 100%;border-bottom: 1px solid black;">
                    &nbsp;
                </td>
            </tr>
        </table>
    </td>
</tr>
```


# Bold Webfont in Arial
```
<h1 style="margin: 0 0 10px; font-family: 'Arial Black', 'Arial', sans-serif; font-weight: 900; font-size: 25px; line-height: 30px; color: #333333; ">This is a Super-Bold Headline</h1>
```