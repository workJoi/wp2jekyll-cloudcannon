---
layout: post
title: iPAD MIDI Control for LiveText
date: 2015-10-16 00:00
author: jjohnston
comments: true
categories: [automation, LiveText, LiveText Tips, MIDI, rptMIDI, Tip, TouchOSC, TriCaster, TriCaster Tips, Video Production Tips]
---
<em><strong>by Kane Peterson, NewTek Workflow Engineer
</strong></em>

Wouldn’t it be great if you could control LiveText from your iPad like you can with your TriCaster? With the correct combination of software, it’s possible!

<strong>Requirements:</strong>
<ul>
	<li>LiveText v2.x</li>
	<li>rtpMIDI: download it from this link.<a href="http://www.tobias-erichsen.de/software/rtpmidi.html">http://www.tobias-erichsen.de/software/rtpmidi.html</a></li>
	<li>TouchOSC, download from the iTunes store.</li>
	<li>Bome’s MIDI Translator Classic: <a href="http://www.bome.com/products/miditranslator/overview/classic">http://www.bome.com/products/miditranslator/overview/classic</a></li>
	<li>LiveTextMIDIControl ZIP file – contains iPad interface file for TouchOSC and shortcut configuration file for Bome’s MIDI Translator Classic: <a href="http://tips.newtek.com/wp-content/uploads/2015/08/LiveTextMIDIControl.zip">LiveTextMIDIControl</a></li>
</ul>
<strong>Software Configuration:</strong>

<img class="alignleft wp-image-1489" src="http://blog.uk.newtek.com/wp-content/uploads/2015/10/LiveText_MIDI_figure001.jpg" alt="LiveText_MIDI_figure001" width="412" height="263" />

Install rtpMIDI on the computer that will be running LiveText.

Open the rtpMIDI configuration window and click the ‘+’ under My Sessions.

Activate the checkmark next to your computer name.

In the directory, you should see the name of your iPad displayed. Select it and press the connect button.

Close the rtpMIDI configuration screen.

Once you have rtpMIDI running, install the Bome’s Translator Classic software on the same computer that will be running LiveText.

<img class="alignright wp-image-1490" src="http://blog.uk.newtek.com/wp-content/uploads/2015/10/LiveText_MIDI_figure002.jpg" alt="LiveText_MIDI_figure002" width="250" height="104" />

From the Bome’s software ‘Midi In’ menu, select the rtpMIDI name from the list. This is the same name that you will see in the ‘My Sessions’ panel in rtpMIDI.

Now in Bome’s MIDI Translator, click on the Files menu and select Open. Included in the LiveTextMIDIControl ZIP file is the configuration file that will program MIDI Translator will the correct keyboard shortcuts for LiveText. Open this file and you will see the LiveText shortcuts displayed.

<img class="aligncenter size-full wp-image-1491" src="http://blog.uk.newtek.com/wp-content/uploads/2015/10/LiveText_MIDI_figure003.jpg" alt="LiveText_MIDI_figure003" width="782" height="581" />

Once you have imported the shortcuts, you can minimize the Bome’s MIDI Translator window. It will still be running the background.

Download and install TouchOSC Editor (<a href="http://www.hexler.net/">www.hexler.net</a>) which will allow you to install the TouchOSC interface supplied in the LiveTextMIDIControl ZIP file onto your iPad. Once you have that on your iPad, you are ready to go. Start up LiveText and when you press the button on the iPad, LiveText should respond. Here is what the buttons do.

<strong>
<img class="alignright wp-image-1492" src="http://blog.uk.newtek.com/wp-content/uploads/2015/10/LiveText_MIDI_figure004_proc.jpg" alt="LiveText_MIDI_figure004_proc" width="300" height="225" />Load Previous/Next Page</strong>: These buttons will load a page into the editing window of LiveText. They will not be displayed on output.

<strong>Send Page to Live</strong>: This button will put the page currently loaded in the editor window into the live output.

<strong>Send Previous/Next Page</strong>: These buttons will load a page into the live output window. They will not load the page into the editor window.

<strong>Motion Page Play/Pause/Stop</strong>: These buttons will control playback of pages that have a roll/crawl motion applied to them. Make sure you press STOP when you are finished or you will not be able to load a new page into the live output.

<strong>DSK</strong>: These buttons are designed to control the Down Stream Keyers in your TriCaster system. They will work with the macros found in the ‘iPad MIDI Control for TriCaster’ blog entry.

<img class="aligncenter size-full wp-image-1493" src="http://blog.uk.newtek.com/wp-content/uploads/2015/10/LiveTextUI_iPAD_MIDI_inset_005_FBClean.jpg" alt="LiveTextUI_iPAD_MIDI_inset_005_FBClean" width="1154" height="619" />

<strong>More tips and tutorials by Kane Peterson:</strong>
<ul>
	<li><strong><a href="http://tips.newtek.com/midi-control-for-tricaster-or-3play-using-windows/" target="_blank">MIDI Control for TriCaster or 3Play Using Windows</a></strong></li>
	<li><strong><a href="http://tips.newtek.com/ipad-midi-control-for-tricaster/" target="_blank">iPad MIDI Control for TriCaster</a></strong></li>
	<li><strong><a href="http://tips.newtek.com/3play-double-punch-tagging-system/" target="_blank">3Play: iPad Double Punch Tagging System</a></strong></li>
	<li><strong><a href="http://tips.newtek.com/wireless-tricaster-control-with-touchosc/" target="_blank">Wireless TriCaster Control with TouchOSC</a></strong></li>
	<li><strong><a href="http://tips.newtek.com/how-to-input-network-video-sources-on-a-tricaster/" target="_blank">How To Input Network Video Sources on a TriCaster</a></strong></li>
</ul>
<strong>Learn more about <a href="http://www.newtek.com/products/tricaster-software/tricaster-livetext.html" target="_blank">LiveText</a></strong>

<strong>Check out our white paper: <a href="http://pages.newtek.com/How-to-Live-Stream-Video.html" target="_blank">How to Stream Like a Professional</a></strong>
