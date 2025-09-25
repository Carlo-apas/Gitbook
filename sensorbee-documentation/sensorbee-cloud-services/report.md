# Report

***

This page provides a report on the values polled by the device’s sensors. The report includes data on temperature, humidity, air quality parameters like particulate matters and particle count, and other relevant metrics. The purpose of this report is to help track and analyze the data collected by the sensors, identify trends, and make informed decisions about how to improve environmental conditions. The report is updated on a regular basis to ensure that the most recent data is always available.

The result can be downloaded as a CSV file for further analysis. Additionally, it can be used as a template for smart city projects that require environmental monitoring.

#### Available Filters: <a href="#id-18fdf7df8eed43fd9fad0f3d13271a95" id="id-18fdf7df8eed43fd9fad0f3d13271a95"></a>

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkY0ODRmODEwMy0zOTE4LTRhZDktYmNlOC01MzNiNWFiZTEwMzMlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9OWM4MzE3YmEtZmZkYi00Njg0LWE4M2EtZmJiNzk0ZmE5YThmJmNhY2hlPXYyJndpZHRoPTEyNDkuOTUwMDczMjQyMTg3NQ==" alt="Figure 1 - Available filters"><figcaption><p>Figure 1 - Available filters</p></figcaption></figure>

* Installations
* You can select here the specific installation / device to view.
* Date From & Date To
* These are datetime pickers that allow you to specify a particular range’s datetime from and datetime to.
* Range Picker
* These are quick range filters that you can choose if you opted not to specify the datetime from and datetime to.
* Granularity / Aggregate
* You can choose the level of granularity from this filter:
* Raw - The report will contain raw data per posting interval.
* Hourly - The report will contain aggregated / averaged data per hour.
* Daily - The report will contain aggregated / averaged data per day.

#### Result: <a href="#cc261e794ccd43de94537d7db34397d0" id="cc261e794ccd43de94537d7db34397d0"></a>

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkZhNzk1MDczNy1iYjQ3LTRiMWEtOTI4MS1jOGE0MGE2NzE2OWElMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9OGRjOThmZmQtNDlkNy00MzJmLWI1NTItZWNlNjhjY2YzNTUxJmNhY2hlPXYyJndpZHRoPTEyNDkuOTI1MDQ4ODI4MTI1" alt="Figure 2 - Report Grid"><figcaption><p>Figure 2 - Report Grid</p></figcaption></figure>

The result will be displayed on a paginated grid, wherein each page consists of up to 1000 rows. The grid’s column arrangement follows the Sensorbee Smart City template wherein all significant parameters for air quality and environment monitoring are set in placed, and their values will be filled in according to the available sensors connected to your device.

#### Smart City Template <a href="#b4f0efed77eb4064a4c626200100a779" id="b4f0efed77eb4064a4c626200100a779"></a>

The smart city template is a report template that presents all significant air quality and environment parameters useful for monitoring and understanding the status of the environment. Sensor values that are polled by the sensors connected to your device will then be mapped out to this template. Only the sensor columns of the sensors connected to your device will have values, while the rest will just be blank.

The template arrangement is fixed and will only be updated when a new column is added to the right.

#### Available Parameters: <a href="#a0c8f9d74e7b45ac822c9f4efde41912" id="a0c8f9d74e7b45ac822c9f4efde41912"></a>

Installation / Base Unit Details:

* `installation_id`
* \<string> The installation id assigned to the device.
* `installation_name`
* \<string> The installation name assigned to the device.
* `installation_site`
* \<string> The installation site assigned to the device. _Note: this is not yet configurable from the portal_
* `bu_serial`
* \<string> The serial of the device.
* `bu_endpoint`
* \<string> The endpoint name of the device registered in the LwM2M server.
* `gps_mode`
* \<number> The GPS mode activated in the device. _Note: this is not yet configurable from the portal_
* `polling_interval`
* \<number> The polling interval set in the device’s settings. _Note: the value is not yet available in the report._
* `posting_interval`
* \<number> The posting interval set in the device’s settings. _Note: this is not yet configurable from the portal._

**Sensor and health data:**

