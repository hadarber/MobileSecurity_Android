
## Explanation of the Work Process

1. **Decompilation of APK**  
   I decompiled the APK file that the instructor uploaded to Moodle using the website [javadecompilers.com](https://javadecompilers.com).

2. **File Structure Extraction**  
   After extracting the file structure, I searched for the `AndroidManifest.xml` file and copied it to the new project I created in Android Studio.

3. **Identifying Activities**  
   In the `AndroidManifest.xml` file, I noticed that there are two activities in the project: `activity_menu` and `activity_game`. Therefore, the next step was to locate these activities among all the files, as well as their corresponding XML files.

4. **Missing Images**  
   In the XML file of the `activity_game`, I noticed that there were four missing arrow images. I searched for these images and added them to the project in the expected drawable folder.

5. **Fixing URL for Activity Menu**  
   To ensure the game could run, I found that `activity_menu` uses a URL that should be stored in the strings resource file. I copied the relevant string from the file directory to my project in the appropriate location. The URL was incorrect and needed to be fixed by removing the zero-width characters.

6. **Running the Game**  
   After this step, I was able to run the game. To understand the game rules, I reviewed the code and saw that the arrows needed to be pressed according to the values input in the ID modulo 4:
   - **Left** - 0
   - **Right** - 1
   - **Up** - 2
   - **Down** - 3

7. **Gameplay**  
   After starting the game, I entered my ID and pressed the arrows in order according to the modulo 4 digit values:  
   **[ID: 318434669]** → **[310030221]** → **[↓→←←↓←↑↑→]**

 
 [Screen_recording_20240704_144749.webm](https://github.com/hadarber/ex2_mobileSecurity/assets/102084058/fd374013-c4b2-4619-bf9e-912c4731fb0f)
