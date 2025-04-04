# Background Image Removal Application

This project provides a web application to remove backgrounds from images. It's based on a forked repository with adjustments made to ensure compatibility and functionality.

**Note:** This project required adjustments to the original repository's dependencies to resolve version conflicts.

## Key Changes:

* Adjusted `requirements.txt` to align with compatible versions of dependencies (specifically Flask and rembg).
* Added `onnxruntime` as a necessary dependency (installed separately due to initial `requirements.txt` conflicts).

## Installation and Setup:

The following steps outline the installation and setup process for this application on an Ubuntu environment.

1.  **Switch to Root User:**

    ```bash
    sudo -i
    ```

2.  **Update Package Lists:**

    ```bash
    apt-get update
    ```

3.  **Install Python Virtual Environment:**

    ```bash
    apt install python3.12-venv -y
    ```

    ![Install venv](images/Screenshot 2025-04-04 020830.png_1.png)

4.  **Clone the Repository:**

    ```bash
    git clone [https://github.com/bigtheophilus/background-remover-python-app.git](https://github.com/bigtheophilus/background-remover-python-app.git)
    ```

    ![Clone repo](images/Screenshot 2025-04-04 021114.png_2.png)

5.  **Create and Activate Virtual Environment:**

    ```bash
    python3 -m venv .venv
    source .venv/bin/activate
    ```

    ![Create venv](images/Screenshot 2025-04-04 021340.png_3.png)
    ![Activate venv](images/Screenshot 2025-04-04 021531.png_3.png)

6.  **Install pip (if not already present):**

    ```bash
    apt install pip
    ```

    ![Install pip](images/Screenshot 2025-04-04 021709.png_4.png)

7.  **Verify pip Installation:**

    ```bash
    pip --version
    ```

    ![pip version](images/Screenshot 2025-04-04 022018.png_5.png)

8.  **Navigate to Application Directory:**

    ```bash
    cd background-remover-python-app/
    ```

9.  **Install Dependencies from `requirements.txt` (Initial Attempt):**

    ```bash
    python3 -m pip install -r requirements.txt
    ```

10. **View `app.py` and `requirements.txt` (for debugging/inspection):**

    ```bash
    cat app.py
    nano requirements.txt
    ```

11. **Re-install `requirements.txt` after adjustments:**

    ```bash
    python3 -m pip install -r requirements.txt
    ```

    ![requirements.txt view](images/Screenshot 2025-04-04 022630.png_6.png)
    ![requirements.txt nano](images/Screenshot 2025-04-04 022742.png_6.1.png)

12. **Install `onnxruntime` Separately:**

    ```bash
    pip install onnxruntime
    ```

    ![Install onnxruntime](images/Screenshot 2025-04-04 023046.png_7.png)

13. **Run the Application:**

    ```bash
    python3 app.py
    ```

    ![Run app](images/Screenshot 2025-04-04 023450.png_8.png)

## Issues Encountered:

* The original `requirements.txt` did not include `onnxruntime`, which is essential for the application.
* Installing `requirements.txt` as-is resulted in dependency conflicts.
* The solution was to:
    * Adjust the `requirements.txt` to compatible version.
    * Install `onnxruntime` separately using `pip`.

## Application Output:

![Application Output](images/Screenshot 2025-04-04 023812.png_9.png)
Collapse
   
   


   
   
   
   
   
   
   
   
   
   
   
