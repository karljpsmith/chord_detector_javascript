# chord_detector_javascript

Karl J. P. Smith
  karljpsmith@gmail.com
  karljpsmith.com
  github.com/karljpsmith
  This html page represents a 'musical lock': to 'open' the lock three 
  people must each sing or hum the three pitches in a C chord, that is 
  C4 (264Hz), E4 (330Hz), and G4 (396Hz). 
  This page works best on a desktop brower, as most mobile browsers are
  very particular about audio autoplay. 
  The page presents three red buttons, each of which corresponds to one
  of the three target pitches. Pressing a button plays an audio file of 
  the respective target pitch (called c4.mp3, e4.mp3, etc.). 
  Also, the page is listening to the microphone. It performs an FFT on the
  raw microphone data, identifies the loudest audio frequencies in the 
  data, and if any of the three notes of interest are present it 
  turns the respective corresponding light green

See it in practice here: https://doctorsparks-201118.appspot.com/chord_detector_standalone/chord_detector.html
