# Autofill Phishing

# Try it yourself!
https://autofill-danger.vercel.app


## Overview

This repo demonstrates an autofill phishing vulnerability in modern day browsers. It highlights how even the latest browsers might be susceptible to this type of basic attack, which has been around for around 8 years.

## Why This Attack Works

Many modern day web browsers offer autofill features to enhance user convenience by automatically filling in form fields with saved data. However, this convenience can be exploited due to:

-  Attackers can hide input fields on a webpage, which get autofilled without the users knowledge.
-  Users often trust autofill to only populate visible fields, unaware that hidden fields can also be filled.

## How This Attack Works

This attack exploits the autofill feature of browsers. Here are the key steps involved:

1. **Crafted Web Form**: The attacker creates a web form with visible and hidden input fields.
2. **User Interaction**: The user visits the malicious website and interacts with the visible form fields.
3. **Autofill Trigger**: The browser's autofill feature automatically populates both visible and hidden fields with saved user data.
4. **Extraction**: The hidden fields capture sensitive information without the user’s knowledge, which is then sent to the attacker.
