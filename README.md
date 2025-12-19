# Spectro Denoise - Remove repetitive patterns from your images

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/J3J31N82KX)

Spectro Denoise is specialized image processing software. Use the Fast Fourier Transform (FFT) to remove repetitive patterns and unwanted artifacts from your images. It is ideal for photographers, designers, researchers, or anyone who needs to process images to improve their quality. It has multiple automation features and advanced manual controls, and supports colour and grayscale images. It's especially good at removing the halftone effect used in some printed images.

# EXECUTION
- Download the executable file “Spectro Denoise.exe” from the link provided by the developer.
- No installation required: simply run the “.exe” file by double-clicking it.
- If you use antivirus software, make sure it allows the file to run (false positives are common with .exe files).
- The executable includes all necessary dependencies.

# USER INTERFACE
Left panel:
- Buttons for manipulating images: 📁 Open, ❌ Close.
- Checkbox 🔧 to calculate the automatic filter.
- Filter intensity slider (0-100%).
- Brush size slider (1-100 pixels).
- Processing: The application automatically detects whether the image is in color or grayscale; this can be changed manually.
- 🛑 Clear selection button, removes all masks made with the brush.
- Buttons for ⚡ Process, 💾 Save.
    
Center panel:
- 🎆 Spectrogram: Shows the frequency representation of the image (FFT).
- 🏞️ Original: Shows the uploaded image without modification.
- ⚡ Processed: Shows the result after applying the filter.
    
# IMPORTANT
- It is only necessary to select the bright “stars” near the center of the spectrogram, not all of them. 
- If there are no clear frequency “peaks,” do not select anything, just click process and manually control the filter intensity. 
- If the result is too blurry, lower the filter intensity manually. 
- If the result still contains a lot of patterns/noise, increase the filter intensity manually.
- When processing very large images, it may take longer than normal; please be patient, the processing will continue without any problems.
