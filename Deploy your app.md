## To deploy your app to App Engine, run the following command from within the root directory of your application where the app.yaml file is located:

>> gcloud app deploy

## Use Y for confirmation

# Refer for the expected output below

Beginning deployment of service [default]...
Some files were skipped. Pass `--verbosity=info` to see which ones.
You may also view the gcloud log file, found at
[/tmp/tmp.dYC7xGu3oZ/logs/2017.11.17/07.18.27.372768.log].
╔════════════════════════════════════════════════════════════╗
╠═ Uploading 5 files to Google Cloud Storage                ═╣
╚════════════════════════════════════════════════════════════File upload done.
Updating service [default]...done.
Waiting for operation [apps/qwiklabs-gcp-233dca09c0ab577b/operations/2e88ab76-33dc-4aed-93c4-fdd944a95ccf] to complete...done.
Updating service [default]...done.
Deployed service [default] to [https://qwiklabs-gcp-233dca09c0ab577b.appspot.com]

## You can stream logs from the command line by running:
>> $ gcloud app logs tail -s default

## To view your application in the web browser run:
>> $ gcloud app browse
