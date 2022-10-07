# Docker container for running Evilginx2

*Evilginx is an attack framework for setting up phishing pages. Instead of serving templates of sign-in pages lookalikes, Evilginx becomes a relay between the real website and the phished user. Phished user interacts with the real website, while Evilginx captures all the data being transmitted between the two parties.*

*Evilginx, being the man-in-the-middle, captures not only usernames and passwords, but also captures authentication tokens sent as cookies. Captured authentication tokens allow the attacker to bypass any form of 2FA enabled on user's account*

#### Phislets:

*Phishlets are new site configs. They are plain-text ruleset files, in YAML format, which are fed into the Evilginx engine*

### You can pull the image using the below command

```

docker pull vishnunair/docker-evilginx2

```

For more info: Check this [link](https://breakdev.org/evilginx-2-next-generation-of-phishing-2fa-tokens/)

## Legal disclaimer:

Usage of Evilnginx2 for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program. Only use for educational purposes.
