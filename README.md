# Professional-Portfolio-v2

The Professional Portfolio v2 is a page where I can display some of my projects, resume, and contact information. I made one a couple weeks ago and it was time to update some content and utilize what I have learned to upgrade my portfolio. This application will feature strcture from HTML and design from Bootstrap CSS.

<br>

## Getting Started

Open your favorite web browser and enter the following web address to access. 

>https://elliotpark410.github.io/Professional-Portfolio-v2/

<br>

## Prerequisites

1. Any of these internet browser will do 
<br>
<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/main-desktop-browser-logos.png" title="Browser Icons image" width = 200 >


2. To see code HTML, CSS, or JavaScript code, any of these Text editors will do
<br>
<img src="https://miro.medium.com/max/1400/0*MyAfggJM7yH40Sdx." title="Text Editor Icons image" width = 200px>

<br>

## Installing

To install this code, use Github's guidlines to clone the repository
<br>

Here is a link to the Github repository
>https://elliotpark410.github.io/Weather-Dashboard/

<br>

## Screenshots 

<img src="Weather Dashboard screenshot.png" title="Weather Dashboard screenshot" width = 700px>

<br>

## Built With

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

<br>

## Code Snippets

This code snippet shows how you can create an HTML content using jQuery and CSS Bootstrap

* jQuery allows user to dynamically generate HTML code within JavaScript with $(`EnterHTMLContentHere`);

* Bootstrap CSS has pre-built cards with CSS styling that you can grab from their website


```

var fiveDayForecastCard = $(`
    <div class="pl-3">
        <div class="card pl-3 pt-3 mb-3 bg-primary text-light" style="width: 12rem;>
            <div class="card-body">
                <h5>${dateFiveDayForecast}</h5>
                <p>${iconURLFiveDayForecast}</p>
                <p>Temperature: ${cityWeatherFiveDayForecast.temperature} °F</p>
                <p>Humidity: ${cityWeatherFiveDayForecast.humidity}\%</p>
            </div>
        </div>
    <div>
`);

$("#five-day-forecast").append(fiveDayForecastCard);

```

 <br>

## Deployed Link

* [https://elliotpark410.github.io/Weather-Dashboard/](#)

<br>

## Learning Points

* How to use jQuery API, and Bootstrap API

<br>

* How to fetch and parse data from OpenWeather API

<br>

* How to create dynamically generated HTML content in JavaScript with jQuery

<br>

* How to persist data with local storage

<br>

## Authors

* **Elliot Park** s

- [Link to Work Weather Dashboard application](https://elliotpark410.github.io/Weather-Dashboard/)
- [Link to Github](https://github.com/elliotpark410)
- [Link to LinkedIn](https://www.linkedin.com/in/elliot-park/)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

<br>

## License

This project is licensed under the UC Berkeley Extension Program 

<br>

## Acknowledgments

* Thank you to Jerome Chenette, Manuel Nunes, Daniel Chicchon, Brittany Crosthwait for their help!