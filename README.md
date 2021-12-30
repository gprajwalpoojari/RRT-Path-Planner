# Steal the soda

## About the project
The soda starts trapped inside a chamber in the vending machine, and must be maneuvered past two barriers to get outside. The goal of this project is to implement an RRT type motion planner to steal the soda.

## About the environment
The environment consists of the vending machine interior, with the main chamber and two barriers connected. Each barrier has a window, just barely large enough to fit a soda can. These windows are misaligned, as an anti-theft measure that must be defeated. The soda can is a standard 12 oz. aluminum beverage can, modeled as a perfect cylinder with
a diameter of 52 mm and height of 122 mm. The main chamber of the vending machine is a cube 1 meter on a side. The first barrier is on the far wall, with an opening with its center 200 mm from the top. The second barrier is offset 250 mm from the first, with an opening with its center 200 mm from the bottom. Both windows are squares, 150 mm on a side, and aligned with the centerline of the inner chamber, along the axis normal to the barriers. A sample of the environment is shown below:
![Capture](https://user-images.githubusercontent.com/53962958/147783728-3228e148-a74c-4540-9aa7-6af992a6e64c.PNG)
