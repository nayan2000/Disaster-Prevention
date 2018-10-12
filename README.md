
I know you are already fed up reading ideas of many groups planning to work on minimising the damage due to these natural disasters or helping get relief funds from different parts of the world. But wait, the motive of this hackathon was to "PREDICT" disasters, not their after effects. So, here we present a unique idea which would actually go in hand with the actual motto of this hackathon.

Let's begin to discuss on an idea which if executed properly with a highly motivated and talented team can do wonders and help revolutionalise the present scenario of Disaster Prediction and hence Prevention.

<h4 style="color:blue">Aim: To predict an earthquake and take suitable measures if detected one.</h6>

What's our plan?
In today's time, everybody has a smartphone. Right? And most of the smartphones today have inbuilt accelerometer sensors in them which can detect nearby vibrations along with many other physical parameters associated with a device's physical location as well as alignment.

We all know, Earthquakes are associated with seismic waves. Before an earthquake, the core of earthquake will produce some omni-directional disturbances which further produce vibrations, which we humans are incapable of detecting but can be detected with some modern sensors. So this is where the accelerometers in our mobile devices come to our rescue.

These Accelerometers can detect these vibrations, though they are minute. But when we receive these minute vibrations from many devices close to a particular area, this could probably be the sign of an earthquake(How? Keep Reading). Henceforth, if detected, we can notify the disaster management agencies, media houses and people nearby to that location.
I know this sounds vague, but hold on.

<h6 style="color:green">-&gt; A brief description</h6>
We have a network of mobile devices through this product(could probably be an app). Now, if we receive vibrations from many mobiles in a certain region, this means there are some common disturbances/vibrations existing in that area.
Here we get this data, have our hosted Machine Learning Models incorporated with AI based algorithms, we send our raw data to them as input, have it processed and it would conclude whether these vibrations could be due to an earthquake or not.

<h4 style="color:blue">############ Some Technical Details ###########</h6>

The accelerometer will show deviations always due to the constant disturbances from external sources. (As in, random using of device, the air flow rates, air blows due to fans, ACs, sound vibrations, travelling, etc.) In the first phase of the app(could be the first week of release when we have some users), we approximate the disturbances through these sources by our ML models. This would be based on principle of averaging out the disturbances(as they are completely random). Now we have a base range of disturbances which we interpret as normal. Now, when we receive fluctuations in vibrations upto certain levels from many devices, this would lead to a sudden deviation from the normal range in the region close to the core of earthquake i.e. source of these vibrations. The extent of change is an important parameter over here.
For these vibrations to be due to an earthquake, this change has to be in particular range. We send this change % to our AI, ML Models. We will use GeoLocation APIs to get current windspeed, etc at the place in concern. According to the windspeed, we define this normal range.

Fact: The change in fluctuations in the vibrations due to an earthquake would be greater than a lower value(which would incorporate the vibration fluctuations due to local reasons). So, if that % change is greater than this lower value, we would sense a possibility of an earthquake. And on the basis of this increase, we will identify the magnitude of the disturbances and henceforth, decide the range of people nearby core to be alerted based on the distance of the location from the core.

<h4 style="color:red">## Important Note:</h6>

I hope you realise that in such a short time, that too near our midsems, we have presented a raw but relevant and unique idea.
We are already working on covering some more test cases, and have a bunch of ideas which when incorporated here would make this highly close to real world usage.
So, if given a chance to work on this, maybe this idea can actually change the world.
Thanks for reading.

<h4 style="color:blue">############# Appendix #############</h6>

We browsed the internet for some technologies that will be used in our actual implementation of the above idea.

-> An accelerometer is a sensor that measures the dynamic acceleration of a physical device as a voltage. Accelerometers are full-contact transducers typically mounted directly on high-frequency elements, such as rolling-element bearings, gearboxes, or spinning blades. These versatile sensors can also be used in shock measurements (explosions and failure tests) and slower, low-frequency vibration measurements. The benefits of an accelerometer include linearity over a wide frequency range and a large dynamic range. Read more here: http://www.ni.com/white-paper/3807/en/

-> Big data is a term used to refer to the study and applications of data sets that are too complex for traditional data-processing application software to adequately deal with. Big data challenges include capturing data, data storage, data analysis, search, sharing, transfer, visualization, querying, updating, information privacy and data source.
Read more here: https://en.wikipedia.org/wiki/Big_data

-> Seismology is the study of earthquakes and seismic waves that move through and around the earth. A seismologist is a scientist who studies earthquakes and seismic waves.
Seismic waves are the waves of energy caused by the sudden breaking of rock within the earth or an explosion. They are the energy that travels through the earth and is recorded on seismographs.
Read more here: http://www.geo.mtu.edu/UPSeis/waves.html

P.S: Ofcourse, this list is very brief and we will add a lot many _jargons_ when in the actual phase of working.

Team Members:
Nayan Khanna (Sophomore pursuing Integrated B.E. Computer Science and Mathematics at BITS Pilani)

LinkedIn: https://linkedin.com/in/nayankhanna

Keshav Sethi (Sophomore pursuing Integrated B.E. Electrical and Electronics and Economics at BITS Pilani)

LinkedIn: https://www.linkedin.com/in/keshav-sethi-b1788a157

