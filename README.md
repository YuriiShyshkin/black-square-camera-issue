# Camera Issue Sample

This sample application shows the camera issue.

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/YuriiShyshkin/black-square-camera-issue?file=js/app.js)

## Preconditions:

Enter your credentials in `config.js`.

## Steps to reproduce:

1. Generate a token for the Host.
2. Launch the app from the desktop Chrome browser, enter the generated token and click the "Submit Token" button.
3. On the confirmation modal click the "Yes" button.
4. Generate a token for the Participant.
5. Launch the app from the desktop Chrome browser, enter the generated token and click the "Submit Token" button.
6. On the confirmation modal click the "Yes" button.
7. As the Host from the desktop Chrome browser click the "Enable Video" button.

Actual Result: The Participant sees a black square before seeing the Host camera.

Expected Result: The Participant should not see a black square before seeing the Host camera.

Note:
 1. Try several times to enable/disable Host camera to reproduce the issue.
 2. The same issue occurs if the host enables the camera and a participant joins the session.