# "WebVR and Samsung" - WebVR/AR Meetup London, April 2017

My slides for [WebVR/AR Meetup London, April 2017](https://www.meetup.com/Web-VR-AR/events/238266181/). 

## To view the slides

Check them out at: [poshaughnessy.github.io/webvr-london-apr-2017/](https://poshaughnessy.github.io/webvr-london-apr-2017/)

Use arrow keys or swipe to move left/right.


## To run locally

```
npm install
npm start
```


## To use the Bluetooth remote control

Load up the Remote page on a Web Bluetooth supporting browser, e.g. Chrome for Android, on the device you want to use 
as a presentation remote: http://localhost:9000/remote.html

Press Connect and (as long as you have the Node server running and Bluetooth enabled on both devices) you should see
a device option called 'Remote'. Select that, wait til it says Connected, then you can use the buttons to send 
commands!


## To deploy (for Peter's reference)

```
./deploy.sh
```
