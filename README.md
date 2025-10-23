# watchbunny-public
**_email me at cruel.petrichor@protonmail.com if you want to know what this is in further detail or discuss access to it if / when it exits indev and is a functional product. If it never leaves development and is eventually dropped / archived I will publicly release the latest dev sourcecode to this public repo irrespective of other's opinions._**

WatchBunny is a detailed game analytics mod that logs most things that a developer may want such as sent and recieved RPCs along with relevant data to them such as actor numbers, related player id's and names, room sent in, and Photon.Pun.MessageInfo. Rooms joined and left, playsession statistics (Tags, rpcs, etc.) and resource usage (mem, cpu, etc.)

and other miscellaneous things including but not limited to: injected / post-load assemblies, game info itself (unity version, location, data path, etc.) all loaded plugins, tag events, and detailed timestamp logging.

its planned to have a customizable data policy at some point (data collection of suspiscious rpc events, and general playsession statistics like total tags, total room joins, total playtime, when you played, etc.) no PII would be collected by this whether you allow it or not. uploading playsession data isn't even added yet, so this is a large 'maybe' rather than a definite plan.

optional export of general playsession statistics to .csv format so you can view long term data easier is also planned.