* `dataset_id`
* \<number> The unique identifier / counter assigned to each payload. This is useful for tracing and debugging data gaps. _Note: this feature is not yet available._
* `timestamp`
* \<number> The timestamp when the sensor values were polled.
* `battery`
* \<number> The device’s battery percentage.
* `gps_duration_fix`
* \<number> Refers to how long a GPS fix was obtained.
* `gps_latitude`
* \<number> GPS latitude
* `gps_longitude`
* \<number> GPS Longitude
* `gps_speed`
* \<number>Refers to how fast the vehicle was moving with the device on it. Applicable only if the device is moving or positioned on top of a mobile unit.
* `gps_accuracy`
* \<number> Refers to how accurate the device position is in terms of percentage.
* `pm0_1`
* \<number> Level of particulate matter 0.1 measured by the air quality sensor.
* unit of measurement: µg/m³
* `pm0_3`
* \<number> Level of particulate matter 0.3 measured by the air quality sensor.
* unit of measurement: µg/m³
* `pm0_5`
* \<number> Level of particulate matter 0.5 measured by the air quality sensor.
* unit of measurement: µg/m³
* `pm1_0`
* \<number> Level of particulate matter 1.0 measured by the air quality sensor.
* unit of measurement: µg/m³
* `pm2_5`
* \<number> Level of particulate matter 2.5 measured by the air quality sensor.
* unit of measurement: µg/m³
* `pm4_0`
* \<number> Level of particulate matter 4.0 measured by the air quality sensor.
* unit of measurement: µg/m³
* `pm5_0`
* \<number> Level of particulate matter 5.0 measured by the air quality sensor.
* unit of measurement: µg/m³
* `pm10_0`
* \<number> Level of particulate matter 10.0 measured by the air quality sensor.
* unit of measurement: µg/m³
* `pc0_1`
* \<number> Particle count of PM0.1 measured by the air quality sensor.
* unit of measurement: #/cm³
* `pc0_3`
* \<number> Particle count of PM0.3 measured by the air quality sensor.
* unit of measurement: #/cm³
* `pc0_5`
* \<number> Particle count of PM0.5 measured by the air quality sensor.
* unit of measurement: #/cm³
* `pc1_0`
* \<number> Particle count of PM1.0 measured by the air quality sensor.
* unit of measurement: #/cm³
* `pc2_5`
* \<number> Particle count of PM2.5 measured by the air quality sensor.
* unit of measurement: #/cm³
* `pc4_0`
* \<number> Particle count of PM4.0 measured by the air quality sensor.
* unit of measurement: #/cm³
* `pc5_0`
* \<number> Particle count of PM5.0 measured by the air quality sensor.
* unit of measurement: #/cm³
* `pc10_0`
* \<number> Particle count of PM10.0 measured by the air quality sensor.
* unit of measurement: #/cm³
* `particle_size`
* \<number> Particle size
* unit of measurement: µg
* `temp_aq`
* \<number> Temperature value measured by the air quality sensor.
* unit of measurement: °C
* `humidity_aq`
* \<number> Relative humidity value measured by the air quality sensor.
* unit of measurement: % RH
* `pressure_aq`
* \<number> Atmospheric Pressure measured by the air quality sensor.
* unit of measurement: hPa
* `noise_aq`
* \<number> Amount of noise in the environment measured by the air quality sensor.
* unit of measurement: dbA
* `voc_aq`
* \<number> Volatile organic compounds (VOC) index measured by the air quality sensor.
* unit of measurement: #
* `ambient_light`
* \<number> Amount of light in the environment
* unit of measurement: lx
* `no2_gas`
* \<number> Level of nitrogen dioxide measured by the air quality sensor.
* unit of measurement: ppm || ppb - if unit is pro2
* `o3_gas`
* \<number> Level of ozone measured by the air quality sensor.
* unit of measurement: ppm || ppb - if unit is pro2
* `so2_gas`
* \<number> Level of sulfur dioxide measured by the air quality sensor.
* unit of measurement: ppm || ppb - if unit is pro2
* `co_gas`
* \<number> Level of carbon monoxide measured by the air quality sensor.
* unit of measurement: ppm || ppb - if unit is pro2
* `solar_panel_power`
* \<number> 5v out voltage coming from the solar panel.
* unit of measurement: mV
* `wind_speed`
* \<number> Wind speed measured by the wind sensor
* unit of measurement: m/s
* `wind_direction`
* \<number> Wind direction in terms of degree angle.
* unit of measurement: deg
* `temp_external`
* \<number> Temperature value measured by external temperature tag.
* unit of measurement: °C
* `humidity_external`
* \<number> Relative humidity value measured by external humidity tag.
* unit of measurement: % RH
* `co2_gas`
* \<number> Level of carbon dioxide measured by the air quality sensor.
* unit of measurement: ppm
* `nox_aq`
* \<number> NOx index measured by the air quality sensor.
* `signal_strength`
* \<number> The average value of the received signal strength indication used in the current network bearer.
* unit of measurement: dBm
* `rain_depth`
* \<number> Measurement of the accumulated rainfall in millimeters (mm).
* unit of measurement:: mm
* `no_gas`
* \<number> Level of nitric oxide measured by the air quality sensor.
* unit of measurement: ppm || ppb - if unit is pro2
* `h2s_gas`
* \<number> Level of hydrogen sulfide measured by the air quality sensor.
* unit of measurement: ppm || ppb - if unit is pro2
* `x_axis_acceleration_rms`
* \<number> Root mean square (RMS) acceleration measured along the x-axis of the device. The RMS acceleration is a measure of the magnitude of the acceleration vector, averaged over time.
* unit of measurement: m/s2
* `x_axis_peak_component_particle_velocity`
* \<number> Peak velocity of a particle along the x-axis. It represents the highest speed reached by any particle during a particular period.
* unit of measurement: mm/s
* `x_axis_velocity_fft_peak_amplitude_frequency`
* \<number> Frequency at which peak amplitude occurs for velocity along the x-axis. It is determined using Fast Fourier Transform (FFT), a method that converts a signal from its time domain to a frequency domain.
* unit of measurement: Hz
* `x_axis_velocity_fft_peak_amplitude`
* \<number> Peak amplitude of the velocity along the x-axis. Amplitude is the maximum extent of a vibration or oscillation, in this case, the velocity of a particle.
* unit of measurement: mm/s
* `y_axis_acceleration_rms`
* \<number> Root mean square (RMS) acceleration measured along the y-axis of the device. The RMS acceleration is a measure of the magnitude of the acceleration vector, averaged over time.
* unit of measurement: m/s2
* `y_axis_peak_component_particle_velocity`
* \<number> Peak velocity of a particle along the y-axis. It represents the highest speed reached by any particle during a particular period.
* unit of measurement: mm/s
* `y_axis_velocity_fft_peak_amplitude_frequency`
* \<number> Frequency at which peak amplitude occurs for velocity along the y-axis. It is determined using Fast Fourier Transform (FFT), a method that converts a signal from its time domain to a frequency domain.
* unit of measurement: Hz
* `y_axis_velocity_fft_peak_amplitude`
* \<number> Peak amplitude of the velocity along the y-axis. Amplitude is the maximum extent of a vibration or oscillation, in this case, the velocity of a particle.
* unit of measurement: mm/s
* `z_axis_acceleration_rms`
* \<number> Root mean square (RMS) acceleration measured along the z-axis of the device. The RMS acceleration is a measure of the magnitude of the acceleration vector, averaged over time.
* unit of measurement: m/s2
* `z_axis_peak_component_particle_velocity`
* \<number> Peak velocity of a particle along the z-axis. It represents the highest speed reached by any particle during a particular period.
* unit of measurement: mm/s
* `z_axis_velocity_fft_peak_amplitude_frequency`
* \<number> Frequency at which peak amplitude occurs for velocity along the z-axis. It is determined using Fast Fourier Transform (FFT), a method that converts a signal from its time domain to a frequency domain.
* unit of measurement: Hz
* `z_axis_velocity_fft_peak_amplitude`
* \<number> Peak amplitude of the velocity along the z-axis. Amplitude is the maximum extent of a vibration or oscillation, in this case, the velocity of a particle.
* unit of measurement: mm/s
* `peak_particle_velocity`
* \<number> Peak velocity of a particle regardless of the axis. It represents the highest speed reached by any particle during a particular period.
* unit of measurement: mm/s

Sample Export CSV

***

Helpful?
