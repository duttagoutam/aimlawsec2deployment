# aimlawsec2deployment
This small program is tested for deploying and running AIML in AWS EC2 instance
1. Copy app.py
2. Copy model.pkl
3. Copy template folder
4. run python app.py
5. Hit the URL from your browser http://<awsinstanceurl>:8080/
Software List:
	flask==1.1.1
	gunicorn==19.9.0
	itsdangerous==1.1.0
	Jinja2==2.10.1
	MarkupSafe=1.1.1
	Werkzeug==0.15.5
	numpy>=1.9.2
	scipy>=0.15.1
	scikit-learn>=0.18
	matplotlib>=1.4.3
	pandas>=0.19
