# random

# cool stuff to try
# Infrared Camera
https://www.raspberrypi.org/learning/infrared-bird-box/worksheet/

## Scope of the project (What is the desired outcome?)
	[Y] Remote Viewing?
	[Y] Remote Archive Interrogation?
	[?] Offsite Backup of Results?
	[?] Facial Fingerprinting?
	[?] Text Recognition? (ANTI-CAPTCHA)

## Technical Methods
### Motion
#### Includes:

Motion detection

Recording when motion is detected (images and video)

Live video feed shown at localhost:8180 (double check that)

#### Potention problems forseen:

Can I inject automated-analysis and manipulation of data before being streamed to localhost:8180

#### How can I overcome:

If I just use the images (.jpg) and run facial fingerprinting over them; that should suffice.
Results can be archived and displayed at a later date with information overlayed.

### Alternative Methods?

# Webmail Server
## Tutorial
	http://arstechnica.com/information-technology/2014/02/how-to-run-your-own-e-mail-server-with-your-own-domain-part-1/

	http://arstechnica.com/information-technology/2014/03/taking-e-mail-back-part-2-arming-your-server-with-postfix-dovecot/

	http://arstechnica.com/business/2014/03/taking-e-mail-back-part-3-fortifying-your-box-against-spammers/

	http://arstechnica.com/information-technology/2014/04/taking-e-mail-back-part-4-the-finale-with-webmail-everything-after/


## Look into SPF and DMARC
Protection againt spoofed emails

From Google:

What is an SPF record in DNS? An SPF record is a type of Domain Name Service (DNS) record that identifies which mail servers are permitted to send email on behalf of your domain. The purpose of an SPF record is to prevent spammers from sending messages with forged From addresses at your domain.

## Thoughts
What is the intention with the end results; will I run all my email through here ?
