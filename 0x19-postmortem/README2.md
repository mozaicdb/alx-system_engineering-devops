Postmortem Summary:
Duration: The outage wreaked havoc from 11:00 AM to 12:30 PM (WAT+1), giving us more stress than Monday morning traffic.
Impact: Our login service took an unexpected coffee break, leaving 70% of our users locked out like forgotten keys.

Root Cause
Picture this: a misconfigured database connection pool, the proverbial wrench in the gears, causing chaos akin to trying to fit a square peg into a round hole.

Timeline:
11:00 AM (WAT+1): Monitoring alerts sounded like a banshee's wail, signaling the start of our unexpected adventure.
11:05 AM: Cue the heroic engineers, diving into action faster than a hungry seagull at a beach picnic.
11:10 AM: Our troubleshooters combed through server logs like detectives in search of a clue.
11:20 AM: Metrics were scrutinized with more intensity than a contestant on a baking show facing Paul Hollywood's critique.
11:30 AM: We briefly considered blaming the office ghost for the outage before refocusing on the task at hand.
11:45 AM: The cavalry arrived in the form of senior database gurus and system architects, ready to slay the misconfiguration dragon.
12:00 PM: The eureka moment! The mischievous misconfiguration was finally unmasked, feeling more relieved than finding your lost keys in the couch cushions.
12:15 PM: With the speed of a ninja, the configuration settings were adjusted, rescuing our login service from the depths of downtime.
12:30 PM: The triumphant return of our login service, greeted with cheers and high-fives all around!

Root Cause and Resolution:
The misconfigured database connection pool played the role of the villain in our outage drama. However, our intrepid team defeated it by reconfiguring the settings, restoring peace and harmony to our web application like a knight vanquishing a troublesome dragon.

Corrective and Preventative Measures:
Improvements/Fixes: 
  We'll be implementing automated monitoring to keep an eagle eye on our database connection pool health, ensuring it behaves better than a well-trained puppy.
  Regular audits of our database configurations will be conducted, preventing future misconfigurations from sneaking in like a stealthy cat burglar.
Tasks to Address the Issue:
  Apply patches to our database connection pool settings, ensuring they're as smooth and efficient as a freshly paved highway.
   Introduce automated alerts for any unusual database connection behavior, acting as our trusty watchdog against future shenanigans.
   Schedule periodic reviews of our database configurations to keep them in line, like a teacher monitoring rowdy students during recess.

By adding a sprinkle of humor and a dash of creativity, we hope this post-mortem not only informs but also entertains, leaving you chuckling and nodding in agreement as you join us on our rollercoaster ride through the world of IT mishaps and triumphs.


