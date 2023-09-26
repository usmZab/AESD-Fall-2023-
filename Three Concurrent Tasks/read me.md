## Creation and Concurrent Execution of 3 Tasks
This is a sample code for the Creation and Concurrent Execution of 3 Tasks on the ESP32 MCU by using FreeRTOS's port for ESP32.

Note that it uses **xTaskCreatePinnedToCore()** API, as we have the option of pinning this new task to a specific core of the dual-core ESP32.  For the sake of demo, I have pinned these all to the same core.

Interesting execution behaviours are observed by commenting out **vTaskDelay()** API, e.g. from Task 1.

Please see the sample code.
