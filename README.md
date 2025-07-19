# 🌬️ Wind Turbine Blade Design & Analysis

This project is a Python-based BME analysis and calculation for **horizontal-axis wind turbine (HAWT)** blades.
It calculates blade parameters such as chord length, angle of attack, and other geometric and aerodynamic properties based on user inputs.

## 📊 Features

- Takes essential wind turbine parameters as input
- Computes blade characteristics across multiple sections
- Tabulated output for clear visualization
- Uses numerical and tabular libraries like `numpy` and `tabulate`

## 🧮 Parameters

The user is prompted to enter the following values:

- `AOA` – Angle of Attack (degrees) --->`7`
- `Lambda` – Tip Speed Ratio (TSR) --->`6`
- `B` – Number of Blades --->`3`
- `Cl` – Lift Coefficient --->`1.29`
- `R` – Rotor Radius --->`1200`
- `N` – Number of Sections --->`11`
- `r[]` – Local radius for each blade section --->`200,300....1200`


## ▶️ How to Run

Open the notebook in Jupyter or any notebook-compatible IDE and execute the cells. You'll be prompted for inputs directly in the notebook interface.

## 📁 Files

- `WindTurbine.ipynb` – Main Jupyter Notebook for blade analysis

## 📌 Sample Output (Tabular Format)

```
+---------+------------------------+------------------------+------------------+--------------+----------+-------------+-------------+------------------------+------------------------------+
| section | local_radius_of_blades | local_tip_speed_ratio  | relative_angles  | chord_length | solidity | pitch_angle | twist_angle | axial_induction_factor | tangential_induction_factor  |
+---------+------------------------+------------------------+------------------+--------------+----------+-------------+-------------+------------------------+------------------------------+
|    1    |         200            |           1            |       30         |    174.01    |  0.415   |     23      |    23.69     |         0.317          |             0.183           |
|    2    |         300            |          1.5           |      22.46       |    147.78    |  0.235   |    15.46    |    16.15     |         0.324          |             0.095           |
|    3    |         400            |           2            |      17.71       |    123.11    |  0.147   |    10.71    |     11.4     |         0.328          |             0.051           |
+---------+------------------------+------------------------+------------------+--------------+----------+-------------+-------------+------------------------+------------------------------+

```

## 🧑‍💻 Technologies & Tools Used

[![My Skills](https://skillicons.dev/icons?i=py,vscode)](https://skillicons.dev)


---

## 📸 Preview

Here’s how the page looks:

![Home Page 1 Preview](HomePage1.png) 
![Home Page 2 Preview](HomePage2.png) 
![AllJobs Page Preview](AllJobs.png) 
![Feedback Page Preview](Feedback.png) 
![SignUp Page Preview](SignUp.png) 
![SignIn Page Preview](SignIn.png) 
![PostJob Page Preview](PostJob.png) 
![EditJob Page Preview](EditJob.png) 
![About Us 1 Page Preview](AboutUs1.png)
![About Us 2 Page Preview](AboutUs2.png)
