Smart Human Emotion Detection — fixes
1. Replace the repository app.py with this app.py.
2. Replace requirements.txt with this requirements.txt. Ensure opencv-python is NOT also listed; use only opencv-python-headless.
3. Commit changes to GitHub and wait for Streamlit Cloud to rebuild. If needed, use Manage app > Reboot app.
4. Test webcam snapshot and photo upload on the deployed HTTPS website.
Notes:
- Streamlit camera_input captures a still image; it does not perform continuous live video detection.
- On mobile, browser camera permission is required.
- If libGL.so.1 persists, dependency conflict may remain in the environment; share the newest logs.
- This code is a proposed patch, not yet verified on your deployed website.
