# react-i18n

```
npm install react-intl
npm install babel-plugin-react-intl
```

Quick overview

The first step is to wrap your application in the <IntlProvider> component:

```
<IntlProvider>
  <App />
</IntlProvider>
```

Then the content to translate: 

```
<p>
  <FormattedMessage
    id="Home.dayMessage"
    defaultMessage="It's a beautiful day outside."
  />
</p>
```

Aggregating default messages and translations into one file, for eg:

```
{
  "en": {
    "Weather.message": "Because it is sunny!",
    "Day.homeLink": "Go back home",
    "Home.header": "Hello, world!",
    "Home.dayMessage": "It's a beautiful day outside.",
    "Home.dayLink": "Click here to find out why!"
  },
  "es": {
    "Weather.message": "¡Porque es soleado!",
    "Day.homeLink": "Regresar a inicio",
    "Home.header": "¡Hola Mundo!",
    "Home.dayMessage": "Es un hermoso día afuera.",
    "Home.dayLink": "¡Haz clic aquí para averiguar por qué!"
  }
}
```



