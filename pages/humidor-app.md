---
layout: default
---

# Humidor app

## Creations


**Stack**: React Native, Firebase, RN [BLE PLX][0]

**What**: Visually simple proof of concept for first connected humidor for the company, with functional bluetooth and cloud database.

**Why**: Quickly confirm core value prog and gain deeper of production requirements.

**Client**: [Case Elegance](https://caseelegance.com/collections/humidors)

Case Elegance is a quickly growing retailer with a strong presence on Amazon. They are a top seller of humidors which let cigar afficionados store their cigars in optimal conditions, much like a wine cellar.

They already have a modern, new clientele, and adding smart capabilities will allow them to serve their customers better and create tremendous corporate value.

I wrote this app from scratch in React Native with a bluetooth connection to an [off-the-shelf Nordic BLE 5 based hygrometer][1]. Development of a more sophisticated bluetooth module was underway.

**Hack**: The spec requested various *averages* for the data: hourly, 7 hours, 24 hours, weekly, monthly. As I was writing the code, I realized that we did not have such old data during these early testing phases, and that I already had the code done to work in a dynamic fashion. By making that visible, I was able to shave development time while still enabling us to get a feel for various averages (add confidence to the hypothesis).


[0]: (https://github.com/Polidea/react-native-ble-plx)
[1]: (https://www.fanstel.com/buy/bwg832f-g6fdz-lxr94-y6xzz)
## Screenshots:

![app](/assets/img/humidor/app.png){:class="img-responsive":height="112.5px" width="243.6px"}

*Note the dynamic Average showing .09 hours, and the button to manually refresh.*


![icon](/assets/img/humidor/icon.jpeg){:class="img-responsive":height="112.5px" width="243.6px"}

*App icon - based on existing collateral, still helps to make it feel real*