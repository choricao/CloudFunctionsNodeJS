#### Add "Service Account User" role to Cloud Build

# Google Cloud Functions - Hello World sample

See:

* [Cloud Functions Hello World tutorial][tutorial]
* [Cloud Functions Hello World sample source code][code]

[tutorial]: https://cloud.google.com/functions/docs/quickstart
[code]: index.js

## Deploy and run the sample

See the [Cloud Functions Hello World tutorial][tutorial].

## Run the tests

1. Read and follow the [prerequisites](../../../../#prerequisites).

2. Install and run the [Google Cloud Functions Emulator](https://github.com/GoogleCloudPlatform/cloud-functions-emulator)

        npm install -g @google-cloud/functions-emulator
        functions start

3. Install dependencies:

        npm install

4. Set the following environment variables:

        export GCF_REGION=us-central1
        export FUNCTIONS_TOPIC=[YOUR_PUBSUB_TOPIC]
        export FUNCTIONS_BUCKET=[YOUR_CLOUD_STORAGE_BUCKET]

5. Run the tests:

        npm test
