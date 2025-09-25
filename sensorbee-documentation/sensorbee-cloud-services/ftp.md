# FTP

Each user account is granted access to an FTP folder where reports will be generated on a scheduled basis. This page allows the user to configure the report generation schedule based on the available parameters, wherein, the user must also select the base units where the report’s data will be sourced from.

#### FTP Credentials <a href="#ac622c306eea468282b7b3c5284ce976" id="ac622c306eea468282b7b3c5284ce976"></a>

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkY0NDEyNGMyNy03NjBlLTQwNWYtODJjNy0wMDE0NzEyMGE2ZDAlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9NjE0NmQxZTQtNzA5Yi00NGRiLTg2NTItZjI5N2Q5YWYzNTZjJmNhY2hlPXYyJndpZHRoPTEyNTIuNzc1MDI0NDE0MDYyNQ==" alt="Figure 1 - FTP Credentials"><figcaption><p>Figure 1 - FTP Credentials</p></figcaption></figure>

This section shows the FTP credentials that the user must use to access the FTP folder using tools like FileZilla, WinSCP, or others.

* Hostname
* The FTP server URL.
* Username
* The FTP access username.
* Password
* The FTP access password
* Port
* The FTP server port number.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkYwMzUwMDgyYi0wY2I3LTRiYjgtOTBlZC0zNjMwNzI2ZmZlYjIlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9YTk1ZWIyMTQtNmM5NS00MWQ0LWE3YzktNDY5MzQ0ZjY1ODE2JmNhY2hlPXYyJndpZHRoPTEyNTIuNzU=" alt="Figure 2 - FileZilla"><figcaption><p>Figure 2 - FileZilla</p></figcaption></figure>

#### Scheduled Reporting <a href="#id-5ee800b5351b4e77a6c9fa77f9cd24b2" id="id-5ee800b5351b4e77a6c9fa77f9cd24b2"></a>

Since the primary purpose of the FTP folder is for scheduled reporting, this page provides the user the capability to set the schedule as well as the filename format.

* **Frequency**
* &#x20;     Refers to how often the reports would be generated.
* Available frequencies:
* &#x20;    **Every End of Day** - The report generator will process and generate reports every midnight of the following day.
* &#x20;    **Every End of Week** - The report generator will process and generate reports every midnight of Sunday.
* &#x20;  **Every End of Month** - The report generator will process and generate reports every midnight of the first day of the following month.
* **Filename Format**
* &#x20;    Refers to the filename format of the report file.
* &#x20;    Available filename formats:
* &#x20;     **Report\_installationId\_YYYY-MM-DD-hhmmss-to-YYYY-MM-DD-hhmmss.csv**
* &#x20;       **Report\_installationId\_YYYYMMDDhhmmss-to-YYYYMMDDhhmmss.csv**
* &#x20;       **Report\_installationId\_YYMMMDD-hhmmss-to-YYMMMDD-hhmmss.csv**

#### Installations / Base Units <a href="#id-28e159e3199842e485aca5c69d39eea8" id="id-28e159e3199842e485aca5c69d39eea8"></a>

Shows the list of base units that you can enable to have scheduled reporting. The report generator will generate 1 report file per enabled base unit, on every interval of the report schedule.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkY5YzhlY2Y4My1mZjI5LTQzZDUtYTYzYi05NmI5NjJkMDg4NTIlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9ZGRhYmQwOGMtZjRmNS00YWQ3LThhYzgtNTIwYmE0NWNlNjU5JmNhY2hlPXYyJndpZHRoPTEyNTIuNzc1MDI0NDE0MDYyNQ==" alt="Figure 3 - Base Unit List"><figcaption><p>Figure 3 - Base Unit List</p></figcaption></figure>

#### Recent Reports <a href="#id-20b58e9660bf4100a7ab4b06f37bae04" id="id-20b58e9660bf4100a7ab4b06f37bae04"></a>

This list shows the most recent reports generated inside your FTP folder. It includes file information such as filename, file size, and file location / folder, which you can use to locate the file inside your FTP folder.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkYxNmJmZWRhMi02MzliLTQzOTgtYjRhYS1iNjg0ZTJjMzIzYjMlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9OGUwMmMwNDEtMzY5NS00NmQ2LTkyNzYtYjk3NTY2MmI4MjZlJmNhY2hlPXYyJndpZHRoPTEyNTIuNzU=" alt="Figure 4 - Recent Reports"><figcaption><p>Figure 4 - Recent Reports</p></figcaption></figure>

***

Helpful?
