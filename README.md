# Sencrop Weather Data

The solutions can be implemented in React using this starter or some other way.
You are free to use the libraries of your choice.
You can also you the tools of your choice.

No pressure about time, what matters the most is code and product quality, not the end result

## Weather data

You can retrieve weather data from these two URLs:

https://assets.sencrop.com/data-examples/daily.json for daily data \
https://assets.sencrop.com/data-examples/hourly.json for hourly data

You can display these data in a chart and a table.

## Growing degree days

To estimate the growth and development of plants, we want to calculate the growing degree days for each day: https://en.wikipedia.org/wiki/Growing_degree-day
The calculation rule is as follows :
```
GDD = Tmean - Tbase (with Tbase > 0 and Tmean = (Tmax + Tmin) / 2) 
```

For example, Tbase equal to 6 for maize and 0 for wheat.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

