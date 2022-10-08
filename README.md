# time-whos-talking
A simple HTML / JS solution that helps people track the talkers during meetings.

## Introduction
Well, here's the context. I was observing in a meeting one day and wanted to keep track of how long individuals are talking. Looked up online for debate timers, Zoom features, but nothing would do the job. I either needed to pay more for extra people in the debate timers, or else I needed to be an admin *and* recording the session in Zoom (and of course, why should we have different tools for different collaboration software?).

So I spent an hour hacking some Javascript, wrapped it up in some ugly HTML, but hey - it's FREE and it does the job!.

## How to use
1. Open the MeetingTimer.html in your browser
2. In the text bot, write down the name of the participants in a comma separated fashion (e.g. Matthew, John, Paul)
3. You will be shown buttons for all participants (e.g. [Matthew] [John] [Paul]) as well as three other buttons: one for Silence (because sometimes it happens), End Meeting, and Print Log.
4. What you need to do now is that any time anyone is talking, just press the button displaying their name. Whenever there's silence, press the Silence button. When the meeting ends, press the End Meeting button.
5. Press the Print Log button to view the log in a CSV format, which you can copy to a spreadsheet solution for further manipulation. (*hint*: if you're a geek, open up the Browser JS Console...)

## Do you want to try it online?
Sure - here's a [link](https://rawcdn.githack.com/maqqju/time-whos-talking/030c1d7d12f95c24a3e7b40bb2ea2b9566711fa3/MeetingTimer.html).

## Feel like contributing?
Be my guest.
