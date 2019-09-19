[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bjrnfrdnnd/panel-test.git/master?filepath=dnmr_abi.ipynb)


## deploy on heroku button

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

(this uses `app.json`)

## Click the "launch binder app" badge above to launch the application. 
Be patient as the server image is launched :)

# panel-test

![DNMR AB quartet](DNMR-AB.png)


Testing the use of Panel to create apps for simulating nuclear magnetic 
resonance (NMR) simulations.

Currently the demo has one simulation: a dynamic NMR (DNMR) simulation for two
coupled spin-1/2 nuclei (an AB quartet at the slow-exchange limit).

* **va** and **vb** are the frequencies of the two nuclei (in the absence of 
exchange
 and coupling) in Hz
* **J** is the coupling constant in Hz
* **k** is the rate constant for the exchange (in s<sup>-1</sup>)
* **w** is the peak width at half height (at the slow-exchange limit)
