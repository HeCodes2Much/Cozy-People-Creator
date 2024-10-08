# [Cozy People Asset Pack](https://shubibubi.itch.io/cozy-people) by [shubibubi](https://shubibubi.itch.io)

To use `serve.py` along with `Generator.html` to create sprites from the Cozy People Asset Pack, follow these steps:

### Prerequisites

1. **Download the Asset Pack**: Ensure you have the Cozy People Asset Pack downloaded and that you have cut up the sprites into usable parts. Since you mentioned you can't share the package, make sure you respect the usage rights.
   
2. **Python Installed**: Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

3. **Basic Files Setup**:
   - You should have `serve.py` and `Generator.html` in the same directory.
   - Place your cut-up sprite images in a folder that will be referenced by `Generator.html`.
  
### Download Files

1. Download files using git. 
   ```bash
   git clone https://github.com/HeGames2Much/Cozy-People-Creator.git
   ```

2. Download from page.
   [Cozy-People-Creator.zip](https://github.com/HeGames2Much/Cozy-People-Creator/archive/refs/heads/main.zip)

### Steps to Create Sprites

![image](https://github.com/user-attachments/assets/64612507-39c9-452c-9b07-0b8c2e168c18)

Each of these folder should have a file named `32x32` with the files inside before following along below.

1. **Setting Up the Server**:
   - Open your terminal (Command Prompt, PowerShell, Terminal, etc.).
   - Navigate to the directory where `serve.py` and `Generator.html` are located using the `cd` command. For example:
     ```bash
     cd path/to/your/directory
     ```

2. **Running the Server**:
   - Run the Python server by executing the following command:
     ```bash
     python serve.py
     ```
   - This will start a local server, usually accessible at `http://localhost:8000` (or another port, depending on your script configuration).

3. **Accessing the HTML File**:
   - Open a web browser and go to the URL provided by your terminal (e.g., `http://localhost:8000/`).
   - This will load the `Generator.html` page, where you can interact with the sprite generator.

4. **Using the Generator**:
   - **Load Sprites**: In the Generator interface, you should have an option to load or select your cut-up sprite images. Choose the images you want to work with.
   - **Configure Settings**: Adjust any settings or parameters available in the generator to customize how the sprites will be created. This might include options like size, orientation, and any special effects.
   - **Generate Sprites**: Click the button to generate the sprites. The generator will process your selections and produce the output based on your configuration.

5. **Exporting Sprites**:
   - Once the sprites are generated, there should be an option to export them. Follow the prompts to save your generated sprites to your desired location.

### Additional Notes

- Make sure that all file paths within `Generator.html` correctly point to where your sprite images are located.
- As the user currently you will need to slice the sprites up yourself as i am not able to share them I will ask Shubibubi to offer the sliced ones on there page.


By following these steps, you should be able to successfully use `serve.py` along with `Generator.html` to create and manage your sprites from the Cozy People Asset Pack. If you have any questions or run into issues, feel free to ask!
