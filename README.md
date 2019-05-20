# Live Demo
http://wvprogramming.com/transcribe/parser.html

# awsTranscribeHTMLFormatter
Using AWS Transcribe service, take the JSON output and output HTML into a nice conversational format for easy posting to a blog.

* Requires jQuery
* Optional inline Edit (highly recommend)
* place output from AWS Transcribe into ajax/asrOutput.json

# HOW TO USE:
You will need to know how many speakers you have in the orginal audio file to add to the speakerNames variable.

Added the jQuery Inline/In-Place Edit Plugin, which can be found here. https://github.com/caphun/jquery.inlineedit

Example of AWS Transcribe output:
https://docs.aws.amazon.com/transcribe/latest/dg/how-it-works.html#output

getJSON example can be found here:
http://api.jquery.com/jQuery.getJSON/
