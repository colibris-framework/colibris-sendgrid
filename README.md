
# SendGrid email backend for [Colibris](https://github.com/colibris-framework/colibris)

## Install

    pip install colibris-sendgrid
    
## Usage

In `settings.py`, set:

    EMAIL = {
        'backend': 'colibrissendgrid.SendGridBackend',
        'api_key': 'yourapikey'
    }
