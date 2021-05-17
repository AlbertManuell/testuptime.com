# testuptime.com
Free Website/Server Uptime Monitoring &amp; Status Pages
Easy & reliable uptime and performance monitoring solution, with highly customizable and fast status pages.

* [TestUptime.com](https://testuptime.com) - Free Forever



    Everything on this website is FREE; you don't need to pay for anything.
    You will find some "Premium"/"Paid" features from others free here.
    The website and features are continuously developed, and we listen to your needs.
    This is a project made from passion; we are not looking for any kind of return.
    Every feature available on this website was made per our needs. After a while, we thought it will be nice to share it with others also.



Monitors: You can monitor your websites or servers through monitors, where you can select the PING mode:

    HTTPs - Ideal for monitoring websites, APIs, and web services.
    ICMP - Ideal for monitoring a server.
    Host/Port - Ideal for monitoring databases, POP, or SMTP servers.

Here you can personalize what type of notifications you want to get once something is happening:

    Receive an email notification once something happens.
    Receive webhook notifications when your monitor goes down / back up to your specified webhook URL. (custom)
    Receive Slack notifications when your monitor goes down / back up to your specified Slack channel via webhooks. Get Slack webhook URL.

Personalize the check interval and the request timeouts:

    Check interval - starting from 1 minute.
    Request timeout - starting from 1 second.

Custom Requests (for developers):

    You can send your own custom body, form data format or JSON.
    Custom Responses.

Heartbeats:

    Keep track of your cronjobs and make sure they are actually running.
    Send GET or POST request to a unique URL generated in your account each time your cronjob runs.(for developers)

StatusPages

Be transparent with your visitors and display your monitor's stats nicely.

    Create a custom URL for your status page (https://testuptime.com/s/ + your name)
    Choose if you want to have Search Engine visibility - let google crawl or not on this page.
    WHITE-LABEL - you can add your logo and your social media accounts on this page + your email.
    You have the possibility to add your own design by adding custom CSS or JavaScript.
    Statistics - you will have access to statistics on how many people have visited that page, refers, browsers, etc.
    QR Code - you can create and display a QR code on your status page.
    Reports - you will be able to create and export Reports in a PDF Report.
    Filtred statistics - you can filter by day/week/month/year/custom interval - to see your desired statistics about your hosts.

Projects

If you run multiple websites/servers, you have the possibility of creating project folders for each one.

API Documentation

If you want more, here you have the API Documentation.


How do I create a monitor?

Once you have created an account,you will be redirected to your Dashboard, where you will have the option "Create Monitor".

You can choose from multiple options of monitor types:

    HTTP(s)
    Ping
    Port

Creating a monitor is as simple as adding a URL or IP address. For the Ping Monitor, you need only the correct IP (or Host). Additionally, for the Port Monitor, you can set a URL and port, too.

What is a heartbeat monitor?

It works in an opposite way compared to other monitoring types. Heartbeat Monitor is the best solution to monitor endpoints inside an intranet (but connected to the internet). It’s also suitable for regular/cron jobs your website/app may be performing.

We will provide a unique URL for each heartbeat monitor to which your device/server/computer will be sending requests. Once it doesn’t arrive, you will receive a downtime alert.

How to create an SMS alert?

We are working on this system implementation, we will send an email when this feature is live.

How can I export a Report?

Once you are logged in, open any monitor or status page, and you will have two export options:

    PDF
    CSV /JSON


