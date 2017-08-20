# Tensorflow-Object-Detector-with-website
Website with image recognition from camera

To work with object detector you must:
1. Get certificate files and add to tornado web server in mainWorker.py file
   - Path to folder - data_dir
   - Then add names for .crt and .key files
2. In file server.js:
   - Add ca-bundle, key and crt files
3. in file receiver.js:
   - Add your wss enpoint address (for example -  wss://example.com:443)
--------

<a href="https://adexin.com/contact-us/">Contact us</a> if you have any questions. Use our <a href="https://adexin.com/services/machine-learning-consulting/">Machine learning development services</a>.
