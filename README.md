This script is a Remote Code Execution (RCE) exploit for the storage.cloudsite.thm API used in the TryHackMe room Rabbit Store.
🚀 Overview

The exploit works by:

    Registering a fake user on the API.

    Logging in with that user to obtain a session cookie.

    Exploiting a vulnerable endpoint (/api/fetch_messeges_from_chatbot) that evaluates user input via a Jinja2 injection.
