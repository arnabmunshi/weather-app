# Weather App

### Create App

```
expo init my-project
```

### Installed Dependencies

```
npm i expo-location @react-native-picker/picker react-native-dotenv
```

### Environment Variable Setup

#### Step #1

Add this line on `babel.config.js` file

```javascript
plugins: [["module:react-native-dotenv"]];
```

#### Step #2

Create a `.env` file on the project root

```
WEATHER_API_KEY="API KEY"
```

#### Step #3

Import the package

```
import { WEATHER_API_KEY } from "@env";
```

#### Step #4

Add `.env` file on `.gitignore` file
