# hello-functions
Hello World! Function using Python.

Install Google Cloud SDK

    https://cloud.google.com/sdk

Clone repository

    git clone https://github.com/davideconsonni/hello-functions.git
    cd hello-functions/

Build Cloud Function

    gcloud functions deploy hello_http --runtime python38 --trigger-http --allow-unauthenticated

Test the endpoint

    curl https://us-central1-{YOUR-PROJECT-ID}.cloudfunctions.net/hello_http?name=Bob