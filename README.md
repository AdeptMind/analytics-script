# analytics-script

Job running on 34.221.120.152
# Add cronjob
    0 7 * * * (cd /home/ubuntu/ashish/decathlon-daily-analytics-uploader; . venv/bin/activate;PYTHONPATH=. JOB_CLIENT_ENV=production python decathlon-analytics.py)  >> /home/ubuntu/cron1 2>&1
