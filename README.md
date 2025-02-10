Weather Modeling using the Quadratic Model in the Waterfall Model
1. Requirements Gathering
We need a program that predicts weather using the formula:
w=0.5(t^2)−0.2h+wind−15
Inputs: Temperature t, Humidity h, Wind Speed wind
Output: Predicted weather value w

2. System Design
Function to calculate the weather value using the formula.
Take user input for t, h, and wind.
Display the result.

4. Implementation
Here’s the Python code:

def weather_prediction(t, h, wind):
    return 0.5 * (t ** 2) - 0.2 * h + 0.1 * wind - 15

t = float(input("Enter temperature (°C): "))
h = float(input("Enter humidity (%): "))
wind = float(input("Enter wind speed (km/h): "))
print(f"Predicted Weather Value: {weather_prediction(t, h, wind):.2f}")

4. Testing
Test with different values for t, h, and wind to check accuracy.
Example Test:
Input: t = 25, h = 60, wind = 10
Output: Predicted Weather Value = 298.50

6. Deployment
Run the program locally or deploy it as a simple command-line tool.

7. Maintenance
Update the formula or input/output handling based on user feedback or new requirements.
