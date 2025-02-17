This file is pretty simple. It makes an application in tkinter that pulls data from USDA NASS QuickStats. 
The data is formatted in a manner consistent with how EPA's Office of Pesticide Programs usually formats their data pulls.

It allows the user to group states into regions, which is important for considering geographic commonalities in pesticide usage.
It also allows the user to pull data for each state.

This is much quicker than pulling the data directly from NASS.

The only thing a user needs to run this, beyond having the correct stuff pip-installed in Python, is a USDA NASS API key.
