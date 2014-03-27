Medico
======

Short Description
-----------------

A small piece of Annoy-Ware that is designed to annoy the user until they have taken their medication.

Project Goal
------------

Fulfil the final wish of a close friend of mine who passed away, at the age of 32, shortly before Christmas 2013. He'd lamented on the fact that there weren't any apps that could help him to take all of his prescribes medications on time.

We'd discussed the idea in great detail during (what would become) his final summer. He medication regimen was quite strict during the final year of his life, and he would follow this procedure everyday:

* Take his first medication shortly after waking
* Create a series of alarms on his mobile devices, one for each the doses of his medication
* Nap until it was time to take his medication (the alarm would wake him)

All of his medication was time based, so he would have to set each of the alarms at the beginning of the day - MANUALLY. What he wanted was an app that would set all of the alarms for him when he took his first dose in the morning. Should his miss or delay a dose, the later alarms would be put on hold until he took his allotted dose, then all alarms based after that one would cascade AUTOMATICALLY.

I will consider this repository 100% successful if only one person is helped by it. Also, should this code base help convince developers to create a similar application, then this will be taken as 100% success for this repository.

Technology
----------

Initially, the application will be written using C# for the Windows platform. This will be the proof of concept phase. Once passed the proof of concept stage, then the application will be ported to Android (using Java). If the application proves useful, then the application will be ported Windows Mobile and iOS.

Use of this Repository
----------------------

Initially the contents of this repository will be released with a LGPL V2 license (please see the license.md file in the root of the main branch for more details). Once the project is passed the planning and proof of concept stage the application will be ported to other platforms, once this happens the code base may be released with a different license. It is hard to say at this juncture as to what will happen.

Each of the different versions of the main application will, likely, have different licenses applied. The applicable license can be found in the license.md file found in the directory containing the code base for that platform (i.e WindowsDesktop for the Windows Desktop version of the application).