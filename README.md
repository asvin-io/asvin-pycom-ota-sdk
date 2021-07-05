# asvin-pycom-ota-sdk
Pycom SDK to integrate over the air update through asvin platform


Find tutorial at https://asvin.readthedocs.io/en/latest/tutorials/pycom-ota.html

+ To do OTA updates the file to be updated should contain the following lines:

    ```python
    path="/flash/config.py"
    version = "0.0.1"
    """
    OTA Config File
    """
    ```