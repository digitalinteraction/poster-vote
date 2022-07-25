# Device Setup

This page contains information on setting up new PosterVote devices.

## Instructions

1. Create your poster on [postervote.openlab.ncl.ac.uk](https://postervote.openlab.ncl.ac.uk)
2. Get your PosterVote device and battery
3. Tentatively put the battery in. You can hook in one side and press down (without clicking it in) which starts the boot process
5. You’ll see lights on the buttons “loading”, this indicates the boot process has begun
6. While booting hold the first 3 buttons (from the battery going away) and release them after the poster stops beeping
7. Wait until all the flashing lights have stopped
8. Push the battery in fully
9. Register the poster with the website (the instructions on the back of the generated PDF)

## Notes

You don't have to use the generated PDF, but creating one sets up the infrastructure to call-in for votes 
and it has the poster-device pairing information on the back.
You can generate one then use your own poster design.

## Reuse

You can use a PosterVote device for multiple deployments.
To reuse a device, generate a new poster on the website and repeat the registration with the device.
Now, any votes that are called in for that device will be allocated to the new poster instead
and the new poster's counts will start at 0.

> When you register a device with a poster, it remembers the votes stored on the device and effectively counts up from there.
> So the new poster's vote will start from zero.

## Known issues

* The numbers on the poster creation form's options are the reverse of the numbers on the physical device.
  This issue is being tracked here: https://github.com/digitalinteraction/poster-vote-frontend/issues/1
* The PDF generation takes a while to load, please be patient it can take up to 30 seconds. Issue:
  https://github.com/digitalinteraction/poster-vote-backend/issues/2
* The registration wording is slightly incorrect, you need to hold the two buttons until it beeps then release,
  https://github.com/digitalinteraction/poster-vote-backend/issues/3
