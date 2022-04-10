let weather = {

    'apiKey' : '68c56902e46172358540ee099d8fe48b',
    fetchWeather : function(city){
        
        fetch(`https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=${this.apiKey}&units=metric`).then((response) => response.json()).then((data) => this.displayWeather(data));
    },
    displayWeather: function(data) {
        const name = data.name;
        const {icon , description} = data.weather[0];
        const {temp} = data.main;
        const speed = data.wind.speed;
      
        document.querySelector(".city").innerHTML = `Weather in ${name}`;
        document.querySelector('.icon').src = `http://openweathermap.org/img/wn/${icon}@2x.png`;
        document.querySelector(".description").innerHTML = description;
        document.querySelector(".temp").innerHTML = temp + " °C";
        document.querySelector(".wind").innerHTML =
        "Wind Speed : " + speed + " km/h";
        if(description == "clear sky")
        {
            document.querySelector('.container').style.backgroundImage = "url('clearsky.jpg')";
        }
        else if(description == "few clouds" || "scattered clouds" )
        {
            document.querySelector('.container').style.backgroundImage = "url('cloudy.jpg')";
        }
        else if(description == "shower rain" || "rain" )
        {
            document.querySelector('.container').style.backgroundImage = "url('rain.jpg')";
        }
        else if(description == "thunderstorm" )
        {
            document.querySelector('.container').style.backgroundImage = "url('thunderstorm.JPG')";
        }
        else if(description == "snow")
        {
            document.querySelector('.container').style.backgroundImage = "url('snow.jpg')";
        }
      
    },
    search : function(){
        this.fetchWeather(document.querySelector('.search-bar').value);
    },
    
};
document.querySelector('.search-btn').addEventListener('click',function(){

    weather.search();

});

document.querySelector('.search-bar').addEventListener('keyup',function(event){
    if(event.key == "Enter")
    {
        weather.search();
    }
})

