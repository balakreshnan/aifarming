# Monitor vegetable garden and use AI

## Watch your vegetable garden and use AI to watch for plant health

## Architecture

![Architecture](https://github.com/balakreshnan/aifarming/blob/main/Architecture/aifarming.jpg "Architecture")

## Use Case

- Create your own monitoring system for home or small farms
- Use AI Camera to capture images
- Use the same camera to detect objects
- Also get sensors for soil
- Collect the images and sensors
- Save the data in cloud
- Create your analytics in cloud
- Analyze and improve your garden

## Architecture Explained

- Build your garden
- get a camera and set it up
- Make sure camera is ip capable and there is RTSP stream
- Get an IoT edge
- We can use Raspberry pi or local computer
- Connect the Edge to IoT Hub
- Send the data to cloud
- We can use stream analytics as ingestion to save the data
- Image can be captured and sent to storage directly
- Images doesn't need to go to IoT Hub
- Edge is secured but IoT hub
- for analytics we can use Azure Synapse Analytics to build your data analytics
- Use power bi to show your report
- We can use Power platform to enable actions