# crawler

give papa some data // computer vision applied to the world (for science and fun)

definitely not skynet. definitely.

## approach // poc

seattle/oregon/cali wildfire shit

- create crawlers for one stream of timestamped images of "open views"
- save and compress images with metadata
- correlate gps and surveillance
- run labeled dataset through basic cnn model (and then the full `vizinet` model)
- 🕳️

high-level research/motivation below. dunno if we'll get there

## why?

### 🇫 🇺 🇳

### track humans
- social distancing compliance via covid-19

### applying computer vision where it doesn't belong (maybe)

formulating earth air quality purely as a computer vision problem. sources of pm2.5 (particulate matter 2.5):
- wildfires
- factories
- power plants 
- cars
- cow burps and farts (yum)

this has benefits primarily for developing countries in place of maintaining expensive equipment for the same task. only proof point is making it more accurate so the tradeoff becomes clear and we can start using citizens as sensors for metrics that improve decision making for the good of the same populus

hypothesis: understanding exponential attenuation caused by particulate matter can help depth estimation systems and automonomous vehicles driving in adverse weather (not just on earth). potential for transfer learning here, but i could be wrong

## data sources

ideal collection locations: seattle (today, for wildfires), beijing, india

### realtime

- vizinet app (human, not so automated)
- https://www.earthcam.com/usa/washington/seattle/?cam=seattledowntown#gall-29
- https://www.tour-beijing.com/
- https://www.webcamtaxi.com/en/usa/california/homewood-mountain-resort.html

### static

- that one dataset i got access to from those beijing mobile app paper authors
- already crawled and correlated tour-beijing images
- https://github.com/awesomedata/awesome-public-datasets#climate-weather - some data to cross-reference here, probably

## existing tools

### crawlers & surveillance
- https://github.com/omic-ai/jailbreak - shameless plug
- https://github.com/scrapy/scrapy
- https://code.google.com/archive/p/surveillancesaver/ - looks like a good source/idea
- https://www.300dollardatarecovery.com/surveillancesaver-live-video-screen-saver-broadcasting-from-around-the-world/
- https://github.com/Pamoi/webcam-crawler
- https://github.com/cloudviz/agentless-system-crawler
- https://github.com/COVID19Tracking
- https://github.com/SuperBuker/CamHell
- https://github.com/yash-1708/Surveillance-crawler
- https://gist.github.com/jeffcrouse/7797275
- https://github.com/hakluke/hakrawler
- https://github.com/mykle1/MMM-EARTH-Live - from the iss, just for fun

### air quality
- https://github.com/Anukriti2512/Air-Quality-Prediction
- https://github.com/grtvishnu/Air-Pollution-Prediction-and-Forecasting
- https://github.com/ginberg/mlcapstone
- https://github.com/spatial-computing/air-quality-prediction-scala
- https://github.com/arnavbansal1/SatellitePollutionCNN
- https://github.com/arnavbansal1/SatellitePollutionCNN
- https://github.com/curiousest/predict-AQI
- https://github.com/curiousest/predict-AQI
- https://github.com/vikmreddy/deep-air
- https://github.com/luna983/air-quality-machine-learning
- https://github.com/ashishpatel26/Real-time-ML-Project
- https://github.com/txytju/air-quality-prediction
- https://github.com/Alro10/deep-learning-time-series
