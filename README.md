# postmessageAPITest

## Problem
In Chrome, everything seems to be OK.
In Edge the parent does not receive any messages from the Zill popup.

## Usage
Open the test.html in Edge.
Click on 'Open popup' and on 'Send message'.
The message will be shown in the popup, and it will send a message back.
That reply will be visible in the parent.

Click on 'Open zill'.
It will open Zill in a new tab.
In Chrome you will see in the parent the reply from zill (on screen and in the console).
In Edge the parent does not receive a message from zill.
