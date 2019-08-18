# Poopy 🐶💩

A 
participatory mobile APP made with **Ionic, MongoDB and Express** where you can search for the nearest poop-bag dispensers in the city of Madrid.

🏅 Codenotch Bootcamp team final project. Elaborated in 2 weeks. To be reviewed and upgraded in the future.


![Poopy](/schema.png "Poopy")

## Features

- Select a bin in the map and change its status from "There are no bags again 😡", to: "I'm safe, my dog can poo all over the park 💩".
- Add a bin to favorites and see all your favorite bags in an editable list. 
- Careful attention to the UX.  with Figma.
- Geolocalization with [API Google Maps] (https://developers.google.com/maps/documentation/?hl=es)
- Real data taken from the [Council of Madrid website](https://datos.madrid.es/portal/site/egob/menuitem.c05c1f754a33a9fbe4b2e4b284f1a5a0/?vgnextoid=fc4d8755e0bc9510VgnVCM2000001f4a900aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD&vgnextfmt=default)


## Setup

> Make sure you have globally installed: **Node**, **NPM**, **Ionic CLI** and **MongoDB**. And if you want to automatically restart your server: **Nodemon**.

1. Clone repository or download
2. Install **NPM** packages `npm i`
3. In the directory *APP* run `ioni serve` for a **ionic** dev server.
4. Resize your browser window to get a mobile device resolution.
5. **Import** the mongo **database** *poopyDB.json*
6. Start the **MongoDB server**. Easily done in windows by opening in your pc the directory *C:\Program Files\MongoDB\Server\3.6\bin* [Your mongodb installed location] and executing the file *mongod*. The default port for mongod is 27017.
7. In the directory *API* run `node main.js` to **connect to the database** or `nodemon main.js` if you want to restart your server when your code changes.
8. Access with the mail: test@test.com and password: test.
9. Enjoy 😊

## Authors
- [Apuluska](https://github.com/Apuluska)
- [Barby Marquina](https://github.com/barbymarquina)
- Me 🙋‍♀️ 