# April 14 In-Class Notes

easier to solder to solder

- tin the pads before you put the piece through and connect

how to clean flux? look in manual never ask the internet, everyone has opinions, cleaning for asthetic v necesifty

it will depend on the flux, so always read the data sheet!

98% isopropyl alc best for cleaning electronic stuff

flux is realy broad category

rosenflux from tee sap rather than acid flux used for plumbing

uploading to arduino is "programming"

"byte trackNumber;
if (digitalRead(4) = LOW && lastButtonState = HIGH && millis() - lastButtonTimestamp > 50) {
    trackNumber = 81;
    Serial.write(trackNumber)
    lastButtonState = LOW;
    lastButtonTimeStamp =millis();
}"

libraries can be used and debounce for you

ezbutton

any time dealing w time in arduino unsigned loop 32bit not including negatives so there is more room for positive #'s
