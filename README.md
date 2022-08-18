# Geocoding in Python with Geoapify

This code sample shows how to geocode addresses with the [Geoapify Batch Geocoding API](https://www.geoapify.com/solutions/batch-geocoding-requests/). 

## Run the code sample

**Important!** Sign up on Geoapify, generate an API key and replace "YOUR_API_KEY" with your API key.

You can run the Python code either locally or through an online compiler. For example, [Programiz](https://www.programiz.com/python-programming/online-compiler/).

To run the code sample locally:
1. Install Python3 from the [official page >>](https://www.python.org/downloads/)
2. Install the "requests" module. You can find detailed instructions [here >>](https://pypi.org/project/requests/)
3. Execute the Python file with "`python3 batch_geo.py`"

## Geocode your addresses

You can geocode up to 6000 addresses/day with your API key for free. Learn [Geoapify Pricing policies here >>](https://www.geoapify.com/pricing/)
1. Put addresses as a string array to the `data` variable
2. Adjust the `timeout` and `maxAttempt` variables according to the size of the `data` array.
3. Run the Code Sample

## Learn more
* [Geoapify Location Platform](https://www.geoapify.com/) - APIs and geodata for Location-aware apps
* [Geocoding and Address Autocomplete playground](https://apidocs.geoapify.com/playground/geocoding/#autocomplete) - try the API without registration
* [Geocoding and Address Autocomplete documentation](https://apidocs.geoapify.com/docs/geocoding/) - learn more about API options and parameters