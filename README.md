# Measuring Web Page Load Times using JMeter

In JMeter, listeners are used to output the results of a load test. There are a variety of listeners available, and the other listeners can be added by installing plugins. We will use the Table because it is easy to read.

Select Thread Group, then Right-click it
Mouse over Add >
Mouse over Listener >
Click on View Results in Table
You may also type in a value for Filename to output the results to a CSV file.

Run the Basic Test Plan Now that we have our basic test plan set up, let's run it and see the results.

First, save the test plan by clicking on File then Save, then specify your desired file name.

Then select on View Results in Table in the left pane, then click Run from the main menu then click Start (or just click the green Start arrow below the main menu).

You should see the test results in the table as the test is run.

enter image description here

Interpreting the Results

You will probably see that the Status of all the requests is "Success" (indicated by a green triangle with a checkmark in it). After that, the columns that you are probably most interest in are the Sample Time (ms) and Latency (not displayed in example) columns.

Latency: The number of milliseconds that elapsed between when JMeter sent the request and when an initial response was received
Sample Time: The number of milliseconds that the server took to fully serve the request (response + latency)

FYI , I have uploaded two videos in dropbox related to user manual for capturing page load time for website application by using Jmeter Tool.

- https://www.dropbox.com/s/tla4b3wpbqmmist/Page%20load%20Time%20Testing%20Part%20-%201.g13688.mp4?dl=0  - Part - 1
- https://www.dropbox.com/s/76r9sz7qduwsaxh/Page%20Load%20Time%20Testing%20Part%20-%202.Uh6424.mp4?dl=0 - Part - 2
