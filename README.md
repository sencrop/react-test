# Sencrop Coding Interview

The solutions can be implemented in React using this starter or some other way.
You are free to use the libraries of your choice.
You can also use the tools of your choice.

No pressure about time, what matters the most is code and product quality, not the end result :)

## React : Data fetching and display

The goal is to retrieve data from an endpoint and display this data.
The display can be a chart, a table or something else.

You can retrieve the weather data from this URL: https://sencrop-assets.s3.eu-central-1.amazonaws.com/data-examples/daily.json.

## Algo : Growing degree days

To estimate the growth and development of plants, we want to calculate the growing degree days for each day: 

https://en.wikipedia.org/wiki/Growing_degree-day

The calculation rule is as follows :

```
GDD = (TMax + TMin) / 2 - TBase
```
with :
- GGD : Growing degree days
- TMax : Temperature max of the day
- TMin : Temperature min of the day
- TBase : A constant depending of the crop.

If `GDD` is negative, then set it to zero.

| Crop  | TBase |
|-------|-------|
| Maize | 10    |
| Wheat | 5.5   |

# Dev 

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

