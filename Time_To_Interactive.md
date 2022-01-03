# Time to interactive (TTI)
 >Time to Interactive (TTI) is the measurement of how long it took from that first request which led to the DNS lookup and SSL connection to when the page is interactive -- interactive being the point in time after the First Contentful Paint when the page responds to user interactions within 50ms. If the main thread is occupied parsing, compiling, and executing JavaScript, it is not available and therefore not able to respond to user interactions in a timely (less than 50ms) fashion.

Time to Interactive (TTI) is a non-standardized web performance 'progress' metric defined as the point in time when the last Long Task finished and was followed by 5 seconds of network and main thread inactivity.

TTI, proposed by the Web Incubator Community Group in 2018, is intended to provide a metric that describes when a page or application contains useful content and the main thread is idle and free to respond to user interactions, including having event handlers registered.

