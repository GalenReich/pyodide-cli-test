# pyodide-cli-test

This is a repo for testing using command line tools with Pyodide. It demonstrates using the Bellingcat [Reddit Post Scraping Tool](https://github.com/bellingcat/reddit-post-scraping-tool/).

## Instructions

>[!IMPORTANT]
>Due to Cross Origin Resource Sharing (CORS) restrictions implemented by browsers, for this test to work, CORS checks must be turned off.
> 
>You can do this in Google Chrome with the [Cross Domain - CORS](https://chromewebstore.google.com/detail/cross-domain-cors/mjhpgnbimicffchbodmgfnemoghjakai) extension. For this demo it is recommended to just disable CORS checking for `reddit.com`.

Run `python3 -m http.server` in the root directory.

Navigate to the hosted address, usually `http://localhost:8000`

Open the browser console (`Ctrl-Shift-I` in Google Chrome) to view the output.

