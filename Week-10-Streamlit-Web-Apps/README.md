# Building Web Apps with [Streamlit.io](https://streamlit.io/) 

Two new libraries...
* `pip install streamlit`
* `pip install pycaret`

[Link to app](https://zd123-streamlit-test-app-home-uq8qo8.streamlit.app/) we will be reviewing in class.

[Link to the github repo](https://github.com/zd123/streamlit-test-app) of that app. 

#### Setting up a virtual env to test your app out locally.
Navigate to the folder you want to build your app in. Then run the following.  

**Very important...**, when you are adding these code files to your github repo, **do not add the env folder at all**.  This is for local use only and will only slow down everything. 

```
mkdir env

python3 -m venv env/

source env/bin/activate

pip install -r requirements.txt
```

## Resources

0. Awesome student, Alex Chen, Example Apps
	* [Image Classifier Code](https://github.com/112523chen/Image-Classification-App), and [website](https://112523chen-image-classification-dem0.streamlitapp.com/)

	* [Data Viz Dashboard Code](https://github.com/112523chen/NYC-Airbnb-Data-Visualization-App), and [website](https://112523chen-nyc-airbnb-data-visualization-dem0.streamlitapp.com/)

0. [Streamlit Cheat-Sheet](https://docs.streamlit.io/library/cheatsheet)

1. Installable cool [3rd party components](https://streamlit.io/components) for streamlit.

2. Cool [pycaret](https://github.com/pycaret/pycaret/tree/master/examples) examples.