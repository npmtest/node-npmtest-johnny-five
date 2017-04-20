# npmtest-johnny-five

#### basic test coverage for  [johnny-five (v0.10.9)](https://johnny-five.io)  [![npm package](https://img.shields.io/npm/v/npmtest-johnny-five.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-johnny-five) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-johnny-five.svg)](https://travis-ci.org/npmtest/node-npmtest-johnny-five)

#### The JavaScript Robotics and Hardware Programming Framework. Use with: Arduino (all models), Electric Imp, Beagle Bone, Intel Galileo & Edison, Linino One, Pinoccio, pcDuino3, Raspberry Pi, Particle/Spark Core & Photon, Tessel 2, TI Launchpad and more!

[![NPM](https://nodei.co/npm/johnny-five.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/johnny-five)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-johnny-five/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-johnny-five/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-johnny-five/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-johnny-five/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-johnny-five/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-johnny-five/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-johnny-five/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-johnny-five/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-johnny-five/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-johnny-five/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-johnny-five/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-johnny-five/build/test-report.html](https://npmtest.github.io/node-npmtest-johnny-five/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-johnny-five/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-johnny-five/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-johnny-five/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-johnny-five/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-johnny-five/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-johnny-five/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-johnny-five/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-johnny-five/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "johnny-five",
    "description": "The JavaScript Robotics and Hardware Programming Framework. Use with: Arduino (all models), Electric Imp, Beagle Bone, Intel Galileo & Edison, Linino One, Pinoccio, pcDuino3, Raspberry Pi, Particle/Spark Core & Photon, Tessel 2, TI Launchpad and more!",
    "version": "0.10.9",
    "homepage": "https://johnny-five.io",
    "author": {
        "name": "Rick Waldron <waldron.rick@gmail.com>"
    },
    "contributors": [
        "Adam Hyland <protonk@gmail.com>",
        "Andreas Haugstrup Pedersen <haugstrup@podio.com>",
        "Andrew Homeyer <homeyer@gmail.com>",
        "Ben Gillies <bengillies@gmail.com>",
        "Carl Danley <carldanley@gmail.com>",
        "Chris Williams <chris@saferaging.com>",
        "Colin Vernon <colin@littlebits.cc>",
        "Corey Daniels <corey@skookum.com>",
        "FotoVerite <mzbphoto@gmail.com>",
        "Francis Gulotta <wizard@roborooter.com>",
        "Irene Ros <irene@bocoup.com>",
        "Jonathan Beri <jmberi@gmail.com>",
        "Julian Gautier <julian.gautier@alumni.neumont.edu>",
        "Linus Larsson <linus@devshm.net>",
        "Mike Breen <hardbap@gmail.com>",
        "Mike Harsch <mike@harschsystems.com>",
        "Mike Sherov <mike.sherov@gmail.com>",
        "Paul Tagliamonte <paultag@sunlightfoundation.com>",
        "Rahul Ravikumar <rahulrav@a2z.com>",
        "Randall A. Gordon <randall@randallagordon.com>",
        "Rebecca Murphey <rmurphey@gmail.com>",
        "Ryan Neufeld <ryan@neucode.org>",
        "Scott González <scott.gonzalez@gmail.com>",
        "Swift <theycallmeswift@gmail.com>",
        "Travis Thieman <travis.thieman@gmail.com>",
        "Vincent Agnano <vincent.agnano@scopyleft.fr>",
        "Cole <mcg42387@gmail.com>",
        "Divan Visagie <visagiedivan@gmail.com>",
        "Sara Gorecki <sgorecki@gmail.com>",
        "Raquel Velez <rockbot01@gmail.com>",
        "Tim Walker <tim.twalker@gmail.com>",
        "Toby Miller <tmiller@localhost.localhost>",
        "Richard Key <rich@busyrich.com>",
        "Patrick Clark <pat@hellop.at>",
        "Boros Márton <martonboros@gmail.com>",
        "Jeremy Morrell <morrell.jeremy@gmail.com>",
        "Bob Holt <bobholt@gmail.com>",
        "Dwayn Matthies <dwayn.matthies@gmail.com>",
        "AJ Fisher <ajfisher.td@gmail.com>",
        "Julian Duque <julianduquej@gmail.com>",
        "Daan van Berkel <daan.v.berkel.1980@gmail.com>",
        "Oli Evans <oli@zilla.org.uk>",
        "Cory Gackenheimer <cory.gack@gmail.com>",
        "Ray Pierce <ray@digitalpierce.com>",
        "Jonathan Clem <jonathan@jclem.net>",
        "achingbrain <alex@achingbrain.net>",
        "Jeff Albrecht <jeffa@iea-software.com>",
        "Isaac Durazo <isaacdurazo@gmail.com>",
        "Pawel Szymczykowski <makenai@gmail.com>",
        "Alex Crooks <alexcrooks@gmail.com>",
        "Donovan Buck <donovan@donovan.bz>",
        "Taha Hesham <taha@wizylabs.com>",
        "Alfonso de la Osa <fonz@botverse.com>",
        "Donald Averill <donaldaverill@nakedcitybrewing.com",
        "Bryan Hughes <bryan@theoreticalideations.com>",
        "Robert Myers <rmyers@euro-pro.com>",
        "David Resseguie <david@resseguie.com>",
        "Lyza Danger Gardner <lyza@lyza.com>",
        "Adam Magaluk <AdamMagaluK@gmail.com>",
        "Udo Kramer <optikfluffel@gmail.com>",
        "Joseph Weakley <joew@samjoe.com>",
        "Dean McDonnell <mcdonnelldean@outlook.com>",
        "Jonathan Petitcolas <petitcolas.jonathan@gmail.com>",
        "Chinmay Pendharkar <notthetup@gmail.com>",
        "Brian Genisio <BrianGenisio@Gmail.com>",
        "Anna Gerber <anna.m.gerber@gmail.com>",
        "Derek Wheelden <derek.wheelden@gmail.com>",
        "Sean Hussey <sean@seanhussey.com>",
        "ralphtheninja <ralphtheninja@riseup.net>",
        "SotirisValogiannis <omiloparmenos@gmail.com>",
        "Sue Lockwood <deathbearbrown@gmail.com>",
        "Henri Cavalcante <contato@henrimichel.com.br>",
        "Dany Shaanan <danyshaanan@gmail.com>",
        "Rachel Hazes <>",
        "DeShawn Williams <deshawn.b.williams@gmail.com>",
        "Michał <bartmichu@gmail.com>",
        "Steve Kinney <hello@stevekinney.net>",
        "H. Phil Duby <philduby@phriendly.net>",
        "Vincent Rubiolo <vincent.libre@cryostase.eu>",
        "Jory Burson <jory@bocoup.com>",
        "Corey Frang <gnarf@gnarf.net>",
        "TRAHOMOTO <trahomoto@i.ua>",
        "Don McCurdy <don.r.mccurdy@gmail.com>",
        "Marcus Wittig <WittigMarcus@gmail.com>",
        "KatieK <KatieK2@users.noreply.github.com>",
        "Iryna Shestak <shestak.irina@gmail.com>",
        "Nathan Loding <nathan@nloding.com>",
        "Eric Lewis <eric.andrew.lewis@gmail.com>",
        "Prayag Verma <prayag.verma@gmail.com>",
        "Stefan Hüsges <Tronsha@gmx.de>",
        "Jean-Philippe Côté <jp@cote.cc>",
        "byronhulcher <byronhulcher@gmail.com>",
        "John Lennard <john@yakmoo.se>",
        "Dario Diaz <darioo.diaz1@gmail.com>",
        "Kimio Kosaka <kim@dhcp209.kosmac.or.jp>",
        "Ashley Williams <ashley666ashley@gmail.com>",
        "kilida <kilidapatch@gmail.com>",
        "Rhys van der Waerden <rhys.vdw@gmail.com>",
        "eiji.ienaga <e-ienaga@esm.co.jp>",
        "Doug Cone <nullvariable@users.noreply.github.com>",
        "Andrew Nicolaou <me@andrewnicolaou.co.uk>",
        "shimnex <shimdal@yahoo.ca>"
    ],
    "keywords": [
        "arduino",
        "raspberry pi",
        "raspberrypi",
        "usb",
        "serial",
        "serialport",
        "firmata",
        "robot",
        "spark",
        "spark core",
        "spark-io",
        "particle",
        "photon",
        "i2c",
        "raspberry pi",
        "rpi",
        "raspi-io",
        "intel galileo",
        "galileo",
        "galileo-io",
        "intel edison",
        "edison",
        "tessel 2",
        "pcduino",
        "MPU6050",
        "ADXL345",
        "ADXL335",
        "MMA8462Q",
        "MPL3115A2",
        "Weather Shield Arduino",
        "Weather Shield Photon",
        "BMP180",
        "Edison Arduino Block",
        "Edison GPIO Block",
        "Edison I2C Block",
        "Edison PWM Block",
        "RedBoard",
        "Ludus Protoshield",
        "Ludus Protoshield Wireless",
        "Ardumoto",
        "HMC5883L",
        "Speed controller",
        "PCF8575",
        "HTU21D",
        "Joystick",
        "Thumb Joystick",
        "Joystick",
        "16x2 LCD",
        "20x4 LCD",
        "LED",
        "Diffused LED",
        "RGB LED",
        "Infrared Sensor",
        "PIR Motion Sensor",
        "Hobby Motor",
        "Infrared Proximity Sensor",
        "LIDAR-Lite v2",
        "Ultrasonic Range Finder",
        "LV-MaxSonar-EZ0",
        "LV-MaxSonar-EZ3",
        "HRLV-MaxSonar-EZ0",
        "SparkFun Sensor Kit",
        "SparkFun Essential Sensor Kit",
        "Servo",
        "Continuous Rotation",
        "Metal Gear",
        "High Torque",
        "Hitec HS-805BB",
        "Hitec HS-425BB",
        "Hitec HS-422",
        "Hitec HS-646WP",
        "Hitec HS-85MG",
        "Hitec HS-625MG",
        "Hitec HS-35HD",
        "Hitec HS-755HB",
        "Temperature",
        "DS18B20",
        "TMP36",
        "ANALOG",
        "MMA7361",
        "MMA7660",
        "ESPLORA",
        "MPU-6050",
        "TINKERKIT",
        "MPL115A2",
        "DEFAULT",
        "EV3",
        "NXT",
        "ISL29125",
        "HMC6352",
        "GP2Y0A21YK",
        "GP2D120XJ00F",
        "GP2Y0A02YK0F",
        "GP2Y0A41SK0F",
        "2Y0A21",
        "2D120X",
        "2Y0A02",
        "OA41SK",
        "0A21",
        "0A02",
        "MCP23017",
        "MCP23008",
        "PCF8574",
        "PCA9685",
        "PCF8591",
        "MUXSHIELD2",
        "PCF8574A",
        "SI7020",
        "GY-521",
        "GY521",
        "MPR121QR2",
        "VKEY",
        "AT42QT1070",
        "MPR121",
        "QTOUCH",
        "JHD1313M1",
        "PARALLEL",
        "HD44780",
        "PCF8574T",
        "PCF8574AT",
        "LCD2004",
        "LCD1602",
        "LCM1602",
        "MJKDZ",
        "BLINKM",
        "HT16K33",
        "TSL2561",
        "ALS-PT19",
        "ALSPT19",
        "Shift Register",
        "74HC595",
        "Shift Register 8-Bit SN74HC595",
        "MCP9808"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/rwaldron/johnny-five.git"
    },
    "bugs": {
        "url": "https://github.com/rwaldron/johnny-five/issues"
    },
    "license": "MIT",
    "main": "lib/johnny-five",
    "engines": {
        "node": ">=0.10.0"
    },
    "dependencies": {
        "chalk": "latest",
        "color-convert": "~1.2.2",
        "ease-component": "latest",
        "es6-shim": "latest",
        "lodash.clonedeep": "^4.3.0",
        "lodash.debounce": "^4.0.3",
        "nanotimer": "0.3.10",
        "temporal": "latest"
    },
    "optionalDependencies": {
        "browser-serialport": "latest",
        "firmata": "latest",
        "serialport": "^4.0.0"
    },
    "devDependencies": {
        "async": "~0.9.0",
        "copy-paste": "^1.3.0",
        "coveralls": "^2.11.9",
        "grunt": "~0.4.5",
        "grunt-cli": "~0.1.13",
        "grunt-contrib-jshint": "~1.0.0",
        "grunt-contrib-nodeunit": "~0.4.1",
        "grunt-contrib-watch": "~0.6.1",
        "grunt-jsbeautifier": "~0.2.10",
        "grunt-jscs": "~2.3.0",
        "keypress": "latest",
        "mock-firmata": "latest",
        "nyc": "^10.2.0",
        "optimist": "~0.6.1",
        "shelljs": "^0.3.0",
        "sinon": "~1.10.2"
    },
    "scripts": {
        "test": "grunt",
        "test-cover": "nyc grunt nodeunit",
        "coveralls": "nyc --reporter=lcov grunt nodeunit && cat ./coverage/lcov.info | coveralls"
    },
    "browser": {
        "galileo-io": false
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
