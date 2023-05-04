Download Link: https://assignmentchef.com/product/solved-cs585-hw1-conceptual-entity-relational-er-diagram
<br>
In this assignment, you need to create a <strong>conceptual Entity-Relational (ER) diagram</strong>, to model the scenario described below; note that your design is not going to be at a logical level, ie. you don’t have to worry about how to represent your design using relational tables (including bridges) or other data models.

<a href="http://bytes.usc.edu/cs585/s20_db0ds1ml2agi/hw/HW1/pics/DropboxSubmission.jpg">Please submit your work as a single image file in .jpg or .png form that shows the entire diagram, via D2L Dropbox (pics/DropboxSubmission.jpg) (not via Blackboard). ALSO include a README.txt that contains any design choices </a>you want to highlight, and/or assumptions you made [if the ER diagram were ‘code’, this would be ‘comments’]. You can create the ER diagram using any software of your choice, including:

yEd (<a href="https://www.yworks.com/products/yed">http://www.yworks.com/products/yed (http://www.yworks.com/products/yed)</a>) draw.io (browser-based) Lucidchart (browser-based)

Vertabelo (also entirely online)

DIA

Project Mogwai (<a href="https://github.com/mirkosertic/MogwaiERDesignerNG">https://github.com/mirkosertic/MogwaiERDesignerNG (https://github.com/mirkosertic/MogwaiERDesignerNG)</a><a href="https://github.com/mirkosertic/MogwaiERDesignerNG">)</a>

<a href="https://highered.mheducation.com/sites/0072942207/student_view0/e_r_assistant.html">E/R Assistant (Windows only: https://highered.mheducation.com/sites/0072942207/student_view0/e_r_assistant.html (https://highered.mheducation.com/sites/0072942207/student_view0/e_r_assistant.html)</a><a href="https://highered.mheducation.com/sites/0072942207/student_view0/e_r_assistant.html">) </a>Visio

…

After constructing the ER diagram, save, or take a screengrab snapshot, submit it [as a .jpg or .png image file].

Note that you can even draw your diagram <strong>legibly</strong> on paper and take a photo of it and submit that – but having said that, I’d encourage you to use a diagramming tool, that will make your result look professional, and have you follow industry practice.

You need to use Crow’s Foot Notation for the ER diagram. For each relationship, indicate the cardinality (minimum <a href="http://bytes.usc.edu/cs585/s20_db0ds1ml2agi/hw/HW1/pics/ERD_Relationship_Symbols_Quick_Reference-1.png">and maximum participation), also via Crow’s Foot symbols – use this</a>

<a href="http://bytes.usc.edu/cs585/s20_db0ds1ml2agi/hw/HW1/pics/ERD_Relationship_Symbols_Quick_Reference-1.png">(pics/ERD_Relationship_Symbols_Quick_Reference-1.png) infograph</a>ic (from www.vivekmchawla.com/) as a guide [you don’t need to denote cardinality as (1,1) etc., instead, you would use the notation shown in the infographic, ie. use symbols such as |O and ||].

How much detail should your diagram contain? Use <a href="http://bytes.usc.edu/cs585/s20_db0ds1ml2agi/hw/HW1/pics/Sample_ER_Diagram.jpg">this (pics/Sample_ER_Diagram.jpg)</a> sample as a guide (eg. you do not need to indicate data types for attributes).

You (a database designer/analyst) have been hired by the owners of a small ‘STEM’ organization that is interested in offering programming courses in their community, during summer vacation [the classes will be aimed towards high school students who will be on summer break].

Rather than offer just “the usual” (Scratch, Java, Python, Ruby…) coding classes, the owners want to make the <a href="https://www.google.com/search?q=microcontroller&amp;rlz=1C1CHBF_enUS723US723&amp;sxsrf=ACYBGNS3HHO-QjCoXCtF0zDz-h29WgDfgw:1568531457864&amp;source=lnms&amp;tbm=isch&amp;sa=X&amp;ved=0ahUKEwiRs_WCo9LkAhWFoJ4KHaKkCIcQ_AUIFCgD&amp;biw=1280&amp;bih=578">classes more fun and engaging – they plan on making the classes be centered around microcontrollers.</a>

<a href="https://www.google.com/search?q=microcontroller&amp;rlz=1C1CHBF_enUS723US723&amp;sxsrf=ACYBGNS3HHO-QjCoXCtF0zDz-h29WgDfgw:1568531457864&amp;source=lnms&amp;tbm=isch&amp;sa=X&amp;ved=0ahUKEwiRs_WCo9LkAhWFoJ4KHaKkCIcQ_AUIFCgD&amp;biw=1280&amp;bih=578">(https://www.google.com/search?q=microcontroller&amp;rlz=1C1CHBF_enUS723US723&amp;sxsrf=ACYBGNS3HHOQjCoXCtF0zDz-</a>

<a href="https://www.google.com/search?q=microcontroller&amp;rlz=1C1CHBF_enUS723US723&amp;sxsrf=ACYBGNS3HHO-QjCoXCtF0zDz-h29WgDfgw:1568531457864&amp;source=lnms&amp;tbm=isch&amp;sa=X&amp;ved=0ahUKEwiRs_WCo9LkAhWFoJ4KHaKkCIcQ_AUIFCgD&amp;biw=1280&amp;bih=578">h29WgDfgw:1568531457864&amp;source=lnms&amp;tbm=isch&amp;sa=X&amp;ved=0ahUKEwiRs_WCo9LkAhWFoJ4KHaKkCIcQ_AUIFC</a>

Students will take coding classes, and also work on hands-on projects (each class or project will last a week, the <a href="https://www.instructables.com/id/Physical-Computing-Scratch-for-Arduino/">entire curriculum will last 6 weeks) that will have them run their code in a microcontroller (eg. like so (https://www.instructables.com/id/Physical-Computing-Scratch-for-Arduino/)</a><a href="https://www.instructables.com/id/Physical-Computing-Scratch-for-Arduino/">).</a>

Below is what the owners have in mind – if their specifications seem incomplete, you are free (expected, in fact) to make relevant assumptions to help create your design [be sure to document them].

<a href="https://processing.org/">Students will sign up for a mix of coding classes, and projects. Coding would be taught using Scratch, Processing</a>

<a href="https://processing.org/">(https://processing.org/), Python, Java and JavaScript. Each project would be based on a microcontroller – Arduino</a>, Raspberry Pi, BeagleBoard or micro:bit. Students pay a single flat fee at the beginning, for the entire curriculum.

bytes.usc.edu/cs585/s20_db0ds1ml2agi/hw/HW1/index.html  1/2 5/11/2020          HW1

Instructors (faculty) would teach a variety of coding classes throughout the day, and also oversee projects when they are not teaching. Each coding class has a textbook. An instructor might specify a textbook for more than one <a href="https://www.amazon.com/Learning-Python-5th-Mark-Lutz/dp/1449355730">class that he/she teaches (eg. the same Python book (https://www.amazon.com/Learning-Python-5th-MarkLutz/dp/1449355730) could be used for Python I and for Python II). A class would have multiple instructors, a</a>nd each instructor could potentially use a different text (their favorite) for the same class (which those multiple instructors would teach).

Instructors would get paid based on hours they teach, and hours they supervise projects (the supervision pays a higher rate); all instructors are paid identical rates.

Projects are done in shared fashion, ie. as a group (typically containing 4 students who all sign up for a common <a href="https://www.raspberrypi.org/magpi-issues/MagPi78.pdf">project, eg. a ‘Building an arcade game using a Raspberry Pi (https://www.raspberrypi.org/magpi-</a>

<a href="https://www.raspberrypi.org/magpi-issues/MagPi78.pdf">issues/MagPi78.pdf)’). Students would sit around large, square, numbered tables (1,2..) assigned to</a> them, to work on projects; at the start of the term, each table would be provided a big plastic storage box containing all the parts for the project the students will work on; at the end of the term, students will return all the parts presumably in good working order, otherwise they would be charged for damaged items.

<a href="https://www.google.com/search?rlz=1C1CHBF_enUS723US723&amp;biw=1280&amp;bih=578&amp;tbm=isch&amp;sxsrf=ACYBGNSd1gSHCe6R4gGyDX7LKIFOKS6WTA%3A1568531853343&amp;sa=1&amp;ei=jeV9XcHKFPGt0PEPmpa8oAs&amp;q=microcontroller+hardware+wheels%2C+motors%2C+sensors%2C+LEDs%2C+switches%2C+enclosures&amp;oq=microcontroller+hardware+wheels%2C+motors%2C+sensors%2C+LEDs%2C+switches%2C+enclosures&amp;gs_l=img.3...18979.23204..24027...0.0..0.81.898.12......0....1..gws-wiz-img.2P_6T4MnL3c&amp;ved=0ahUKEwiBxb-_pNLkAhXxFjQIHRoLD7QQ4dUDCAc&amp;uact=5">Each project would require parts specific to it – a microcontroller, and extra hardware such as wheels, motors, sensors, LEDs, switches, enclosures, etc. (https://www.google.com/search?</a>

<a href="https://www.google.com/search?rlz=1C1CHBF_enUS723US723&amp;biw=1280&amp;bih=578&amp;tbm=isch&amp;sxsrf=ACYBGNSd1gSHCe6R4gGyDX7LKIFOKS6WTA%3A1568531853343&amp;sa=1&amp;ei=jeV9XcHKFPGt0PEPmpa8oAs&amp;q=microcontroller+hardware+wheels%2C+motors%2C+sensors%2C+LEDs%2C+switches%2C+enclosures&amp;oq=microcontroller+hardware+wheels%2C+motors%2C+sensors%2C+LEDs%2C+switches%2C+enclosures&amp;gs_l=img.3...18979.23204..24027...0.0..0.81.898.12......0....1..gws-wiz-img.2P_6T4MnL3c&amp;ved=0ahUKEwiBxb-_pNLkAhXxFjQIHRoLD7QQ4dUDCAc&amp;uact=5">rlz=1C1CHBF_enUS723US723&amp;biw=1280&amp;bih=578&amp;tbm=isch&amp;sxsrf=ACYBGNSd1gSHCe6R4gGyDX7LKIFOKS6WTA%3</a>

<a href="https://www.google.com/search?rlz=1C1CHBF_enUS723US723&amp;biw=1280&amp;bih=578&amp;tbm=isch&amp;sxsrf=ACYBGNSd1gSHCe6R4gGyDX7LKIFOKS6WTA%3A1568531853343&amp;sa=1&amp;ei=jeV9XcHKFPGt0PEPmpa8oAs&amp;q=microcontroller+hardware+wheels%2C+motors%2C+sensors%2C+LEDs%2C+switches%2C+enclosures&amp;oq=microcontroller+hardware+wheels%2C+motors%2C+sensors%2C+LEDs%2C+switches%2C+enclosures&amp;gs_l=img.3...18979.23204..24027...0.0..0.81.898.12......0....1..gws-wiz-img.2P_6T4MnL3c&amp;ved=0ahUKEwiBxb-_pNLkAhXxFjQIHRoLD7QQ4dUDCAc&amp;uact=5">wiz-img.2P_6T4MnL3c&amp;ved=0ahUKEwiBxb-_pNLkAhXxFjQIHRoLD7QQ4dUDCAc&amp;uact=5)</a>

<a href="https://www.sparkfun.com/">The owners of the institution plan to order project parts from several online suppliers (such as SparkFun (https://www.sparkfun.com/)</a><a href="https://www.sparkfun.com/">,</a> <a href="https://www.adafruit.com/">adafruit (https://www.adafruit.com/)</a><a href="https://www.sparkfun.com/"> etc.) – there is expected to be multiple</a> orders placed with multiple vendors, to procure all the items.

There are several rooms that will be available for the classes and projects – students will be provided a schedule that will list where and when these will be.

<a href="https://www.google.com/search?rlz=1C1CHBF_enUS723US723&amp;sxsrf=ACYBGNSmLrAUZlMTge1WTjSqo2MF9B9AWg%3A1568531940255&amp;ei=5OV9XbaQD9HB7gK1j4ToAQ&amp;q=books+about+electronics+and+coding&amp;oq=books+about+electronics+and+coding&amp;gs_l=psy-ab.3...1409.3255..3928...0.2..0.105.616.6j1......0....1..gws-wiz.......0i71j33i10.XKSewr7EkNs&amp;ved=0ahUKEwi2kvjopNLkAhXRoFsKHbUHAR0Q4dUDCAs&amp;uact=5">There is a small library that contains books about electronics, coding (https://www.google.com/search?</a>

<a href="https://www.google.com/search?rlz=1C1CHBF_enUS723US723&amp;sxsrf=ACYBGNSmLrAUZlMTge1WTjSqo2MF9B9AWg%3A1568531940255&amp;ei=5OV9XbaQD9HB7gK1j4ToAQ&amp;q=books+about+electronics+and+coding&amp;oq=books+about+electronics+and+coding&amp;gs_l=psy-ab.3...1409.3255..3928...0.2..0.105.616.6j1......0....1..gws-wiz.......0i71j33i10.XKSewr7EkNs&amp;ved=0ahUKEwi2kvjopNLkAhXRoFsKHbUHAR0Q4dUDCAs&amp;uact=5">rlz=1C1CHBF_enUS723US723&amp;sxsrf=ACYBGNSmLrAUZlMTge1WTjSqo2MF9B9AWg%3A1568531940255&amp;ei=5OV9Xba ab.3…1409.3255..3928…0.2..0.105.616.6j1……0….1..gws-</a>

<a href="https://www.google.com/search?rlz=1C1CHBF_enUS723US723&amp;sxsrf=ACYBGNSmLrAUZlMTge1WTjSqo2MF9B9AWg%3A1568531940255&amp;ei=5OV9XbaQD9HB7gK1j4ToAQ&amp;q=books+about+electronics+and+coding&amp;oq=books+about+electronics+and+coding&amp;gs_l=psy-ab.3...1409.3255..3928...0.2..0.105.616.6j1......0....1..gws-wiz.......0i71j33i10.XKSewr7EkNs&amp;ved=0ahUKEwi2kvjopNLkAhXRoFsKHbUHAR0Q4dUDCAs&amp;uact=5">wiz…….0i71j33i10.XKSewr7EkNs&amp;ved=0ahUKEwi2kvjopNLkAhXRoFsKHbUHAR0Q4dUDCAs&amp;uact=5), etc. A student </a>can check out up to 4 books at a time, which need to be returned in 2 weeks.

At the end of the curriculum, students will be required to rate their instructors, courses, and projects, using a single score for each (one to five stars).